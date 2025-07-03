# Emotional Intelligence Tracker

This project hosts a single-page web app for visualizing mood data from CSV files. Open `index.html` in your browser to get started.

## Features

- Detects mood and date columns automatically using heuristics.
- Saves parsed data to your browser's local storage.
- Provides a chart of mood by month.
- Allows exporting saved data to a JSON file and clearing storage.

## Usage

1. Open `index.html` in a modern browser.
2. Click **Choose File** and select a CSV containing mood and date information.
3. Review the generated report and charts.
4. Use the **Export JSON** button to download your data or **Clear Saved Data** to reset.

## CSV Format

The CSV must include columns for mood and date. Common date formats like `YYYY-MM-DD` or `MM/DD/YYYY` are recognized automatically.

