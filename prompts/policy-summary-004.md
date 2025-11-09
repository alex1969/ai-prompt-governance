# Prompt ID: POLICY-SUMMARY-004
## Title: Summarize Internal Policy for Stakeholder Briefing

**Domain**: Regulatory  
**Use Case**: Convert policy text into stakeholder-friendly summaries  
**Version**: v1.0  
**Owner**: Alexander Stevens  
**Status**: Approved  
**Tags**: policy, summarization, stakeholder, briefing

---

## Prompt

You are a regulatory analyst preparing a stakeholder briefing. Summarize the following internal policy section in plain language.

## Input
"""
Employees must report any conflict of interest involving vendors, clients, or personal relationships within 10 business days of discovery.
"""

## Instructions
1. Identify the core obligation.
2. Rewrite it in plain language.
3. Limit summary to 25 words.

## Output Format
```json
{
  "summary": "[Plain language summary]",
  "policy_type": "Disclosure | Conduct | Reporting"
}
```

## Example
Input: "Report conflicts of interest within 10 days." 
Output:
```json
{
  "summary": "Tell us about any personal or business conflicts within 10 days of noticing them.",
  "policy_type": "Disclosure"
}
```


