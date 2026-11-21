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

- `static/` — CSS, JavaScript, and static assets
- `templates/` — HTML Jinja2 templates
- `app.py` — Main Flask application & routes
- `model.py` — Data processing & analytics logic
- `inventory_history.db` — SQLite database for inventory tracking
- `requirements.txt` — Python dependencies
- `Procfile` — Render/Gunicorn deployment configuration

## ⚙️ Local Installation & Setup

1. **Clone the repository:** `git clone https://github.com/thorf1nx/Food-Rescue-AI.git && cd Food-Rescue-AI`
2. **Create and activate virtual environment:** `python -m venv venv` (Windows: `venv\Scripts\activate` | macOS/Linux: `source venv/bin/activate`)
3. **Install dependencies:** `pip install -r requirements.txt`
4. **Run the application:** `python app.py` and open `http://127.0.0.1:5000`

## 👤 Author

**Ibrahim Balayev** — GitHub: [@thorf1nx](https://github.com/thorf1nx)
