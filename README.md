# Lagos Automotive Importation & Demurrage Logistics Tracker

An interactive spatial and financial risk dashboard analyzing international automotive shipping lanes into *Tin Can Island Port, Lagos, Nigeria*. Built to pinpoint transit bottlenecks, port congestion, and cumulative demurrage penalties across major global export hubs.

🔗 *[View Live Interactive Dashboard on Tableau Public](https://public.tableau.com/app/profile/clinton.ubah4498/viz/LagosAutomotiveImportationDemurrageLogisticsTracker/LagosAutomotiveImportationDemurrageLogisticsTracker)*

![Dashboard Preview](dashboard_preview.png)

---

## Business Problem
In automotive and spare parts importation, port clearance delays and demurrage fees at Tin Can Island Port directly erode profit margins. Without visibility into how specific origin ports correlate with sea transit times and downstream demurrage costs, importers face unpredictable landing expenses. 

This project maps global shipping corridors into Lagos and quantifies financial risk by origin port to support better freight scheduling and customs preparation.

---

## Key Insights
* *Highest Financial Risk Corridor:* Shipments originating from *Port Newark / Elizabeth (USA)* generated the highest cumulative demurrage fees at *$4,140*, signaling a priority lane for pre-arrival customs documentation and clearing optimization[span_0](start_span)[span_0](end_span)[span_1](start_span)[span_1](end_span)[span_2](start_span)[span_2](end_span).
* *European & Asian Lane Exposure:* *Port of Hamburg (Germany)* accounted for *$2,420* in cumulative demurrage, followed by *Port of Yokohama (Japan)* at *$1,900*[span_3](start_span)[span_3](end_span)[span_4](start_span)[span_4](end_span)[span_5](start_span)[span_5](end_span).
* *Lowest Penalty Lane:* *Port of Houston (USA)* recorded the lowest cumulative demurrage exposure at *$420*, serving as a benchmark for smoother clearance turnaround[span_6](start_span)[span_6](end_span)[span_7](start_span)[span_7](end_span)[span_8](start_span)[span_8](end_span).

---

## Tools & Methodology
* *Data Modeling & Preparation:* Structured a multi-attribute shipment dataset containing origin/destination coordinates, Transit Duration Days, and Demurrage Fee Usd.
* *Geospatial Visualization (Tableau):* Engineered custom spatial flight-path arcs using MAKELINE and MAKEPOINT functions to render shipping lanes from North America, Europe, and Asia into Lagos[span_9](start_span)[span_9](end_span).
* *Interactive Cross-Filtering:* Configured dashboard filter actions linking the global route map with a ranked horizontal bar chart and average transit time tooltips, enabling one-click isolation of any trade corridor.

---

## Repository Structure
* global_shipping_routes_lagos.csv — Spatial and logistics dataset covering shipments into Tin Can Island Port, Lagos.
* dashboard_preview.png — High-resolution preview of the published Tableau dashboard.
* README.md — Project documentation and key analytical findings
