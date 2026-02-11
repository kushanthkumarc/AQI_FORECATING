# AQI Forecasting Project

This project predicts Air Quality Index (AQI) using machine learning models and provides a dashboard for visualization.

## Features
- AQI prediction using trained ML models
- Interactive dashboard (Flask app)
- Data visualization

## Datasets
- `station_day.csv` and `stations.csv` contain air quality data from 2015 to 2020.

## Files
- `app.py`: Flask web application for AQI prediction and dashboard
- `Final_AQI_ML.ipynb`: Jupyter notebook for model training and analysis
- `AQI_Forecasting.pkl`: Trained ML model
- `model_columns.pkl`: Model feature columns
- `background.jpg`: Dashboard background image
- `index.html`: Web interface
- `requirements.txt`: Python dependencies

## Live Demo

The app is live at: [https://cozy-speculoos-b7a94c.netlify.app/]
## Usage
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the web app:
   ```bash
   python app.py
   ```
3. Access the dashboard at `http://localhost:5000`



