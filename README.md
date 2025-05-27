# U.S. Obesity Rate Data Analysis (2016–2023)

This project explores patterns in adult obesity and physical inactivity across the United States using government health data from 2016 to 2023. The analysis focuses on how obesity varies by demographic factors (age, income, education, race/ethnicity, and sex) and behavioral factors (physical inactivity), as well as national and state-level trends over time.

---

## Key Goals

- Clean and transform real-world public health data from [data.gov](https://www.data.gov/)
- Explore obesity rate trends by demographics and geography
- Investigate the relationship between physical inactivity and obesity
- Communicate key findings through meaningful visualizations

---

## Dataset

- **Source:** CDC Behavioral Risk Factor Surveillance System (BRFSS)
- **Years Covered:** 2016–2023
- **Granularity:** Aggregated by state, year, and demographic group

---

## Process Overview

1. **Data Cleaning:**  
   - Dropped redundant columns  
   - Standardized demographic labels  
   - Pivoted question responses into wide format when applicable

2. **Exploratory Data Analysis (EDA):**  
   - Distribution plots by income, education, race, sex, and age  
   - Time trends of national obesity growth  
   - Scatter plots to assess correlation between inactivity and obesity  
   - Violin plots and boxplots for detailed subgroup comparisons

---

## Key Findings

- Obesity rates increased steadily from 2016 to 2022, with a slight drop in 2023.
- Higher education and income levels are associated with lower obesity rates.
- Midlife adults (45–54) show the highest median obesity rates.
- Physical inactivity at the state level is positively associated with obesity rates.

---

## Tools Used

- Python, pandas, seaborn, matplotlib, plotly
- Jupyter Notebook / Google Colab
- Data source: [CDC BRFSS](https://catalog.data.gov/dataset/nutrition-physical-activity-and-obesity-behavioral-risk-factor-surveillance-system)
