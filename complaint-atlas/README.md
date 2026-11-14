# Complaint Atlas

Mortgage complaint patterns and company responses. A public-data business intelligence portfolio project by Mohammad Usman Bashir.

![Complaint Atlas overview](overview.png)

## Business question

Where do reported mortgage problems concentrate, and how does the response mix vary?

## What I built

I built a Power BI report using 21,438 public mortgage complaints received in 2024. I prepared dates and missing categories, checked complaint IDs, and defined response rates using explicit denominators. The report connects issue volumes with monthly patterns and response composition, with comparison and methodology pages.

The report includes an overview, a comparison page, a data-quality and definitions page, and an interactive diagnostic page. The current native report is in [Complaint Atlas.pbix](Complaint%20Atlas.pbix). The [PDF](Complaint%20Atlas.pdf) and PNGs are static previews exported from that saved report on 14 November 2026.

## Download the data and documentation

- [Prepared CSV datasets, methodology, DAX, Power Query, SQL, native report definitions and validation evidence](complaint-atlas-data-and-documentation.zip). Extract the ZIP to retain its documented folder structure.
- [Complete four-report bundle and original public source snapshots](https://github.com/usman5642/powerbi-portfolio/releases/tag/atlas-v1.0.0). This includes the shared Python rebuild and verification scripts.

## Validation and scope

I checked the reported metrics independently using Python and SQL. The four-report release passed 217 metric, data, SQL and native-file integrity checks; rebuilding the prepared Fact tables from the pinned public sources also matched the released data. Interaction checks were performed in Power BI Service. Windows Desktop reopening and refresh remain untested.

This is an independent public-data portfolio project. I do not present descriptive patterns as causal effects or measured business improvements. The PBIX contains imported data; screenshots and the PDF are static previews. Read the bundled methodology for denominators and limitations.

## Sources

Source attribution and licence references are included in the bundle and in the [shared source guide](../ATLAS_SOURCES.md).
