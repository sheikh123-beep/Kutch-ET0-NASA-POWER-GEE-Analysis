# Kutch ET₀ Analysis: NASA POWER vs Google Earth Engine

### Temporal Analysis and Assessment of Reference Evapotranspiration (ET₀) in Kutch, Gujarat

![Research](https://img.shields.io/badge/Research-Environmental%20Data%20Analysis-green)
![Python](https://img.shields.io/badge/Python-Data%20Analysis-blue)
![NASA](https://img.shields.io/badge/Data-NASA%20POWER-orange)
![GEE](https://img.shields.io/badge/Validation-Google%20Earth%20Engine-brightgreen)

## 📌 Project Overview

This research project investigates the temporal variability of Reference Evapotranspiration (ET₀) in Kutch District, Gujarat, India.

The study uses hourly meteorological data obtained from NASA Prediction of Worldwide Energy Resources (NASA POWER) and applies the FAO-56 Penman–Monteith method to estimate reference evapotranspiration.

The resulting ET₀ estimates are analyzed at hourly, daily, monthly, and seasonal scales. Additionally, NASA POWER-based daily ET₀ estimates are compared with an independently derived Google Earth Engine (GEE) dataset for statistical validation.

The research aims to understand atmospheric evaporative demand and its implications for irrigation planning and sustainable water-resource management in arid and semi-arid regions.

## 🎯 Research Objectives

- Estimate reference evapotranspiration using the FAO-56 Penman–Monteith method.
- Analyze hourly and daily ET₀ variations.
- Investigate monthly and seasonal evapotranspiration patterns.
- Compare NASA POWER-based estimates with GEE-derived ET₀ values.
- Evaluate dataset agreement using statistical validation metrics.
- Explore the implications of ET₀ variability for irrigation and water-resource management.

## 📍 Study Area

**Location:** Kutch District, Gujarat, India.

Kutch is an arid to semi-arid region characterized by high temperatures, variable rainfall, and limited water availability.

Understanding atmospheric water demand in this region is important for agricultural planning and efficient irrigation management.

## 📊 Datasets

### 1. NASA POWER Dataset

Source: NASA Prediction of Worldwide Energy Resources.

- Study period: January 2010 – February 2022.
- Temporal resolution: Hourly.
- Total observations: 106,423.
- Main variables: Air temperature, relative humidity, wind speed, and radiation-related parameters.

File: `data/nasa_power_data.csv`

### 2. Google Earth Engine Dataset

An independently derived dataset obtained through Google Earth Engine was used for comparison and validation.

- Available coverage: 2010–2025.
- Total records: 139,513.
- Includes hourly records and corresponding daily ET₀ values.
- Common validation period: 1 January 2010 – 20 February 2022.

File: `data/gee_data.csv`

## ⚙️ Methodology

The research methodology consists of the following stages:

1. Meteorological data acquisition.
2. Data preprocessing and quality checks.
3. Preparation of meteorological variables.
4. Hourly ET₀ estimation.
5. Daily aggregation and temporal analysis.
6. Monthly and seasonal ET₀ assessment.
7. NASA POWER and GEE dataset matching.
8. Statistical validation.
9. Visualization and interpretation.

### FAO-56 Penman–Monteith Method

The study uses the standardized FAO-56 Penman–Monteith approach for reference evapotranspiration estimation.

The method considers meteorological parameters including:

- Air temperature
- Relative humidity
- Wind speed
- Solar radiation
- Net radiation
- Soil heat flux

## 📈 Statistical Validation

NASA POWER-based daily ET₀ estimates were compared against GEE-derived daily estimates.

| Statistical Metric | Result |
|---|---:|
| R² | 0.6312 |
| RMSE | 1.2692 mm/day |
| MAE | 1.0238 mm/day |
| MBE | -0.1607 mm/day |
| Matched observations | 4,434 |

The results indicate a reasonable agreement between the two datasets, with a slight negative bias in NASA POWER-based estimates.

## 🔍 Key Research Findings

- May recorded the highest monthly mean ET₀ at approximately 10.19 mm/day.
- April recorded approximately 9.45 mm/day.
- Summer/pre-monsoon recorded the highest seasonal mean ET₀ at approximately 9.25 mm/day.
- Higher atmospheric evaporative demand was observed during warmer pre-monsoon months.
- The two datasets showed measurable agreement during the common validation period.

These findings demonstrate the importance of temporal ET₀ assessment for understanding atmospheric water demand in water-limited regions.

## 📉 Research Visualizations

The research includes six major visualizations:

1. Study Area Location Map
2. Monthly and Seasonal ET₀ Variation
3. Diurnal ET₀ Variation
4. Daily ET₀ Time-Series Analysis
5. NASA POWER vs Google Earth Engine Comparison
6. Statistical Validation Scatter Plot

Generated visualizations will be organized in the `results/` directory.

## 🛠️ Technologies and Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- NASA POWER
- Google Earth Engine
- FAO-56 Penman–Monteith
- Git and GitHub

## 📁 Repository Structure

```text
Kutch-ET0-NASA-POWER-GEE-Analysis/
│
├── data/
│   ├── nasa_power_data.csv
│   └── gee_data.csv
│
├── research/
│   ├── research_paper.pdf
│   └── presentation_certificate.jpg
│
├── notebooks/
│   └── et0_analysis.ipynb
│
├── results/
│   └── research_visualizations
│
├── README.md
├── requirements.txt
└── .gitignore
```

## 🏆 Research Publication & Presentation

**Conference:** Hinweis Fifth International Conference on Networking, Communication and Computing Technology (NCCT-2026).

**Conference Dates:** October 24–25, 2026.

**Research Title:**

Temporal Analysis and Assessment of Reference Evapotranspiration (ET₀) in Kutch, Gujarat Using NASA POWER Data with Google Earth Engine-Based Validation.

**Researcher:** Sheikh Abubakar

**Institution:** Department of Computer Science and Engineering, Parul Institute of Engineering and Technology, Vadodara, Gujarat, India.

The research paper was approved and presented at NCCT-2026. A Certificate of Presentation & Publication is included in the repository.

Research paper and certificate are available in the `research/` directory.

## 🌍 Research Significance

This project demonstrates the application of meteorological datasets and geospatial technologies in environmental data analysis.

Potential applications include:

- Agricultural Data Analytics
- Irrigation Scheduling
- Climate Data Analysis
- Environmental Monitoring
- Geospatial Data Science
- Water Resource Management
- Remote Sensing and Earth Observation

## 👨‍💻 Author

**Sheikh Abubakar**

Department of Computer Science and Engineering  
Parul Institute of Engineering and Technology  
Vadodara, Gujarat, India.

- GitHub: [Sheikh Abubakar](https://github.com/sheikh123-beep)
- LinkedIn: [Sheikh Abubakar](https://www.linkedin.com/in/sheikh-abubakar-869866420/)

## 📜 License

This repository is intended for academic, educational, and research purposes.

Please refer to the original dataset providers and research publication when reusing the datasets or research findings.