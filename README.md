# ABA Behavioral Outcomes Dashboard

An Excel-based data analysis project modeling clinical behavior tracking workflows used in Applied Behavior Analysis (ABA) therapy. Built to demonstrate data pipeline design, formula-driven analysis, and dashboard visualization using real-world clinical data structures.

---

## Project Overview

This workbook simulates a session-level behavioral dataset across multiple clients, skill targets, and treatment phases. The goal was to replicate the kind of data a behavior technician or clinical analyst would work with, and build a clean reporting layer on top of it.

**Dataset:** 300 simulated ABA sessions across 3 clients, 5 behavior targets, and 3 treatment phases (Baseline, Intervention, Maintenance)

---

## Features

- **Structured data layer** — Raw session logs with anonymized client IDs, trial counts, phase labels, and therapist assignments
- **Formula-driven analysis** — AVERAGEIFS-based summary tables calculating mastery rates by behavior target and treatment phase
- **Automated dashboard** — KPI cards and dynamic charts that update when new session data is added
- **Separated data/logic/presentation layers** — Raw Data, Analysis, and Dashboard sheets kept intentionally independent to preserve data integrity

---

## Workbook Structure

| Sheet | Purpose |
|---|---|
| Dashboard | Visual summary — KPI cards, bar chart, phase progression line chart |
| Raw Data | Source data — one row per session, never edited directly |
| Analysis | AVERAGEIFS summary tables feeding the dashboard charts |
| Instructions | Plain-language guide to using and updating the workbook |

---

## Key Skills Demonstrated

- Excel formula logic (AVERAGEIFS, IFERROR, COUNTIF, SUMPRODUCT)
- Data normalization and layer separation
- Dashboard design and chart configuration
- Applied understanding of ABA data structures (trial-based measurement, phase comparisons, mastery criteria)

---

## Clinical Context

In ABA therapy, skill acquisition is measured by tracking the percentage of correct responses across discrete trials. Progress is evaluated by comparing performance across three phases:

- **Baseline** — Pre-intervention measurement of natural behavior
- **Intervention** — Active skill instruction period
- **Maintenance** — Post-instruction follow-up to assess skill retention

This project models that workflow in a format consistent with how behavioral data is tracked and reported in clinical and research settings.

---

## Tools Used

Microsoft Excel — Power Query, AVERAGEIFS, PivotCharts, conditional formatting

---

*Data in this project is entirely simulated. No real client information was used.*
