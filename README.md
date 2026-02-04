# World Energy Consumption Analysis 🌍

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/4hmed-n/World-Energy-Consumption-Analysis/blob/main/World_Energy_Consumption_%28Uncleaned%29.ipynb)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

## 📌 Overview
This project analyzes global energy consumption trends over the past 40+ years to identify patterns in usage and the transition toward sustainability. By comparing fossil fuel dominance against the rise of renewables, this analysis highlights critical trends that inform energy policy and forecasting.

## 📊 Dataset
* **Source:** Kaggle – [World Energy Consumption](https://www.kaggle.com/datasets/pralabhpoudel/world-energy-consumption)
* **Description:** A comprehensive country-level dataset covering multiple energy sources (coal, gas, oil, nuclear, renewable) across decades.
* **Key Columns:** `Country`, `Year`, `Energy Type`, `Consumption (TWh)`, `CO2 Emissions`.

## ⚙️ Technical Approach
The analysis methodology includes:
1.  **Data Preprocessing:** Cleaning missing values and standardizing units across different energy types.
2.  **Exploratory Data Analysis (EDA):** Visualizing temporal trends and regional energy distributions.
3.  **Comparative Analysis:** contrasting the growth rates of renewable energy vs. fossil fuels.
4.  **Forecasting:** Implementing Linear Regression to project future energy demands and shifts in source dependency.

## 📈 Key Insights
* **Global Growth:** Energy consumption has risen consistently since 1980, driven largely by industrializing nations.
* **The Energy Mix:** While fossil fuels (coal, oil) remain the dominant baseline, renewable energy sources have seen exponential growth in the last decade.
* **Regional Shifts:** Several developed nations show a clear decoupling of economic growth from fossil fuel reliance, marking a successful transition phase.
* **Forecasting:** Trends suggest a continued rise in overall demand, necessitating accelerated renewable adoption to meet global climate goals.

## 🚀 Usage (Run in Colab)
You can run the full analysis in your browser without installing anything.

1.  Click the **"Open in Colab"** badge at the top of this README.
2.  **Important:** Since the dataset is hosted in this repository, run the following command in the first cell of the Colab notebook to download the data:

```python
!wget [https://raw.githubusercontent.com/4hmed-n/World-Energy-Consumption-Analysis/main/world_energy_consumption.csv](https://raw.githubusercontent.com/4hmed-n/World-Energy-Consumption-Analysis/main/world_energy_consumption.csv)
