# S3 Directory Repository

This repository contains published school files that are synced to S3 storage.

## Structure

```
s3/
└── directory/
    └── schools/
        └── {school-slug}/
            ├── {slug}-fcapi-classicality-audit.md
            ├── {slug}-fcapi-classicality-abstract.md
            ├── {slug}-v*-fcapi-classicality-audit.pdf
            ├── {slug}-homepage-screenshot.png
            └── {slug}-og-image.png
```

## Purpose

Files in this directory are automatically published from the main THI application when accounts meet all publishing criteria. The `publish` curation rule handles:

- Validation of required address fields
- Geocoding of school locations
- Verification of required files
- Population of grades and school type
- Publishing accounts and copying files to this directory

Files are only copied if they don't exist or if their size or modification time has changed.

## Maintenance

This repository is managed separately from the main THI application repository to allow for independent versioning and deployment of published content.

