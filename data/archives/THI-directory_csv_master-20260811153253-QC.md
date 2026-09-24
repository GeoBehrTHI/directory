# storage-curation QC report

- Exit code: 0
- Generated at: 2026-08-11 15:32:54

## Additions and Changes

Compared `s3/data/THI-directory_csv_master.csv` to previous publish `s3/data/archives/THI-directory_csv_master-20260804202042.csv`.

**Summary:** 0 added, 1 changed

### Additions (0)

None.

### Changes (1)

| Slug | Name | Classical Status Origin | Published At | Fields |
| --- | --- | --- | --- | --- |
| capstone-classical-academy-nd-58104 | Capstone Classical Academy | accs-membership | 2026-07-01 | grades, grades_offered, latitude, longitude, school_type, street |

## Command

```
artisan queue:work
```

## Summary

- Command: artisan queue:work
- Rule: publish
- Slug: —
- URL: —
- Dry run: no
- Check folder: no
- Featured placeholders assigned: 0
- Accounts: 5629
- Processed: 0
- Successful: 0
- Failed: 0
- Skipped: 5629
- Files kept: 0
- Files deleted: 0
- Files created: 0
- Assets updated: 0
- Cursor file: s3/data/cursors/_cursor-20260811153253.json
- Exported 3227 published accounts to CSV
- Master CSV path: s3/data/THI-directory_csv_master.csv
- Archive path: s3/data/archives/THI-directory_csv_master-20260811153253.csv
- QC report path: s3/data/archives/THI-directory_csv_master-20260811153253-QC.md
- CSV diff vs previous publish: 0 added, 1 changed

- Schools with validation errors: 86
