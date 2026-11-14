# Sources and attribution

All four projects use public source data. The pinned source files were downloaded on 9 November 2026; the reports were refined and exported on 14 November 2026. `sources.json` records exact URLs, file sizes and SHA-256 hashes. Historical data should not be presented as a live operational feed.

## Complaint Atlas

[CFPB Consumer Complaint Database](https://www.consumerfinance.gov/data-research/consumer-complaints/). Scope: Mortgage complaints received in calendar 2024. CFPB states that its published complaint data is freely available to use, analyse and build on. This is not a statistical sample of all customers. The source preserves historical issue wording. The derived dataset selects columns, parses dates, retains missing categories, and adds response and forwarding measures. No consumer narrative is included in the report.

## Service Atlas

Amaral, Fantinato and Peres (2018), [Incident Management Process Enriched Event Log](https://doi.org/10.24432/C57S4H), UCI Machine Learning Repository. Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). The source is anonymised. Changes: select the latest event per incident using a stable tie-break, clean missing markers, parse dates and calculate durations and flags. No endorsement by the source authors is implied.

## Workforce Atlas

US Office of Personnel Management, [FedScope employment data](https://www.opm.gov/data/datasets/Index.aspx), September 2024. The exact public archive is recorded in `sources.json`. Official classification dictionaries are preserved in the source archive. Changes: decode classifications, aggregate employment and valid salary/service-length totals, and retain coverage denominators. Source disclosure and suppression conventions still apply; no endorsement by OPM is implied. A separate Creative Commons licence is not asserted for this federal source.

## Learning Atlas

Kuzilek, Hlosta and Zdrahal (2015), [Open University Learning Analytics Dataset](https://doi.org/10.24432/C5KK69), UCI Machine Learning Repository. Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Changes: validate enrolment joins, aggregate days 0–28 VLE clicks, filter eligible assessment records, and derive outcome flags. No endorsement by the source authors is implied.

Source licences and attributions remain separate from the report design and code. This package does not grant additional rights over third-party materials.
