# ASTRA — REQUIRED REPOSITORY FILE MENU

The repository should expose the actual active source code, not hide the entire implementation inside ZIP archives.

## Root

```text
/
├── README.md
├── 00_READ_FIRST_ASTRA.md
├── 01_PRODUCT_REQUIREMENTS.md
├── 02_EXECUTION_PLAN.md
├── 03_REPOSITORY_FILE_MENU.md
├── 04_ACCEPTANCE_TESTS.md
├── PROJECT_STATUS.md
├── CHANGELOG.md
├── UI design.png
│
├── docs/
├── public/
├── admin/
├── api/
├── lib/
├── database/
├── data/
├── tests/
├── legacy/
└── reference/
```

## Public

```text
public/
├── index.html
├── countries.html
├── country-detail.html
├── work.html
├── study.html
├── immigration.html
├── jobs.html
├── job.html
├── visa-news.html
├── guides.html
├── post.html
├── pathway.html
├── success.html
├── check-options.html
├── compare.html
├── about.html
├── pricing.html
├── contact.html
├── resources.html
├── cv-maker.html
├── privacy-policy.html
├── cookie-policy.html
├── disclaimer.html
├── css/
├── js/
├── img/
└── lib/
```

The exact filenames may remain as implemented if changing them would break routing. The important rule is that there is one active public tree and one consistent design system.

## API

```text
api/
├── index.php
├── bootstrap.php
├── config.example.php
└── ...
```

Keep secrets outside committed source.

## Database

```text
database/
├── schema.sql
├── seed.sql
├── migrations/
└── ...
```

## Data

```text
data/
├── countries.json
├── content/
└── ...
```

JSON may be used for development/fallback only if it cannot conflict with the production database.

## Admin

```text
admin/
├── entry point
├── styles
├── scripts
└── ...
```

The admin frontend must actually exist if referenced by redirects or documentation.

## Legacy

```text
legacy/
└── original-site/
```

The original Travisa implementation belongs here and is reference-only.

## Reference

```text
reference/
├── UI design.png
└── migration/reference material
```

## Tests

```text
tests/
├── smoke/
├── api/
├── data/
└── ...
```

## Important
Do not move files merely to match this menu if the current application depends on paths. First map dependencies, then refactor safely.
