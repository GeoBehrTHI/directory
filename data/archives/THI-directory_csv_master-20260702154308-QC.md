# storage-curation QC report

- Exit code: 0
- Generated at: 2026-07-02 15:43:09

## Additions and Changes

Compared `s3/data/THI-directory_csv_master.csv` to previous publish `s3/data/archives/THI-directory_csv_master-20260702153858.csv`.

**Summary:** 1 added, 0 changed

### Additions (1)

| Slug | Name | Classical Status Origin | Published At |
| --- | --- | --- | --- |
| rafiki-classical-academy-fl-32736 | Rafiki Classical Academy | website-submission | 2026-07-02 |

### Changes (0)

None.

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
- Accounts: 5626
- Processed: 0
- Successful: 0
- Failed: 0
- Skipped: 5626
- Files kept: 0
- Files deleted: 0
- Files created: 0
- Assets updated: 0
- Cursor file: s3/data/cursors/_cursor-20260702154308.json
- Exported 3227 published accounts to CSV
- Master CSV path: s3/data/THI-directory_csv_master.csv
- Archive path: s3/data/archives/THI-directory_csv_master-20260702154308.csv
- QC report path: s3/data/archives/THI-directory_csv_master-20260702154308-QC.md
- CSV diff vs previous publish: 1 added, 0 changed

- Schools with validation errors: 86
