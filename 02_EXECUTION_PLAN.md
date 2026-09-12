# ASTRA — EXECUTION PLAN

## Phase 0 — Understand before editing
- Read all files in this Astra handoff folder.
- Inspect the actual source tree.
- Inspect the database schema.
- Inspect API/backend.
- Inspect public JS/CSS.
- Inspect admin.
- Inspect legacy only for reference.
- Do not make code changes yet.

Output internally:
- actual architecture;
- actual entry points;
- actual data sources;
- actual routes;
- actual reusable components;
- actual missing files/dependencies;
- actual security risks.

## Phase 1 — Stabilize foundation
Fix architecture problems before visual polishing:
- source-of-truth duplication;
- broken routes;
- missing referenced files;
- broken asset paths;
- inconsistent shared CSS/JS loading;
- backend/API inconsistencies;
- admin entry-point problems;
- security issues.

Do not delete potentially useful legacy assets until dependencies are checked.

## Phase 2 — Establish the public design system
Create/verify shared:
- header;
- navigation;
- footer;
- typography;
- spacing;
- buttons;
- cards;
- forms;
- badges;
- breadcrumbs;
- content layouts;
- CTA patterns;
- responsive breakpoints.

Then apply it consistently to EVERY public page.

Do not polish only the homepage.

## Phase 3 — Country Explorer
Complete the existing Leaflet implementation rather than replacing it unnecessarily.

Required:
- search;
- Work;
- Study;
- Immigration;
- Jobs;
- region filters;
- markers;
- marker interaction;
- country preview panel/card;
- country page link;
- featured cards;
- mobile behavior;
- central country data.

Verify all initial destinations.

## Phase 4 — Country and content relationships
Connect:
Country → Pathways → Jobs → Study Programs → Guides → Visa News → Success Stories.

No duplicated country records.

## Phase 5 — Immigration
Complete pathway templates and data relationships.

## Phase 6 — Jobs and Study
Complete filtering, detail pages, status/expiry logic, sponsorship labels, study programs and pathways.

## Phase 7 — Check My Options + Comparison
Implement rules-driven assessment and factual comparison.

## Phase 8 — CMS/Admin
Complete real server-side CMS and role permissions.
Verify admin UI matches actual API/database capabilities.

## Phase 9 — SEO / Analytics / Social / Booking
Complete centralized settings and tracking.

## Phase 10 — Security and production hardening
Perform security audit and remove insecure legacy behavior.

## Phase 11 — QA
Run:
- syntax checks;
- route checks;
- asset checks;
- API checks;
- responsive checks;
- functional tests;
- database tests;
- map tests;
- admin tests;
- SEO checks;
- security checks.

## Phase 12 — Deployment
Document and test Hostinger deployment separately.

## Development discipline
At the end of each phase:
- record what changed;
- record tests;
- record known limitations;
- update project status/changelog;
- do not silently mark incomplete features as done.
