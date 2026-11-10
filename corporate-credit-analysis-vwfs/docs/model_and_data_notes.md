# Model and Data Notes

## Workbook used

The author supplied an Excel credit model named `VWFS_credit_analysis (2).xlsx`. It contains these sheets:

| Sheet | Purpose |
|---|---|
| Summary | Credit-analysis dashboard and analyst signals |
| Ratios | Financial ratios, growth comparisons and definitions |
| IS | Standardised income statement |
| BS | Standardised balance sheet |
| CF | Cash flow analysis |
| Cap | Capital, liquidity, funding and operating KPIs |
| Credit | Asset quality, residual values and concentration |
| Holdco | Standalone VW FS AG HGB holding-company view |
| Risk | Automotive-industry and credit risk map |
| Pred | Predecessor-group financial information |
| Notes | Sources, definitions, assumptions and perimeter caveats |

## Public exports

The CSV files in `analysis/` are static exports/transcriptions of selected workbook outputs. CSV does not retain Excel formulas, formatting, chart objects, validation rules or interactive stress-test inputs. The original workbook remains the author's calculation file.

## Perimeter and comparability

The current VW FS AG group (European operations plus VW Bank) exists from 1 July 2024. H2 2024 is a six-month comparative period; FY2023 represents the predecessor global group. The workbook presents several growth views and labels annualised H2 2024 comparisons as indicative only.

Do not compare FY2025 with H2 2024 as if both were full financial years. Annualisation ignores seasonality and one-offs. FY2023 predecessor-group figures are contextual and do not describe the current group perimeter.

## Source basis

The credit memo identifies:
- FY2025 IFRS consolidated financial statements and combined management report (published March 2026).
- FY2025 HGB standalone annual financial statements.
- FY2024 IFRS and HGB reports for comparative checks.
- FY2023 IFRS and HGB reports for predecessor-group context.

Detailed page references are recorded in the supplied credit memo and workbook Notes sheet.

## Reproducibility and review

Before reusing the model externally:
1. Reconcile workbook formulas with published annual-report figures.
2. Check cached formula values against recalculated values in Excel or LibreOffice.
3. Reconfirm ratios and definitions, particularly those adapted for a bank/captive-finance business.
4. Check dates, ratings and market-sensitive statements against latest sources.
5. Preserve the distinction between reported data, analyst estimates, stress assumptions and judgement.
6. Do not describe analyst signals as a formal credit rating.

## Data handling

Only include information that is public or authorised for release. Do not upload confidential source material, internal bank data, personal data or restricted third-party documents.
