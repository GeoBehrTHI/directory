# storage-curation QC report

- Exit code: 0
- Generated at: 2026-07-01 18:10:58

## Additions and Changes

Compared `s3/data/THI-directory_csv_master.csv` to previous publish `s3/data/archives/THI-directory_csv_master-20260701101839.csv`.

**Summary:** 4 added, 23 changed

### Additions (4)

| Slug | Name | Classical Status Origin | Published At |
| --- | --- | --- | --- |
| headwaters-academy-nc-28652 | Headwaters Academy | audit | 2026-07-01 |
| highlands-latin-school-atlanta-ga | Highlands Latin School - Atlanta | clsa-membership | 2026-07-01 |
| highlands-latin-school-louisville-lower-ky-40243 | Highlands Latin School - Louisville Elementary | scl-membership | 2026-07-01 |
| windsor-christian-academy-pa- | Windsor Christian Academy | hf-membership | 2026-07-01 |

### Changes (23)

| Slug | Name | Classical Status Origin | Published At | Fields |
| --- | --- | --- | --- | --- |
| highlands-latin-cottage-school-anderson-sc-29621 | Highlands Latin Cottage School - Anderson | clsa-membership | 2026-07-01 | email, parent_sf_account_id, phone |
| highlands-latin-cottage-school-beaufort-sc-29906 | Highlands Latin Cottage School - Beaufort | audit | 2026-07-01 | email, latitude, longitude, parent_sf_account_id, street |
| highlands-latin-cottage-school-billings-mt-59108 | Highlands Latin Cottage School - Billings | audit | 2026-07-01 | email, parent_sf_account_id, phone, street |
| highlands-latin-cottage-school-charleston-sc-29407 | Highlands Latin Cottage School - Charleston | audit | 2026-07-01 | email, latitude, longitude, parent_sf_account_id, phone, street |
| highlands-latin-cottage-school-greenville-sc-29681 | Highlands Latin Cottage School - Greenville | manual | 2026-07-01 | parent_sf_account_id |
| highlands-latin-cottage-school-jackson-mi-49203 | Highlands Latin Cottage School - Jackson | audit | 2026-07-01 | email, latitude, longitude, parent_sf_account_id, phone, street |
| highlands-latin-cottage-school-miami-fl-33031 | Highlands Latin Cottage School - Miami | clsa-membership | 2026-07-01 | parent_sf_account_id |
| highlands-latin-cottage-school-naples-fl-34109 | Highlands Latin Cottage School - Naples | clsa-membership | 2026-07-01 | parent_sf_account_id |
| highlands-latin-cottage-school-northeast-wi-54942 | Highlands Latin Cottage School - Northeast Wisconsin | clsa-membership | 2026-07-01 | parent_sf_account_id |
| highlands-latin-cottage-school-pasadena-ca-91042 | Highlands Latin Cottage School - Pasadena | audit | 2026-07-01 | email, parent_sf_account_id, phone, street |
| highlands-latin-cottage-school-phoenix-az-85050 | Highlands Latin Cottage School - Phoenix | clsa-membership | 2026-07-01 | email, latitude, longitude, parent_sf_account_id, phone, street |
| highlands-latin-cottage-school-richmond-va-23221 | Highlands Latin Cottage School - Richmond | clsa-membership | 2026-07-01 | parent_sf_account_id, phone |
| highlands-latin-cottage-school-santa-clarita-ca-91355 | Highlands Latin Cottage School - Santa Clarita | audit | 2026-07-01 | email, latitude, longitude, parent_sf_account_id, phone, street |
| highlands-latin-cottage-school-south-bay-ca-90501 | Highlands Latin Cottage School - South Bay | audit | 2026-07-01 | email, latitude, longitude, parent_sf_account_id, phone, street |
| highlands-latin-cottage-school-stillwater-ok-40243 | Highlands Latin Cottage School - Stillwater | audit | 2026-07-01 | email, latitude, longitude, parent_sf_account_id, phone, street |
| highlands-latin-cottage-school-summerville-sc-29485 | Highlands Latin Cottage School - Summerville | clsa-membership | 2026-07-01 | latitude, longitude, parent_id, parent_name, parent_sf_account_id, phone, street, website |
| highlands-latin-cottage-school-sunland-ca-91040 | Highlands Latin Cottage School - Sunland | clsa-membership | 2026-07-01 | parent_sf_account_id |
| highlands-latin-cottage-school-wichita-ks-67230 | Highlands Latin Cottage School - Wichita | clsa-membership | 2026-07-01 | parent_sf_account_id |
| highlands-latin-cottage-school-williamsburg-va-23188 | Highlands Latin Cottage School - Williamsburg | clsa-membership | 2026-07-01 | latitude, longitude, parent_sf_account_id |
| highlands-latin-school-houston-tx-77058 | Highlands Latin Cottage School - Houston | clsa-membership | 2026-07-01 | email, parent_sf_account_id, salesforce_account_id |
| highlands-latin-school-indianapolis-in-46032 | Highlands Latin School - Indianapolis | audit | 2026-07-01 | email, latitude, longitude, name, phone, street |
| highlands-latin-school-orlando-fl-32792 | Highlands Latin School - Orlando | audit | 2026-07-01 | parent_sf_account_id |
| highlands-latin-school-owensboro-ky-42301 | Highlands Latin School - Owensboro | audit | 2026-07-01 | email, parent_sf_account_id, phone, street |

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
- Accounts: 5621
- Processed: 0
- Successful: 0
- Failed: 0
- Skipped: 5621
- Files kept: 0
- Files deleted: 0
- Files created: 0
- Assets updated: 0
- Cursor file: s3/data/cursors/_cursor-20260701181057.json
- Exported 3224 published accounts to CSV
- Master CSV path: s3/data/THI-directory_csv_master.csv
- Archive path: s3/data/archives/THI-directory_csv_master-20260701181057.csv
- QC report path: s3/data/archives/THI-directory_csv_master-20260701181057-QC.md
- CSV diff vs previous publish: 4 added, 23 changed

- Schools with validation errors: 83
