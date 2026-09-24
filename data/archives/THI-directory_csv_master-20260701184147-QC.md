# storage-curation QC report

- Exit code: 0
- Generated at: 2026-07-01 18:41:48

## Additions and Changes

Compared `s3/data/THI-directory_csv_master.csv` to previous publish `s3/data/archives/THI-directory_csv_master-20260701183629.csv`.

**Summary:** 0 added, 1 changed

### Additions (0)

None.

### Changes (1)

| Slug | Name | Classical Status Origin | Published At | Fields |
| --- | --- | --- | --- | --- |
| highlands-latin-school-owensboro-ky-42301 | Highlands Latin School - Owensboro | clsa-membership | 2026-07-01 | classical_status_origin, latitude, longitude, street |

## Command

```
artisan thi:storage-curation --rule=publish --dry=false
```

## Summary

- Command: artisan thi:storage-curation --rule=publish --dry=false
- Rule: publish
- Slug: —
- URL: —
- Dry run: no
- Check folder: no
- Accounts: 5625
- Processed: 0
- Successful: 0
- Failed: 0
- Skipped: 5625
- Files kept: 0
- Files deleted: 0
- Files created: 0
- Assets updated: 0
- Cursor file: s3/data/cursors/_cursor-20260701184147.json
- Exported 3227 published accounts to CSV
- Master CSV path: s3/data/THI-directory_csv_master.csv
- Archive path: s3/data/archives/THI-directory_csv_master-20260701184147.csv
- QC report path: s3/data/archives/THI-directory_csv_master-20260701184147-QC.md
- CSV diff vs previous publish: 0 added, 1 changed

- Schools with validation errors: 86
