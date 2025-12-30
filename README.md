# S3 School Directory Repository

This repository contains published school files and data that are synced from the THI application.

## Structure

```
.
├── data/
│   ├── THI-directory_csv_master.csv          # Current Full listing of published schools
│   └── archives/                             # Historical CSV exports
│       ├── THI-directory_csv_master-20251018.csv
│       ├── THI-directory_csv_master-20251017.csv
│       └── ...
└── schools/
    └── {school-slug}/                        # Individual school folders
        ├── {slug}-directory.json             # School data in JSON format
        ├── {slug}-homepage.png               # Image of school homepage
        ├── {slug}-classicality-audit.md      # Full Classicality audit report (Markdown)
        ├── {slug}-classicality-audit.pdf     # Full Classicality audit report (PDF)
        ├── {slug}-classicality-abstract.md   # Abstract of Classicality audit (Markdown)
        └── {slug}-og-image.png               # Open Graph image
```

## Purpose

Files in this repository are automatically published from the main THI application when accounts meet all publishing criteria. The `publish` curation rule handles:

- Validation of required address fields
- Geocoding of school locations
- Verification of required files
- Population of grades and school type
- Publishing accounts and copying files to this repository
- Generating CSV exports of all published schools

Files are only copied if they don't exist or if their size or modification time has changed, preventing unnecessary updates.

## Maintenance

This repository is managed separately from the main THI application repository to allow for independent versioning and deployment of published content. The repository is automatically updated when the `publish` curation rule runs successfully.
