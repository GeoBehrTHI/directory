# S3 School Directory Repository

This repository contains published school files and data that are synced from THI solutions

## Data

This stores the current live directory data file, along with archives of past files, and \_cursor files for future incremental updates.

## Placeholders

This stores placeholder images for schools that do not have a valid image.

NOTE: these should eventually be managed in the PayloadCMS.

## Schools

This stores the files for each school, including their abstract and audit MD files, and the PDF file.

NOTE: Images may be there, but at this time THI is only using placeholder images for schools.

## Structure

```
.
├── data/
│   ├── THI-directory_csv_master.csv            # Current Full listing of published schools
│   └── archives/                               # Historical CSV exports
│       ├── THI-directory_csv_master-20251018.csv
│       ├── THI-directory_csv_master-20251017.csv
│       └── ...
│   └── cursors/                               # Historical CSV exports
│       ├── _cursor_20251018.json.             # Cursor for incremental updates
│       └── ...
├── placeholders/
│   ├── placeholder-elementary-0.png            # Placeholder image 0 for elementary schools
│   ├── placeholder-elementary-1.png            # Placeholder image 1 for elementary schools
│   ├── ...
│   ├── placeholder-elementary-9.png            # Placeholder image 9 for elementary schools
│   ├── placeholder-homeschool-0.png            # Placeholder image 0 for homeschools
│   ├── placeholder-homeschool-1.png            # Placeholder image 1 for homeschools
│   ├── ...
│   ├── placeholder-homeschool-9.png            # Placeholder image 9 for homeschools
│   ├── placeholder-intermediate-0.png          # Placeholder image 0 for intermediate/middle schools
│   ├── placeholder-intermediate-1.png          # Placeholder image 1 for intermediate/middle schools
│   ├── ...
│   ├── placeholder-intermediate-9.png          # Placeholder image 9 for intermediate/middle schools
│   └── placeholder-secondary-0.png             # Placeholder image 0 for secondary/high schools
│   ├── placeholder-secondary-1.png             # Placeholder image 1 for secondary/high schools
│   ├── ...
│   └── placeholder-secondary-9.png             # Placeholder image 9 for secondary/high schools
└── schools/
    └── {school-slug}/                          # Individual school folders
        ├── {slug}-homepage-screenshot.png      # Image of school homepage
        ├── {slug}-classicality-audit.md        # Full Classicality audit report (Markdown)
        ├── {slug}-classicality-audit.pdf       # Full Classicality audit report (PDF)
        ├── {slug}-classicality-abstract.md     # Abstract of Classicality audit (Markdown)
        └── {slug}-og-image.png                 # Open Graph image
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
