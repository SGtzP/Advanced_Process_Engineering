# Advanced_Process_Engineering
Scripts and tools for Statistical Process Control (SPC), process development, and data analysis to support engineering in high-tech manufacturing. Designed to monitor processes, visualize data, and help identify root causes for improved quality and efficiency.


# Correlative Advance SPC
# Levey-Jennings Control Chart with Regression Analysis

This Python script generates Levey-Jennings control charts and performs linear regression on process control data from multiple reactors. It highlights anomalies using statistical control limits and category-specific regression deltas.

## Features

- Plots Levey-Jennings charts with ±1σ, ±2σ, and ±3σ lines
- Performs full regression and last-N-point regression per reactor
- Computes delta between regression slope and process mean
- Visualizes anomalies with bar plots, heatmaps, and scatter plots

## Requirements

- Python 3.8+
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn

Install requirements with:

```bash
pip install pandas numpy matplotlib seaborn
