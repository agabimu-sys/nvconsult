# NVConsult.eu — Fresh Source + Astra Build Instructions

This repository contains the **actual original NVConsult.eu website source** supplied by the project owner,
plus the dedicated Astra implementation instructions.

## Source of truth

- The website source in this repository is the original source upload: `nvsion _public_html(1).zip`.
- The embedded `.git` history from that upload was intentionally excluded so this repository can be initialized as a fresh GitHub repository.
- The previous generated/packaged build archives are NOT part of this repository and must not be treated as source.

## Astra instructions

Read these files in this order before making changes:

1. `00_READ_FIRST_ASTRA.md`
2. `01_PRODUCT_REQUIREMENTS.md`
3. `02_EXECUTION_PLAN.md`
4. `03_REPOSITORY_FILE_MENU.md`
5. `04_ACCEPTANCE_TESTS.md`
6. `05_AI_HANDOFF_PROMPT.txt`

Astra must inspect the actual source before editing and must preserve useful existing functionality.
Do not treat old Travisa/template documentation as product requirements.

## Important

- Do not reintroduce the old Travisa visual design.
- Do not build a modern homepage while leaving internal pages inconsistent.
- Do not create dummy/test content as a substitute for implementation.
- Use one authoritative data model/source of truth.
- Keep secrets and credentials out of frontend code.
- Immigration content must never promise or guarantee eligibility/outcomes.
- Do not claim completion without evidence from tests or inspection.

## Repository layout

The active website source remains at the repository root to avoid breaking its existing relative paths.
Astra may reorganize the architecture during implementation, but must preserve working paths/dependencies or update them systematically.

`legacy-original-docs/` contains documentation from the original template/source package for reference only.
