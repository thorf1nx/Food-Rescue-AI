# 🥗 Food Rescue AI

**Food Rescue AI** is a web-based inventory management and sustainability analytics platform built to minimize food waste through intelligent tracking, expiry alerts, and interactive trend analysis.

## 🚀 Key Features

- **Multi-User Inventory & Session Isolation:** Secure user-specific inventory management backed by SQLite (`inventory_history.db`).
- **Interactive Analytics Dashboard:** Power BI-style visual insights and dynamic trend tracking powered by Pandas.
- **Excel Data Ingestion:** Seamless multi-user Excel upload and automated data processing pipeline.
- **Smart Waste Prevention:** Real-time monitoring of product expiration timelines and automated inventory snapshots with robust error handling.
- **Cloud-Ready Deployment:** Configured for production deployment on Render with Gunicorn (`Procfile`).

## 🛠️ Tech Stack

- **Backend:** Python, Flask, Gunicorn
- **Data & Analytics:** Pandas, SQLite
- **Frontend:** HTML5, CSS3, JavaScript
- **Deployment:** Render

## 📂 Project Structure

```text
Food-Rescue-AI/
├── static/                 # CSS, JavaScript, and static assets
├── templates/              # HTML Jinja2 templates
├── app.py                  # Main Flask application & routes
├── model.py                # Data processing & analytics logic
├── inventory_history.db    # SQLite database for inventory tracking
├── requirements.txt        # Python dependencies
└── Procfile                # Render/Gunicorn deployment configuration
