# TSBIE QA Project

This repository contains a complete sample QA project for the TSBIE admission journey review.

## Project objective

Validate whether a user can discover the admission flow, download the required form, and complete the process without technical or UX blockers.

## Deliverables

- `TestPlan.docx` and `TestPlan.pdf`: project overview, scope, and strategy
- `TestCases.xlsx`: executed test cases with status tracking
- `BugReport.xlsx`: documented defects with severity, impact, and evidence mapping
- `Screenshots/`: screenshot evidence cards for major findings
- `TestSummaryReport.docx`: final execution summary and recommendations
- `README.md`: repository overview

## Execution summary

- Total test cases: 12
- Passed: 3
- Failed: 7
- Needs Improvement: 2
- Pass percentage: 25.0%

## Main findings

1. Homepage to Admission navigation works.
2. Form download is exposed, but the journey stops there.
3. No upload option or submit button is available.
4. No clear instructions are shown for applicants.
5. The download destination appears untrusted and shows a certificate warning in the supplied evidence.
6. Mobile responsiveness and general UX quality need improvement.

## Suggested GitHub structure

```text
TSBIE_QA_Project/
+-- BugReport.xlsx
+-- README.md
+-- Screenshots/
+-- TestCases.xlsx
+-- TestPlan.docx
+-- TestPlan.pdf
+-- TestSummaryReport.docx
+-- TestSummaryReport.pdf
```

## Note

The evidence set combines the user-provided screenshots with live page-text verification from the public admission page so the final package is consistent and GitHub-ready.
"# TSBIE_QA_Project" 
