# Metrics dashboard mock

- Job ID: ADV-MORNING-001
- Status: shareable teaching mock
- Updated: 2026-07-21
- Source contract: [metrics learning](metrics_learning.md)
- Dashboard workbook: [wow_metrics_cockpit_mock.xlsx](../../../../outputs/metrics_dashboard_mock/wow_metrics_cockpit_mock.xlsx)
- Plain data export: [wow_metrics_cockpit_mock.csv](../../../../outputs/metrics_dashboard_mock/wow_metrics_cockpit_mock.csv)

## Purpose

This workbook makes the metrics contract easy to explain and share. It shows what a healthy
synthetic replay could look like and why a good-looking number is not enough on its own.

It is not connected to the product. All values and goals in the workbook are invented examples.
They must not be treated as measured results, approved thresholds, tax correctness, or permission
to run live work.

## What is inside

| Tab | What it explains |
| --- | --- |
| Dashboard | The four early product KPIs and the hard safety checks for one healthy example. |
| Scenario library | Five mock outcomes that show why the product gate can become `hold`. |
| Read me | A plain-language explanation of what success means, what still needs to happen, and what the mock cannot prove. |

The dashboard uses the confirmed early KPIs from the metrics contract:

1. Trusted bookkeeping completion (`M001`).
2. Advisor effort per accepted period (`M008`).
3. Time to the correct next Advisor action (`M015`).
4. Material-work coverage (`M016`).

One false-ready case, missing material evidence link, unsafe action, or duplicate retry action is
enough to stop the affected path. The PDF reader stays a separate capability proof. It remains
inactive in the core structured-data workflow until its own safety and quality checks pass.

## How to share it

Upload the `.xlsx` file to Google Drive and open it with Google Sheets. Use the `.csv` only when
someone needs the scenario data without the visual dashboard.

## What must happen before the real dashboard

- Collect the five-day Advisor baseline.
- Agree the exact gold-case rubric.
- Name the responsible owners.
- Add the required runtime measurement events.
- Set numeric thresholds before replay results are viewed.

Until then, the correct gate remains `hold → narrow`.
