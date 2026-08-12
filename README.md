# Home Healthcare Demand Planner (POC-06)

A geospatial intelligence dashboard designed to visualize the supply-demand gap for home healthcare services across Gulf regions. This tool turns abstract wait times and capacity limits into actionable, interactive mapping data for healthcare administrators and planners.

## 🚀 Features

* **Interactive Geospatial Mapping:** Live visualization of patient demand (urgency-weighted) vs. available caregiver supply using Leaflet and CartoDB Dark Matter tiles.
* **Real-Time Analytics:** Dynamic key performance indicators (KPIs) tracking active requests, deployed caregivers, and staffing ratios.
* **Trend & Wait Time Charts:** Visual breakdowns of visit volumes and zonal wait times using Recharts.
* **Dynamic Filtering:** Filter data instantly by City (Abu Dhabi, Dubai, Riyadh, Jeddah) and Service Tiers (Post-Op, Elderly Assistance, etc.).
* **Data Export:** One-click generation and download of CSV reports for offline analysis.

## 🛠️ Tech Stack

**Frontend (Client):**
* Next.js 14 (App Router)
* React 18 / TypeScript
* Tailwind CSS (Real Rails Dark Theme)
* `react-leaflet` (Geospatial Rendering)
* `recharts` (Data Visualization)
* `lucide-react` (Iconography)

**Backend (API):**
* Python 3
* FastAPI
* Uvicorn (ASGI Server)

## 📦 Getting Started

### 1. Start the Backend API
Open a terminal, navigate to your backend directory, activate your virtual environment, and run the FastAPI server:
```bash
# Activate your virtual environment
.\venv\Scripts\activate

# Run the FastAPI server
uvicorn main:app --reload --port 8000
