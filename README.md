# International-Aid-Dashboard
Interactive Excel dashboard analysing $13.2B in Chinese development aid to Africa (2000–2021) — 9,300+ AidData records cleaned, modelled, and visualised.
# 🌍 China in Africa: Financial Aid Flows — Excel Dashboard

**An end-to-end data analysis project**: 9,300+ raw records from AidData's
Global Chinese Development Finance Dataset, cleaned, modelled, and distilled
into two interactive Excel dashboards analysing $13.2B in Chinese development
finance across 53 African nations (2000–2021).

![Main Dashboard](screenshots/dashboard-insight.png)

---

## 🎯 The Question

Where does Chinese development finance in Africa actually go — which
countries, which sectors, on what terms, and how has it changed over
two decades?

## 📊 Headline Findings

- **$13.2B** in tracked aid across **159 projects** in **53 nations**
- **Egypt** is the single largest recipient; the top 5 recipients account
  for the majority of all flows
- **Industry, Mining & Construction** leads sector allocation, ahead of
  Health and Transport
- **Grants (62%)** outnumber **loans (33%)** — the remaining flows are
  scholarships, technical assistance, and debt forgiveness
- Funding is strongly targeted: **~95% flows to low and lower-middle
  income countries** (OECD classification)
- Annual commitments peaked at **$3.5B in 2019**, with an earlier
  wave in 2008–09

![Trend Dashboard](screenshots/trend-dashboard.png)

---

## 🛠️ How I Built It

**1. Data Cleaning** — Filtered a 9,345-record global extract down to a
validated African project set: standardised statuses and dates, resolved
missing implementation/completion years, and converted original-currency
amounts to USD with a dedicated exchange-rate lookup table.

**2. Data Modelling** — Structured the cleaned data as Excel tables and
built a pivot-table layer to power every visual, so all charts respond
to slicer filters and refresh with new data.

**3. KPI Design** — Six headline metrics computed on a dedicated sheet
and surfaced as icon-tagged KPI cards.

**4. Dashboard Design** — A deliberate design system applied across both
dashboards: a green / orange / brownish-gold palette, Gill Sans
typography, uniform KPI cards, palette-coded slicers, and charts that
label only what matters (peak years, leading categories) instead of
every data point.

![KPI Cards](screenshots/kpi-cards.png)

---

## 🎛️ Interactivity

Five slicers — **Region, Commitment Year, Status, OECD Income Group,
Recipient** — let a reader isolate any country, era, or income tier and
watch every KPI and chart update.

![Slicers](screenshots/slicers.png)

---

## 💡 Skills Demonstrated

`Data Cleaning` · `Data Modelling` · `Pivot Tables` · `Interactive
Dashboards` · `Data Visualisation` · `KPI Design` · `Excel`

## 📦 Data Source

> AidData. *Global Chinese Development Finance Dataset.*
> William & Mary — https://www.aiddata.org
> Amounts in constant 2021 USD.

## 📂 Repository Contents

| File | Description |
|---|---|
| `International Aid_China Dashboard.xlsx` | Full workbook — raw data, cleaning layer, pivots, KPIs, dashboards |
| `screenshots/` | Dashboard previews used in this README |
