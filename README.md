# Healthcare KPI Reporting Project

Built healthcare KPI reporting project using Databricks SQL, notebook workflows, and Power BI reporting dashboard.

## Project Overview

This project analyzes CMS hospital readmissions data to evaluate national healthcare readmission trends, state-level benchmarking variation, hospital-level KPI performance, and reporting quality across major readmission measures.

The analysis focuses on:

* Excess Readmission Ratio (ERR)
* Predicted vs Expected Readmission Rates
* Reporting suppression and footnote logic
* Facility-level benchmarking variation
* Reporting-ready KPI datasets for downstream Power BI visualization

## Business Objective

Hospital readmissions are a major healthcare quality and cost metric. This project explores how CMS readmission measures can be transformed into reporting-ready KPI datasets for operational analytics and executive dashboard reporting.

The project demonstrates a full analytical workflow including:

* Data exploration
* Data cleaning
* SQL transformation logic
* KPI analysis
* Reporting classification
* Dashboard development

---

# Tools Used

* Databricks SQL
* Databricks Notebooks
* Power BI
* CMS Hospital Readmissions Data

---

# Repository Structure

```text
healthcare-kpi-reporting/
├── notebooks/
├── powerbi/
├── images/
```

### notebooks/

Contains analytical notebooks covering:

* Data exploration
* Data quality review
* KPI transformation logic
* Readmission metric analysis
* Reporting classification workflows

### powerbi/

Contains the Power BI dashboard file used for KPI reporting and visualization.

### images/

Contains dashboard screenshots and project visuals.

---

# Key Analytical Areas

## Excess Readmission Ratio (ERR)

Evaluated hospital-level readmission performance relative to CMS expected benchmarks.

## Predicted vs Expected Readmission Rates

Compared modeled hospital readmission performance against CMS peer expectations.

## Reporting Suppression Logic

Applied CMS footnote classifications to identify unavailable, suppressed, and partial reporting periods.

## Reporting-Ready KPI Development

Prepared structured datasets suitable for dashboard reporting and downstream business intelligence workflows.

---

# Dashboard Preview

Example:

![Dashboard Overview](images/Power BI Screenshot.jpg)


---

# Project Notes

This project was developed using publicly available CMS hospital readmissions data for educational and portfolio purposes.
