name: New Prompt Request
about: Propose a new prompt for the library
title: "[Request] AML Red Flag Detection Prompt"
labels: new-prompt, triage
assignees: alexanderstevens
---

## Proposed Prompt Title
What should this prompt be called?

> AML Red Flag Detection

## Use Case
Describe the business or compliance task.

> Identify red flags in transaction descriptions for AML screening.

## Sample Input
Provide a realistic example.

> “Wire transfer to offshore account labeled ‘consulting fee’.”

## Desired Output Format
What should the model return?

```json
{
  "flagged": true,
  "risk_reason": "Unusual offshore transfer with vague purpose",
  "confidence_score": "0.87"
}
```
## Examples (Optional)
Include a few input/output pairs if available.

## Tags
Relevant keywords: AML, red flag, screening, risk

## Notes
Any constraints, formatting needs, or model preferences?

Should work with GPT-4 and Copilot. Output must be JSON.
