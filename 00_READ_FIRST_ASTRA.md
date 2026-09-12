# ASTRA — READ THIS FIRST

You are continuing development of NVConsult.eu.

Your job is NOT to create another experimental redesign and NOT to patch the legacy website.

You must take the existing NVConsult 2026 implementation as the starting codebase, audit it, stabilize it, and complete it against the requirements in this repository.

## Absolute rules

1. The old Travisa template is LEGACY ONLY.
2. Never reintroduce the old Travisa public UI.
3. Do not make the homepage look modern while leaving internal pages on an older design.
4. All public pages must use one coherent NVConsult design system.
5. Do not create dummy/test/placeholder production content.
6. Do not duplicate country data between unrelated files.
7. The Country Explorer must use the same authoritative country data as country pages and related features.
8. Preserve useful existing functionality unless there is a documented technical reason to replace it.
9. Do not declare a feature complete merely because code exists.
10. Do not expose secrets in frontend code.
11. Do not make immigration guarantees.
12. Current policy/news information must be verified before publication.
13. Work in milestones and test every milestone.
14. Fix shared architecture problems at the shared level; do not create page-specific hacks.
15. Before deleting or replacing functionality, inspect its dependencies and document the decision.

## First action

Before changing application code:

- inspect the repository tree;
- inspect the existing NVConsult implementation;
- inspect the database schema;
- inspect API/backend files;
- inspect public JS/CSS;
- inspect admin files;
- inspect the legacy directory only to understand migration/reference material;
- compare the implementation with `01_PRODUCT_REQUIREMENTS.md`;
- produce an internal gap list grouped as IMPLEMENTED / PARTIAL / BROKEN / MISSING / DUPLICATED / LEGACY / SECURITY RISK.

Do not start a new framework or rewrite the whole application simply because parts are imperfect.

## Required outcome

The finished site must be a coherent NVConsult.eu product covering:

Explore / Country Explorer, Work, Study, Immigration, Jobs, Visa News, Guides, Success Stories, Check My Options, Country Comparison, CMS/Admin, Booking, CV Maker, SEO, analytics and social sharing.

The detailed requirements are in `01_PRODUCT_REQUIREMENTS.md`.

The required execution order is in `02_EXECUTION_PLAN.md`.

The required repository structure is in `03_REPOSITORY_FILE_MENU.md`.

The acceptance criteria are in `04_ACCEPTANCE_TESTS.md`.
