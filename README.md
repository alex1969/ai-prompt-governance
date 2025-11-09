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
2. Use the `prompt-data-dictionary.csv` to filter by domain, use case, or tags
3. Submit feedback or request new prompts using GitHub Issues:
   - [Prompt Feedback](../../issues/new?template=prompt-feedback.md)
   - [New Prompt Request](../../issues/new?template=new-prompt-request.md)

## Contributing
We welcome contributions from prompt engineers, domain SMEs, and governance leads. To Contribute:
- Fork the repo and create a branch
- Add or update prompt files using the universal template
- Update `prompt-data-dictionary.csv` with metadata
- Submit a Pull Request with a summary of changes

## Issue Templates

To streamline collaboration and governance, this repo includes GitHub Issue Templates:

- **Prompt Feedback** – Report issues, suggest improvements, or flag hallucination risks
- **New Prompt Request** – Propose new prompts with sample inputs, outputs, and use cases

These templates live in `.github/ISSUE_TEMPLATE/` and are automatically available when creating a new issue.

## How to Request a New Prompt

To propose a new prompt for inclusion:

1. Use the [New Prompt Request Form](https://github.com/alex1969/ai-prompt-governance/issues/new?template=new-prompt-request.md)
2. Include:
   - Prompt title and use case
   - Sample input and desired output format
   - Tags and domain (e.g., Legal, AML, Policy)
   - Any constraints or formatting needs

Your request will be reviewed by the Prompt Engineer and Governance Lead.

## Governance

All prompts follow a versioning and review workflow documented in `governance/`. Changes must be reviewed by domain SMEs and governance leads before approval.

## Contact

Maintained by Alexander Stevens. For questions or onboarding support, open an Issue or email [alexstevens1969@gmail.com].

