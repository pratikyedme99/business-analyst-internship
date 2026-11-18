# Week 5 – Deployment and Production

## Project
**Retail Order Delivery Visibility and Customer Communication**

This folder contains Week 5 deployment-readiness documentation for the Business Analyst internship project.

## Files
- `Week5_Deployment_and_Production_Report.docx` – detailed deployment and production report.
- `Week5_Deployment_Readiness_Tracker.xlsx` – environment matrix, release checklist, staging checks, monitoring plan, incident log, rollback plan, and stakeholder communication templates.
- `Week5_Sample_Monitoring_Events.csv` – fictional monitoring events for practice.

## What this phase covers
1. Deployment preparation and release scope.
2. Development, staging/UAT, and production environment planning.
3. Version control and release pipeline controls.
4. Staging validation and go-live acceptance criteria.
5. Production monitoring and support.
6. Incident handling, troubleshooting, and rollback.
7. Stakeholder communication, handover, risks, and readiness decision.

## Important scope and evidence note
This is a **Business Analyst deployment-readiness simulation**. No live application, production server, deployment pipeline, production URL, or real customer system was provided. The project therefore does **not** claim that a real production deployment has taken place. The monitoring CSV contains fictional training events. All staging checks in the workbook begin as `Not Run`; only update them after actual execution and attach evidence.

## How to use the tracker
1. Review the `Start Here` sheet.
2. Complete the `Release Checklist` with actual owners and evidence.
3. Execute `Staging Checks` only in an available test environment.
4. Record actual results, status, tester, date, and defect ID.
5. Review the `Monitoring Plan`, `Incident Log`, and `Rollback Plan`.
6. Do not approve production release until all critical checks pass, critical defects are resolved, backup/rollback are verified, monitoring ownership is assigned, and approvals are recorded.

## Sample baseline carried from Week 3
The prior sample exercise recorded 30 orders, 21 on-time orders, 9 delayed orders, a 30% delay rate, a 3-day average delay among delayed orders, 6 support contacts, and ₹36,750 order value. These are illustrative sample figures, not real company results.

## Suggested GitHub structure
```text
business-analyst-internship/
└── Week 5/
    ├── Week5_Deployment_and_Production_Report.docx
    ├── Week5_Deployment_Readiness_Tracker.xlsx
    ├── Week5_Sample_Monitoring_Events.csv
    └── README.md
```
