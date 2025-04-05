# ETL Pipeline Project

## Description
A complete ETL pipeline pulling data from 5 sources:
- CSV File
- JSON File
- Google Sheets API
- MongoDB Atlas
- REST API (OpenWeatherMap)

## Features
- Data cleaning, timestamp formatting, unit conversion
- Daily automation using `schedule`
- CI/CD via GitHub Actions
- Final output stored in MongoDB & CSV

## Setup Instructions
1. Create virtualenv and install requirements
2. Add `config/db_config.json` and `credentials.json`
3. Run `python etl_pipeline.py`
4. Use `scheduler.py` for daily automation
