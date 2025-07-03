# 🅳🆈🅽🅰🅼🅸🅲 🅿🆁🅸🅲🅸🅽🅶 🅵🅾🆁 🆄🆁🅱🅰🅽 🅿🅰🆁🅺🅸🅽🅶 🅻🅾🆃🆂
Summer Analytics 2025 Capstone • Consulting & Analytics Club × Pathway

> **Goal** — Build a real‑time pricing engine that adjusts parking fees on the fly based on demand, traffic conditions, special events and competition, improving utilisation and revenue across 14 urban parking lots.

---

## ✨ Key Features
| Stage | Highlights |
|-------|------------|
| **Data Ingestion** | 73 days of 18×/day records per lot; streamed via Pathway to mimic live feeds |
| **Pre‑processing** | Timestamp fusion, occupancy‑rate calc, categorical encoding for vehicle type & traffic |
| **Models** | <br>1. **Baseline Linear** — price ↗︎ linearly with occupancy<br>2. **Demand‑Based** — multi‑feature demand score (queue, traffic, events, vehicle mix)<br>3. **Competitive (extensible)** — geospatial price adjustment using nearby lots |
| **Real‑Time Engine** | Pathway transforms → pricing logic → live output topic |
| **Visualisation** | Bokeh dashboards (Jupyter/Colab ready) – baseline vs dynamic curves |
| **Extensibility** | Plug‑in rerouting suggestions, advanced ML, REST/WS endpoints |

---

## 🛠 Tech Stack
| Layer | Tools & Libraries |
|-------|-------------------|
| Language | **Python 3.10+** |
| Data Ops | **NumPy, Pandas** |
| Streaming | **Pathway** (🐍 Python API) |
| Visualisation | **Bokeh** (interactive HTML) |
| Notebook | **Jupyter / Google Colab** |
| Optional | GeoPy (distance calc), scikit‑learn (future ML), Docker for deploy |

---
.
├── notebooks/
│   ├── Simple_Dynamic_Pricing_Notebook.ipynb
│   └── Full_Dynamic_Pricing_Notebook.ipynb
├── src/
│   ├── data_prep.py
│   ├── pricing_models.py
│   └── streaming_app.py
├── dataset.csv
├── requirements.txt
└── README.md
