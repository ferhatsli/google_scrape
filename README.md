# 📍 Google Maps Scraper

A Python-based scraper using **Playwright** to extract structured restaurant data from Google Maps.

> ⚙️ Originally based on an open-source implementation — now enhanced with better stability, parsing, and output control.

---

## 🎥 Demo Video

[![Watch the demo](https://img.youtube.com/vi/YaqTiqq2Wjg/0.jpg)](https://www.youtube.com/watch?v=YaqTiqq2Wjg)

> Real-time scraping session showing how restaurant data is collected from Google Maps.

---

## ✨ Features

- Extracts detailed restaurant information including:  
  ✅ Name, Address, Website, Phone Number  
  ✅ Reviews count, Average Rating  
  ✅ Location (latitude/longitude)
- Exports results to **Excel** and **CSV** formats  
- Customizable search queries (`-s`) and result limits (`-t`)  
- Forces Google Maps interface to **English** for consistent scraping  
- Stable scraping using **Playwright + Chromium** automation  
- Improvements include: better timeout handling, retry logic, and modular code

---

## 🚀 Installation

```bash
# (Optional) Create and activate a virtual environment
virtualenv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
playwright install chromium
```

⸻

## 🧪 Usage

python3 main.py -s="Dubai restaurants" -t=15

Flag	Description
-s	Search query (e.g. city + category)
-t	Number of results to collect


⸻

## 📁 Output

Results are saved in the output/ folder:
	•	✅ google_maps_data_<search_query>.xlsx
	•	✅ google_maps_data_<search_query>.csv

⸻

## 📚 Notes
	•	This script is for educational and testing purposes only
	•	Please respect Google’s Terms of Service
	•	Add delays or proxies if used at scale to prevent blocking

⸻

## 👨‍💻 Contributions

This repo was originally forked and extended to include:
	•	🛠 Modular function separation
	•	🧠 Parsing logic improvements
	•	🌐 Better search consistency across locales
	•	📦 Output handling and file naming conventions

⸻

## 📧 Contact

ferhatsli63@gmail.com <br>
linkedin.com/in/ferhat-taşlı-674953218

⸻
