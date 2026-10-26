# storage-curation QC report

- Exit code: 0
- Generated at: 2026-10-25 21:10:50

## Additions and Changes

Compared `s3/data/THI-directory_csv_master.csv` to previous publish `s3/data/archives/THI-directory_csv_master-20261025210632.csv`.

No additions or changes since the last published CSV.

## Command

```
artisan queue:work --once --name=default --queue=default --backoff=0 --memory=448 --sleep=3 --tries=1
```

## Summary

- Command: artisan queue:work --once --name=default --queue=default --backoff=0 --memory=448 --sleep=3 --tries=1
- Rule: publish
- Slug: —
- URL: —
- Dry run: no
- Check folder: no
- Featured placeholders assigned: 0
- Accounts: 6038
- Processed: 0
- Successful: 0
- Failed: 0
- Skipped: 6038
- Files kept: 0
- Files deleted: 0
- Files created: 0
- Assets updated: 0
- Cursor file: s3/data/cursors/_cursor-20261025211049.json
- Exported 3650 published accounts to CSV
- Master CSV path: s3/data/THI-directory_csv_master.csv
- Archive path: s3/data/archives/THI-directory_csv_master-20261025211049.csv
- QC report path: s3/data/archives/THI-directory_csv_master-20261025211049-QC.md
- CSV diff vs previous publish: 0 added, 0 changed

- Schools with validation errors: 231
