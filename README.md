# Portable Solar Radio Telescope Dashboard

A Streamlit-based dashboard to visualize and analyze solar activity data.

## Features
- Upload and manage multiple CSV files
- Visualize sensor output with labeled solar activity events
- Detect sun entry/exit, gain saturation, and solar flares

## File Format
- CSV with no headers
- Two columns: `Time (s)`, `Sensor Output`

## Run Instructions
```bash
pip install -r requirements.txt
streamlit run dashboard.py
```
