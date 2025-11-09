# Prompt ID: LRMC-TEMPLATE-001
## Title: <example: Classify Clause Risk Level>
**Domain**: Legal  
**Use Case**: modular and auditable template  
**Version**: v1.0  
**Owner**: Alexander Stevens

---

This template is modular and auditable — ideal for maintaining a **versioned prompt library**. You can adapt it for:
- Document review
- Case triage
- Regulatory mapping
- Compliance tracking
- Stakeholder Q&A agents

This can be used to build a few role-specific prompt variants (e.g., for AML screening, contract redlining, or policy summarization)?

[ROLE]
You are a [describe the role the model should assume, e.g., "compliance analyst specializing in GDPR risk assessment"].

[OBJECTIVE]
Your task is to [clearly state the goal, e.g., "analyze the following contract clause and classify its risk level"].

[CONTEXT]
This task supports [briefly describe the business or regulatory context, e.g., "automated triage of third-party vendor agreements for data privacy compliance"].

[INPUT]
Here is the input you will analyze:
"""
[Insert text, clause, document excerpt, or structured data]
"""

[INSTRUCTIONS]
Follow these steps:
1. [Step-by-step guidance, e.g., "Identify key risk indicators."]
2. [e.g., "Classify the clause as High, Medium, or Low risk."]
3. [e.g., "Justify your classification in 1–2 sentences."]

[OUTPUT FORMAT]
Respond using the following structure:
```json
{
  "risk_level": "High | Medium | Low",
  "justification": "[Concise explanation]",
  "confidence_score": "[0.0–1.0]"
}
```
[CONSTRAINTS]
Use plain language suitable for non-technical stakeholders.
Limit justification to 2 sentences.
Do not include disclaimers or assumptions unless explicitly asked.

[EXAMPLES] (Optional for few-shot prompting) 
Example 1: Input: "The vendor may transfer data outside the EU without prior notice." 
Output:
{
  "risk_level": "High",
  "justification": "Unrestricted data transfer violates GDPR Article 44.",
  "confidence_score": "0.92"
}

[REVIEW INSTRUCTION] (Optional for self-refinement) 
After completing your response, review it for clarity, completeness, and alignment with the instructions.
