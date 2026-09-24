# storage-curation QC report

- Exit code: 0
- Generated at: 2026-07-01 18:36:31

## Additions and Changes

Compared `s3/data/THI-directory_csv_master.csv` to previous publish `s3/data/archives/THI-directory_csv_master-20260701181057.csv`.

**Summary:** 3 added, 1 changed

### Additions (3)

| Slug | Name | Classical Status Origin | Published At |
| --- | --- | --- | --- |
| grace-classical-christian-academy-al-35950 | Grace Classical Christian Academy | scl-membership | 2026-07-01 |
| highlands-latin-school-louisville-ky-40206 | Highlands Latin School - Louisville | scl-membership | 2026-07-01 |
| highlands-latin-school-nashville-tn-37206 | Highlands Latin School - Nashville | clsa-membership | 2026-07-01 |

### Changes (1)

| Slug | Name | Classical Status Origin | Published At | Fields |
| --- | --- | --- | --- | --- |
| grace-classical-christian-academy-tx-76048 | Grace Classical Christian Academy | accs-membership | 2026-07-01 | website |

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
- Cursor file: s3/data/cursors/_cursor-20260701183629.json
- Exported 3227 published accounts to CSV
- Master CSV path: s3/data/THI-directory_csv_master.csv
- Archive path: s3/data/archives/THI-directory_csv_master-20260701183629.csv
- QC report path: s3/data/archives/THI-directory_csv_master-20260701183629-QC.md
- CSV diff vs previous publish: 3 added, 1 changed

- Schools with validation errors: 86
