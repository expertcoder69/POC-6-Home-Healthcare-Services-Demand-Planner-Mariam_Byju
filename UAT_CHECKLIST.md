# UAT Checklist: Home Healthcare Demand Planner (POC-06)

## Phase 1: Visual Inspection
- [x] Dashboard loads with dark theme and cyan accents.
- [x] KPI strip renders 4 distinct metrics.
- [x] Map renders CartoDB dark tiles successfully.
- [x] Visit Volume Area Chart renders with gradient fill.
- [x] Wait Time Bar Chart renders horizontal bars correctly.
- [x] Right sidebar renders "Why This Matters" and "Control Panel".

## Phase 2: Interaction Testing
- [x] Hovering over a map red/amber node (Demand) shows a tooltip with Service, Urgency, and Wait Time.
- [x] Hovering over a map cyan node (Caregiver) shows a tooltip with Status and Specialty.
- [x] Recharts tooltips display correct values on hover.
- [x] Control Panel city dropdown correctly updates map center, KPIs, and charts.
- [x] Control Panel service checkboxes correctly filter map nodes.
- [x] Export Data button successfully downloads a CSV of the active view.

## Phase 3: Performance & Stability
- [x] No runtime crashes on page load.
- [x] Backend responds to fetch requests within acceptable latency.
- [x] Map zoom/pan performs smoothly without tile tearing.
