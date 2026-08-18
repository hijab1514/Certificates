# Certifications Master Database

Evidence-based index of verified certifications extracted from files available in this repository/workspace.

## Document Analysis Summary
| Item | Result |
|---|---|
| Evidence files inspected (PDF/images/credential docs) | 0 |
| Unique certifications verified | 0 |
| Duplicate files consolidated | 0 |
| Last audit date | 2026-08-18 |

No certificate evidence files are currently present, so the database below is empty.

## Master Certification Tracker
| Certification | Issuer | Category | Date | Credential ID | Skills | Verification | Evidence |
|---|---|---|---|---|---|---|---|
| _No verified certifications recorded yet_ |  |  |  |  |  |  |  |

## Category Directories
- [AI & Machine Learning](./ai-ml/README.md)
- [Computer Vision](./computer-vision/README.md)
- [Computer Science](./computer-science/README.md)
- [Cloud & DevOps](./cloud/README.md)
- [Data Science](./data-science/README.md)
- [Software Development](./software-development/README.md)
- [Research & Academic](./research/README.md)
- [Other](./other/README.md)

## Certification Entry Template
Use: [CERTIFICATION_TEMPLATE.md](./CERTIFICATION_TEMPLATE.md)

## How to Add a New Certification
1. Add the source evidence file under `/assets` (PDF/image/certificate export).
2. Create one certification markdown file in the correct category folder using this naming format:
   - `YYYY-MM-certification-name.md`
3. Fill the template using only information visible in the evidence file.
4. If present, record credential ID, issue date, expiration date, and official verification URL.
5. Add a single row to the master table in this file.
6. Add a matching row to the selected category README.
7. Link the certification page from the evidence row.
8. If multiple files represent one credential, keep one certification record and list duplicate files as supporting evidence.

## Verification Guidance
Use only official issuer verification pages when available. If missing from certificate evidence, set verification to **Not provided**.
