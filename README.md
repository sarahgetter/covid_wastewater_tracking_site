#COVID-19 Wastewater Tracking Dashboard

This project is an interactive dashboard prototype for monitoring SARS-CoV-2 viral load in wastewater samples across U.S. cities. Wastewater epidemiology provides an early warning of COVID-19 outbreaks before clinical cases are reported.

The dashboard demonstrates how real-time monitoring and visualization tools can support public health decision-making.

Features

Hero Section with Animated Background — powered by Vanta.js
.

Responsive UI — styled with TailwindCSS
.

Smooth animations — via AOS (Animate on Scroll)
.

Feather icons — lightweight, scalable vector icons.

Dynamic charts — built with Chart.js
, including:

Viral Load Trends (line chart)

Variant Distribution (doughnut chart)

Regional Comparison (bar chart)

Stat Cards for samples analyzed, monitoring sites, and early detections.

Placeholder map for future integration of geospatial visualization.

Methodology section explaining wastewater sampling → RNA extraction → RT-qPCR analysis.

Tech Stack

Tailwind CSS
 — utility-first CSS

AOS
 — scroll animations

Feather Icons
 — clean vector icons

Chart.js
 — charting library

Vanta.js
 — animated backgrounds

How to Run

Simply clone the repo and open index.html in your browser:

git clone https://github.com/<your-username>/wastewater-covid-dashboard.git
cd wastewater-covid-dashboard
open index.html   # or double-click in file explorer


No build tools required — everything loads via CDN.

Future Improvements

Integrate real wastewater data sources (e.g. CDC NWSS).

Add interactive map visualization (Leaflet.js / Mapbox).

Expand to track multiple pathogens (flu, RSV, etc.).

Deploy online with GitHub Pages or Vercel.
