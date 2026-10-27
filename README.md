# Saúde+ | Healthcare Process Mining and Analytics

**NOVA IMS | Business Process Management | June 2025**

## Overview

This academic project used **Celonis** to analyze appointment workflows at Saúde+ Health Center, a Portugal-based clinical appointment process case study. The analysis explored patient journeys, process variants, throughput times, cancellations, service performance, and patient/customer segmentation to identify potential improvement opportunities.

## Data and ETL

The assignment provided:
- A **case table** with appointment attributes, such as patient demographics, insurance status, satisfaction, and costs.
- An **event log** with timestamped process activities linked to each case.

The project imported both tables into Celonis, checked their schemas, performed SQL-based preprocessing, linked them by `case_id`, and defined the event log as the process activity table. The reported load contained **6,245 combined rows**.

## Analysis and dashboards

The Celonis work included:
- **Variant Explorer:** Compared frequent patient journey sequences and variants.
- **Process Explorer:** Mapped process activities and transitions, including consultation, payment, cancellations, and exits.
- **Case Explorer:** Examined case-level throughput times and exceptional journeys.
- **Activity Explorer:** Explored activity frequencies and durations.
- **Overview and segmentation dashboards:** Analyzed appointment volumes, cancellations, satisfaction, demographics, and costs.

## Selected findings

The academic report documented:
- **148** distinct patient-journey variants.
- **611** cancelled appointments, reported as approximately **32%** of appointments.
- Differences in appointment experiences across patient groups and journey types.

These are descriptive findings from the case study; proposed improvements were not experimentally validated.

## Technology and methods

Celonis EMS, SQL-based ETL, Process Query Language (PQL) for process analytics, event-log modeling, process discovery and variant exploration, throughput-time analysis, KPI dashboards, and patient segmentation.

**Methodological note:** The project report documents process and variant exploration. It does not provide a formal conformance-checking fitness or alignment score.

## Repository contents

- [Celonis Visuals.pdf](Celonis%20Visuals.pdf) — PDF showcase of the project's dashboard screenshots and analysis.
- `README.md` — Project documentation.

The original case/event datasets, live Celonis workspace, and complete academic report are **not included** in this repository. The PDF is a static portfolio showcase.

## Team

Group T: **Inês Araújo, Jude Gbenimako, Tomás Ribeiro, Afonso Gião, and Solveig Notø**, as listed in the submitted project report.

## Academic context

NOVA Information Management School (NOVA IMS), MSc in Data Science and Advanced Analytics, Business Process Management (2024/2025).
