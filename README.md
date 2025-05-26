# YouTube Channel Metadata Analysis

## Overview
This project uses the YouTube Data API v3 and Python to extract metadata for three popular tech/data YouTube channels:
- Alex The Analyst
- CodeBasics
- Chandoo

It fetches channel-level data such as subscriber counts, total views, publishing dates, country, total videos, and playlist IDs.

## Features
- Connects to the YouTube Data API using `googleapiclient`
- Extracts key channel statistics and metadata
- Converts data types and parses dates for analysis
- Calculates channel age (in years)
- Visualizes subscriber counts and channel age with bar charts

## How to Run
1. Clone the repo.
2. Install dependencies:
pip install google-api-python-client pandas python-dateutil matplotlib

3. Replace the `api_key` variable in the script with your own API key.
4. Run the Python script or Jupyter notebook.

## Visualizations
- **Subscribers by Channel:** Bar chart showing subscriber counts (in millions).
- **Channel Age:** Horizontal bar chart showing the age of each channel in years.

## Author
Dhanya K.R
