# Prompt Library Versioning Policy

## Purpose
To ensure traceability, reproducibility, and governance compliance across all prompt updates.

## Version Format
Use semantic versioning: `v[major].[minor]`
- **Major**: Significant changes to prompt logic, structure, or output format
- **Minor**: Minor edits, example updates, metadata changes

## Examples
- `v1.0`: Initial release
- `v1.1`: Added new example
- `v2.0`: Changed output format from JSON to table

## Change Log Requirements
Each prompt update must include:
- Summary of change
- Author
- Date
- Rationale

## Approval Workflow
- Drafts must be reviewed by domain SME
- Approved prompts are tagged as `Approved`
- Deprecated prompts are tagged as `Deprecated` and archived

## Audit Readiness
- All prompts must maintain version history
- Changes must be documented in the `PromptVersions` table
