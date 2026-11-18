# Business Analyst Internship --- Week 2

## Core Concepts and Skills

This repository contains my Week 2 Business Analyst internship learning
report and a practice case study demonstrating core business analysis
concepts.

> **Note:** The retail order-status scenario is an illustrative learning
> exercise. It does not use real company data or represent work
> performed for an actual client.

## Objectives

-   Understand business problems and business objectives.
-   Identify stakeholders and their possible needs.
-   Draft clear business requirements.
-   Write sample user stories and acceptance criteria.
-   Map a simple business process.
-   Identify possible measures for evaluating business outcomes.
-   Apply clear documentation practices and reflect on areas for further
    learning.

## Practice Case: Retail Order-Status Improvement

### Problem statement

Customers may contact a retailer's support team because they cannot
easily find the latest order status or estimated delivery date. This can
increase support workload and create uncertainty for customers.

### Example requirements

-   Customers should be able to view the latest available status of an
    order.
-   An estimated delivery date should be displayed when available.
-   If the delivery estimate is unavailable, the system should
    communicate that clearly.
-   Authorized support agents should be able to find an order and view
    its status.

### Example process flow

Customer opens order tracking → enters order number → system checks the
order record → latest status and estimated delivery date are displayed
when available → customer contacts support if information is missing or
needs clarification.

### Possible success measures

-   Number of order-status enquiries per week.
-   Average time taken to resolve order-status enquiries.
-   Percentage of orders with up-to-date status information.
-   Customer satisfaction related to delivery communication.

No actual performance data or improvement results are claimed. In a real
project, a baseline would be measured and requirements would be
validated with stakeholders before implementation.

## Files

-   `Week_2_Business_Analyst_Core_Concepts_Report.docx` --- detailed
    Week 2 report.

## Key learning

A Business Analyst should understand and define the business problem
before recommending a solution. Clear stakeholder analysis, testable
requirements, process documentation, and measurable success criteria
help teams align on what a solution needs to achieve.

## Next steps

-   Review the requirements with a mentor or relevant stakeholder where
    possible.
-   Practise creating a process diagram and prioritizing requirements.
-   Add feedback and evidence after completing those activities.


# Business Analyst Internship — Week 3
## Practical Implementation Project

**Project:** Improving Retail Order Delivery Visibility and Customer Communication

### Project purpose
This portfolio project demonstrates a structured Business Analysis approach: problem definition, stakeholder analysis, sample data analysis, requirements, process design, testing, implementation planning, risks, and success measures.

> **Important data note:** The case study and 30 order records are synthetic learning material created for this project. They are not actual company records, stakeholder interviews, production system outputs, or measured business results. The proposed solution has not been implemented or tested in a live environment.

### Repository contents
- `Week3_Practical_Implementation_Project_Report.docx` — detailed project report.
- `Week3_Retail_Delivery_Analysis.xlsx` — synthetic order dataset, KPI summary, and category chart.
- `synthetic_retail_orders.csv` — source dataset used in the workbook.

### Practice dataset snapshot
- Sample orders: 30
- Delayed sample orders: 9 (30.0%)
- On-time sample orders: 21
- Average delay among delayed orders: 3.0 days
- Sample orders marked as having a support contact: 6

These figures describe only the synthetic sample and must not be interpreted as real company performance.

### How to review
1. Read the Word report for the business case, scope, stakeholders, requirements, process, test plan, risks, and KPIs.
2. Open the Excel workbook and review the `Orders`, `KPI Summary`, and `Category Summary` sheets.
3. Review the CSV file as the source data for the analysis.

### Suggested future work
- Validate the problem statement with stakeholders.
- Replace synthetic data with approved, anonymized business data if permitted.
- Confirm baseline KPI definitions and targets.
- Review requirements and process design with business and technical owners.
- Execute test cases in an approved test environment and record evidence.


Week 4 – Testing and Quality Assurance

Business Analyst Internship Project

Project: Retail Order Delivery Visibility and Customer Communication

### Purpose

This folder contains a business-analysis-focused QA plan for the proposed retail order tracking solution. It checks requirement clarity and testability, defines acceptance criteria, and plans functional, integration, end-to-end, UAT, regression, data-quality, access-control and performance checks.

### Files

`Week4_Testing_and_Quality_Assurance_Report.docx` – detailed report and methodology.

`Week4_Test_Cases_and_QA_Tracker.xlsx` – 18 test cases, requirements traceability, defect log, test summary and data dictionary.

`week4_order_tracking_test_data.csv` – fictional sample orders for test practice.

### How to use

Review the requirements and acceptance criteria in the report.

Open the Excel tracker and review the **Test Cases** sheet.

Use the CSV as fictional test data in a test environment or prototype.

Execute each test only when the relevant feature is available.

Record the actual result, status, severity and evidence in the tracker.

Log genuine failures in the Defect Log, fix them with the responsible team, retest and run relevant regression tests.

Update the Test Summary and obtain business/UAT sign-off.

### Important accuracy note

All test cases are initially marked Not Run. No live application or production environment was supplied with this assignment, so this repository does not claim that tests have been executed or passed. The 3-second response-time figure is a proposed target and must be confirmed by the project owner. All sample order/customer IDs and records are fictional.

### Project skills demonstrated

Business requirements review, acceptance criteria, test planning, requirement traceability, test-case design, data-quality validation, UAT planning, defect management, risk analysis and documentation.

Week 5 – Deployment and Production
Project
Retail Order Delivery Visibility and Customer Communication

This folder contains Week 5 deployment-readiness documentation for the Business Analyst internship project.
Files
- Week5_Deployment_and_Production_Report.docx – detailed deployment and production report.
- Week5_Deployment_Readiness_Tracker.xlsx – environment matrix, release checklist, staging checks, monitoring plan, incident log, rollback plan, and stakeholder communication templates.
- Week5_Sample_Monitoring_Events.csv – fictional monitoring events for practice.
What this phase covers
1. Deployment preparation and release scope.
2. Development, staging/UAT, and production environment planning.
3. Version control and release pipeline controls.
4. Staging validation and go-live acceptance criteria.
5. Production monitoring and support.
6. Incident handling, troubleshooting, and rollback.
7. Stakeholder communication, handover, risks, and readiness decision.
Important scope and evidence note
This is a Business Analyst deployment-readiness simulation. No live application, production server, deployment pipeline, production URL, or real customer system was provided. The project therefore does not claim that a real production deployment has taken place. The monitoring CSV contains fictional training events. All staging checks in the workbook begin as Not Run; only update them after actual execution and attach evidence.
How to use the tracker
1. Review the Start Here sheet.
2. Complete the Release Checklist with actual owners and evidence.
3. Execute Staging Checks only in an available test environment.
4. Record actual results, status, tester, date, and defect ID.
5. Review the Monitoring Plan, Incident Log, and Rollback Plan.
6. Do not approve production release until all critical checks pass, critical defects are resolved, backup/rollback are verified, monitoring ownership is assigned, and approvals are recorded.
Sample baseline carried from Week 3
The prior sample exercise recorded 30 orders, 21 on-time orders, 9 delayed orders, a 30% delay rate, a 3-day average delay among delayed orders, 6 support contacts, and ₹36,750 order value. These are illustrative sample figures, not real company results.


Week 6 – Final Capstone Project and Assessment
Project
Retail Order Delivery Visibility and Customer Communication

This is the final Business Analyst internship capstone. It consolidates the earlier project work into a structured end-to-end case: business problem, stakeholders, requirements, process design, sample-data analysis, KPIs, testing/UAT planning, deployment readiness, risks, roadmap and stakeholder presentation.
Repository
https://github.com/pratikyedme99/business-analyst-internship
Files
- Week6_Final_Capstone_Report.docx – main report.
- Week6_Capstone_Workbook.xlsx – source data, KPI dashboard, requirements, process and rules, UAT plan, risk register, roadmap and KPI definitions.
- Week6_Retail_Orders_Dataset.csv – synthetic sample dataset with a calculated delay flag.
- Week6_Stakeholder_Presentation.pptx – summary presentation.
- README.md – project guide.
Sample analysis (synthetic data only)
- Orders: 30
- Sample order value: ₹36,750
- Delayed orders: 9 (30.0%)
- On-time orders: 21
- Average delay among delayed orders: 3.0 days
- Support-contact orders: 6 (20.0%)
These results are calculated from a synthetic practice dataset. They are not actual company performance and should not be presented as such.
How to review
1. Open the Word report for the full business analysis.
2. Open the Excel workbook and review the KPI Dashboard and supporting sheets.
3. Review the UAT Plan. Test cases are marked Not Run because no live application or test environment was supplied.
4. Review the Roadmap and Risk Register for proposed next steps.
5. Use the PowerPoint for a short stakeholder presentation.
Evidence and limitations
- No live application, production environment, real customer records or courier integration was provided.
- No production deployment or executed UAT is claimed.
- Do not mark any test Passed unless you execute it and attach evidence.
- Proposed performance/freshness thresholds and targets require stakeholder approval.
- Do not upload confidential company data, credentials or personal information to a public repository.
