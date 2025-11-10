# ai-prompt-governance
Governance-aware prompt engineering library for Legal, Regulatory, and Compliance (LRMC) AI agents.

# Prompt Engineering Library for LRMC AI Agents

Welcome to the governance-aware prompt library for Legal, Regulatory, and Compliance (LRMC) AI enablement. This repository contains reusable, auditable prompt templates designed to support AI agent deployment across triage, document review, policy summarization, and compliance tracking.

## Folder Structure

- `prompts/`: Individual prompt files with metadata, examples, and output formats
- `templates/`: Universal prompt templates and reusable scaffolds
- `metadata/`: CSV files and dictionaries for prompt tracking and filtering
- `governance/`: Versioning policies, review workflows, and audit documentation
- `docs/`: Stakeholder onboarding guide, training materials, and governance reference
- `.github/ISSUE_TEMPLATE/`: GitHub-native issue forms for prompt feedback and new prompt requests

## 🛠 How to Use

1. Browse the `prompts/` folder for approved prompts
2. Use the `prompt-data-dictionary.csv` in `metadata/` to filter by domain, use case, or tags
3. Submit feedback or request new prompts using:
   - [New Prompt Request](https://github.com/alex1969/ai-prompt-governance/issues/new?template=new-prompt-request.md)
   - [Prompt Feedback](https://github.com/alex1969/ai-prompt-governance/blob/main/docs/prompt-feedback.md)
   
## Contributing
We welcome contributions from prompt engineers, domain SMEs, and governance leads. To Contribute:
- Fork the repo and create a branch
- Add or update prompt files using the universal template
- Update `prompt-data-dictionary.csv` with metadata
- Submit a Pull Request with a summary of changes

## Issue Templates

To streamline collaboration and governance, this repo includes GitHub Issue Templates:
- **[New Prompt Request](https://github.com/alex1969/ai-prompt-governance/issues/new?template=new-prompt-request.md)** – Propose new prompts with sample inputs, outputs, and use cases
- **[Prompt Feedback Form](https://github.com/alex1969/ai-prompt-governance/blob/main/docs/prompt-feedback.md)** – Report issues, suggest improvements, or flag hallucination risks

These templates live in `.github/ISSUE_TEMPLATE/` and are automatically available when creating a new issue.

## How to Request a New Prompt
1. Open an issue and title it: [New Prompt Request](https://github.com/alex1969/ai-prompt-governance/issues/new?template=new-prompt-request.md)
2. Include:
   - Prompt title and use case
   - Sample input and desired output format
   - Tags and domain (e.g., Legal, AML, Policy)
   - Any constraints or formatting needs
3. Alternatively, copy the - [New Prompt Request Template](https://github.com/alex1969/ai-prompt-governance/blob/main/.github/ISSUE_TEMPLATE/new-prompt-request.md) then open [New Prompt Request](https://github.com/alex1969/ai-prompt-governance/issues/new?template=new-prompt-request.md) paste in the copied template, and fill in details as needed.

## How to Submit Prompt Feedback
1. Open an issue and title it: [Prompt Feedback](https://github.com/alex1969/ai-prompt-governance/issues/new?template=prompt-feedback.md)
2. Include:
   - Prompt ID
   - One-sentence feedback summary
   - Input, output, and suggested fix
   - Any additional notes. 
3. Alternatively, copy the - [Prompt Feedback Template](https://github.com/alex1969/ai-prompt-governance/blob/main/docs/prompt-feedback.md) then open [Prompt Feedback](https://github.com/alex1969/ai-prompt-governance/issues/new?template=prompt-feedback.md) past in the copied template, and fill in details as needed. 

Your requests will be reviewed by the Prompt Engineer and Governance Lead.

## Governance

All prompts follow a versioning and review workflow documented in `governance/`. Changes must be reviewed by domain SMEs and governance leads before approval.
- [Governance Exception Request](https://github.com/alex1969/ai-prompt-governance/blob/main/governance/review-workflow.md)

## Contact

Maintained by Alexander Stevens. For questions or onboarding support, open an Issue or email [alexstevens1969@gmail.com].

