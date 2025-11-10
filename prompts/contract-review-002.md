# Prompt ID: CONTRACT-REVIEW-002
## Title: Contract Clause Summarization for Legal Review

**Domain**: Legal  
**Use Case**: Summarize clauses for redlining and review  
**Version**: v1.0  
**Owner**: Alexander Stevens  
**Status**: Approved  
**Tags**: summarization, contract, redlining, legal

---

## Prompt

You are a legal assistant helping to summarize contract clauses for review. Your task is to extract the key obligation or restriction from each clause and present it in plain language.

## Input
"""
The licensee shall not sublicense, assign, or otherwise transfer the rights granted herein without prior written consent from the licensor.
"""

## Instructions
1. Identify the core restriction or obligation.
2. Rewrite it in plain language suitable for non-legal stakeholders.
3. Limit summary to 30 words.

## Output Format
```json
{
  "summary": "[Plain language summary]",
  "clause_type": "Restriction | Obligation | Permission"
}
```
## Example
Input: "The licensee shall not sublicense without consent." 
Output:
```json
{
  "summary": "You can’t transfer rights unless the licensor agrees in writing.",
  "clause_type": "Restriction"
}
```
## Notes
Use for redlining prep and stakeholder briefings.
Avoid legalese unless explicitly requested.
