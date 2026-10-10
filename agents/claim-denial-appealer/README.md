# Claim Denial Appealer

Analyzes insurance claim denial remark codes (CARC/RARC) and drafts formal appeal letters supported by clinical chart notes and coverage policies.

## Working Folder Structure

- Denial Notices & EOBs: `./denials/`
- Clinical Chart Notes: `./charts/`
- Appeal Packages: `./appeals/`

## Example Prompts

- "Analyze the insurance claim denial in ./denials/claim_eob_829.txt and identify the denial reason."
- "Draft a medical necessity appeal letter for CPT code 99214 denied under CARC 50."
- "What documentation is required to overturn this pre-authorization denial?"
