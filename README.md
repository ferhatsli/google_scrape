# Google Maps Scraper

A Python-based scraper that uses Playwright to extract restaurant data from Google Maps.

## Features
- Extracts restaurant information including:
  - Name
  - Address
  - Website
  - Phone number
  - Reviews count
  - Average rating
  - Location coordinates (latitude/longitude)
- Saves data in both Excel and CSV formats
- Customizable search parameters
- Language control (forced to English)

## Installation
1. (Optional) Create & activate a virtual environment:
   ```bash
   virtualenv venv
   source venv/bin/activate
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   playwright install chromium
   ```

## Usage
Run the script with the following command:
```bash
python3 main.py -s="<search query>" -t=<number of results>
```

Example:
```bash
python3 main.py -s="Dubai restaurants" -t=15
```

## Output
The script generates two output files in the `output` directory:
- Excel file: `google_maps_data_<search_query>.xlsx`
- CSV file: `google_maps_data_<search_query>.csv`

## Note
This script is for educational purposes only. Please respect Google's terms of service and rate limits when using this tool.
