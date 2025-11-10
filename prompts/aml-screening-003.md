# Prompt ID: AML-SCREENING-003
## Title: Entity Risk Classification for AML Screening

**Domain**: Compliance  
**Use Case**: Classify entities based on anti-money laundering risk indicators  
**Version**: v1.0  
**Owner**: Alexander Stevens  
**Status**: Approved  
**Tags**: AML, entity screening, risk classification

---
```markdown
## Prompt

You are a compliance analyst screening entities for AML risk. Review the entity profile and classify its risk level.

## Input
"""
Entity: XYZ Holdings  
Jurisdiction: Cayman Islands  
Transaction Volume: $12M/month  
Known Affiliations: None  
PEP Status: No
"""

## Instructions
1. Assess risk based on jurisdiction, volume, and affiliations.
2. Classify as High, Medium, or Low risk.
3. Justify your classification in 1–2 sentences.

## Output Format
```json
{
  "risk_level": "High | Medium | Low",
  "justification": "[Concise explanation]",
  "confidence_score": "[0.0–1.0]"
}
```
## Example
Input: Entity in Panama with $20M/month and PEP status 
Output:
```json
{
  "risk_level": "High",
  "justification": "High transaction volume and PEP status in a high-risk jurisdiction.",
  "confidence_score": "0.88"
}
```
```
