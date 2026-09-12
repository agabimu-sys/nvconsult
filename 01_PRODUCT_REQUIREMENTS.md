# ASTRA — NVConsult.eu PRODUCT REQUIREMENTS

## 1. Product positioning

NVConsult.eu is a destination-led platform for international candidates covering work, study, immigration and jobs.

Primary audience:
- non-EU candidates outside Canada/EU and other destination markets;
- EU candidates remain welcome.

Business model:
- SEO/organic traffic;
- practical jobs/study/immigration utility;
- consultation/service conversion.

Do not use aggressive sales claims. Do not guarantee immigration or employment outcomes.

## 2. Design system

The public website must be:
- modern;
- clean;
- premium but approachable;
- navy/blue identity;
- light/white content areas;
- strong typography;
- generous spacing;
- restrained rounded cards;
- clear CTAs;
- responsive;
- visually consistent on every public page.

The homepage and internal pages must look like one product.

Do NOT use the old Travisa template as the active design.

## 3. Main navigation

Use these concepts as first-class navigation:
- Explore
- Work
- Study
- Immigration
- Jobs
- Visa News
- Guides
- Success Stories
- About
- Search
- Check My Options

Immigration MUST remain a top-level section separate from Work and Study.

## 4. Country Explorer — critical feature

The Country Explorer is the signature discovery feature.

Technology:
- Leaflet interactive map.

Required:
- country search;
- Work filter;
- Study filter;
- Immigration filter;
- Jobs filter;
- region filters;
- country markers;
- marker hover/click interaction;
- country preview panel/card;
- link to country page;
- popular/featured destination cards below the map;
- responsive behavior.

Visual behavior:
- quiet and premium;
- not cluttered;
- approximately 5–7 major destinations can have prominent visible labels by default;
- other countries remain discoverable through search/filter/hover/click.

Mobile:
- simplified map interaction;
- prioritize search, filters, selection and country preview.

Initial curated destinations:
- Canada
- United States
- Australia
- New Zealand
- Japan
- United Kingdom
- Germany
- Czech Republic
- Netherlands
- Poland
- Austria
- Portugal

The map must NOT be a decorative image.

## 5. Country model

Country fields should support:
- name;
- slug;
- region;
- flag;
- image;
- description;
- work_enabled;
- study_enabled;
- immigration_enabled;
- jobs_enabled;
- featured;
- show_in_explorer;
- status;
- internal map coordinates;
- relationships to pathways, jobs, study programs, guides, Visa News and Success Stories.

Production source of truth should be the database/application data model. JSON fallback data, if retained, must not become a conflicting second production source.

Admin should expose:
- Show in Country Explorer;
- Featured;
- Status.

Ordinary admins should NOT have to manage latitude/longitude/GIS configuration.

## 6. Country pages

Each country page should support:
- overview;
- Work/work visas/work pathways;
- Jobs;
- Study/programs/scholarships;
- Immigration/pathways/PR/family/citizenship where relevant;
- Visa News;
- Guides;
- Success Stories;
- Compare;
- Check My Options;
- future-ready Cities capability;
- related content;
- consultation CTA.

## 7. Immigration

Immigration is a separate product section.

Supported conceptual categories:
- Skilled Immigration;
- Permanent Residence;
- Family Immigration;
- Business/Investor;
- Regional Programs;
- Citizenship.

Only publish categories/pathways actually supported by verified data.

Each pathway should support:
- overview;
- eligibility;
- job offer;
- education;
- experience;
- language;
- salary/income where relevant;
- documents;
- process;
- cost;
- timeline;
- family;
- long-term options;
- common mistakes;
- unsuitable cases;
- official sources;
- last verified;
- related jobs;
- related guides;
- related Visa News;
- CTA.

Never guarantee eligibility or approval.

## 8. Visa News

Visa News is separate from evergreen Guides.

Each news item should support:
- what changed;
- who is affected;
- what has not changed;
- what to do;
- NVConsult analysis;
- official sources;
- published date;
- last verified;
- country;
- pathway/category;
- related content.

AI may assist discovery/drafting, but a human must verify current policy before publication.

## 9. Guides

Guides should be evergreen and people-first:
- direct answer;
- requirements;
- process;
- costs;
- timeline;
- mistakes;
- who may be unsuitable;
- official sources;
- related content;
- CTA;
- author/reviewer;
- last verified.

## 10. Jobs

Preserve useful existing jobs functionality.

Job fields:
- title;
- company;
- country;
- city;
- region;
- sector;
- occupation;
- salary;
- currency;
- experience;
- education;
- language;
- sponsorship status;
- visa pathway;
- source;
- original URL;
- posted;
- expiry;
- status;
- featured;
- verified;
- last checked.

Sponsorship statuses:
- confirmed;
- likely/possible;
- work permit support;
- EU Blue Card eligible;
- not specified;
- no sponsorship.

Expired jobs MUST NOT appear in current listings.

## 11. Study

Support:
- study destinations;
- universities/institutions;
- programs;
- scholarships;
- study pathways;
- country relationships;
- guides/news;
- consultation/enquiry CTAs.

## 12. Check My Options

Inputs:
- nationality;
- age range;
- education;
- occupation;
- experience;
- language;
- goal;
- preferred destinations;
- budget;
- family situation where relevant.

Results:
- Strong potential;
- Worth investigating;
- Possible but challenging;
- Likely unsuitable.

Show reasons. No guarantees.

Questions, rules and relationships should be CMS/database controlled where practical.

## 13. Comparison

Allow 2–4 countries.

Use factual attributes. Do not use arbitrary stars without a transparent methodology.

## 14. Dynamic collections

Support:
- Automatic;
- Manual;
- Hybrid.

Examples:
- Healthcare Abroad;
- International Nurses;
- Jobs With Visa Sponsorship;
- Skilled Workers;
- Study in Europe;
- Canada Immigration;
- EU Blue Card;
- English-Speaking Jobs.

Manual pinning can override automatic sorting.

## 15. Content types

Support:
- Guide;
- Visa News;
- Job;
- Study Program;
- Success Story;
- Country;
- Pathway;
- Landing Page;
- Standard Page.

## 16. Taxonomies

Support:
- Country;
- Region;
- Category;
- Goal;
- Pathway;
- Occupation;
- Sector;
- Language;
- Audience.

Content can have multiple taxonomy terms.

## 17. CMS/admin

Admin must be real functionality, not a mockup.

Support management of:
- posts/content;
- categories/taxonomies;
- pages;
- countries;
- pathways;
- jobs;
- study programs;
- collections;
- options questions/rules;
- media;
- settings;
- navigation;
- social links;
- booking;
- SEO;
- reusable sections/components.

Roles:
- Super Admin;
- Editor;
- Jobs Manager;
- SEO Manager;
- Reviewer.

## 18. Page builder

Controlled section builder:
- add;
- remove;
- hide/show;
- reorder;
- duplicate;
- edit;
- reuse;
- save templates.

Reusable components:
- Hero;
- Rich Text;
- Image;
- Two Columns;
- Stats;
- Country Cards;
- Job Cards;
- Visa News Cards;
- Guide Cards;
- Pathway Cards;
- Study Program Cards;
- Success Stories;
- FAQ;
- Accordion;
- Timeline;
- Comparison;
- CTA;
- Newsletter;
- Video;
- Collection.

Do not create an unrestricted pixel-level builder.

## 19. Templates

Support:
- Country;
- Pathway;
- Guide;
- Visa News;
- Job;
- Study Program;
- Custom Landing Page;
- Standard Page.

## 20. Social

Configurable profiles:
- Facebook;
- Instagram;
- LinkedIn;
- X;
- YouTube;
- TikTok;
- WhatsApp;
- custom.

Sharing:
- LinkedIn;
- Facebook;
- X;
- WhatsApp.

Automatic publishing requires official OAuth/API integrations and real credentials. Secrets remain server-side.

## 21. Booking

Keep Cal.com.

Centralize:
- enabled;
- provider;
- embed/link mode;
- booking URL/event;
- CTA.

Do not scatter booking URLs through source files.

## 22. SEO

Support:
- SEO title;
- meta description;
- slug;
- canonical;
- OG title;
- OG description;
- OG image;
- index/noindex;
- breadcrumbs;
- author/reviewer;
- dates;
- related content;
- structured data.

Relevant schema:
- Organization;
- WebSite;
- BreadcrumbList;
- Article;
- NewsArticle;
- JobPosting.

## 23. Analytics

Support events:
- country_view;
- pathway_view;
- job_search;
- job_view;
- news_view;
- guide_view;
- comparison_started;
- options_check_started;
- options_check_completed;
- consultation_clicked;
- booking_started;
- booking_completed;
- pricing_view;
- newsletter_signup.

## 24. Trust

Do not publish unverified marketing metrics.

Existing claims such as 1K+ guided, 500+ placements, 15+ countries and 4.8 Trustpilot require verification and definitions.

## 25. Security

Required:
- server-side auth;
- password hashing;
- secure sessions;
- CSRF protection;
- validation;
- escaping;
- upload validation;
- role permissions;
- rate limiting;
- audit log;
- backup/rollback;
- secure secret storage.

Never:
- expose API keys in frontend;
- commit passwords/secrets;
- use hardcoded admin passwords;
- rely on client-side authorization;
- use browser localStorage as authoritative production CMS.

Any old exposed AI credential must be revoked/rotated and never reused.

## 26. Hosting

Target:
- Hostinger File Manager;
- MySQL;
- staging first;
- backup before deployment;
- SSL;
- secure environment configuration.

Local QA and live Hostinger QA are separate.

## 27. CV Maker

Preserve the useful CV Maker/CV Studio functionality and integrate it visually into the new NVConsult system.

## 28. Future extensibility

Architecture must allow future developers to add:
- content types;
- components;
- APIs;
- social providers;
- map layers;
- collection rules;
- analytics;
- AI workflows;
- city explorer;
- salary/cost-of-living;
- job importers;
- accounts/dashboard;
- multilingual support.

Do not build a one-off system that requires a full rewrite for every extension.
