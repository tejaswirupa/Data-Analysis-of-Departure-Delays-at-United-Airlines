# Analyzing Factors Influencing United Airlines Departure Delays

## Overview
This project investigates the impact of temporal and environmental factors on departure delays for United Airlines (UA) flights using the `nycflights13` dataset. By analyzing trends and conducting permutation tests, we aim to provide actionable insights for operational improvements and enhanced customer satisfaction.

---

## Objectives
- Analyze how **time of day**, **time of year**, and **weather factors** (temperature, wind speed, precipitation, visibility) influence flight delays.
- Apply **permutation testing** to assess statistical significance of observed differences.
- Use **data visualization** to communicate patterns clearly and effectively.

---

## Methodology
- **Data Wrangling**: Joined flight and weather datasets using R (`tidyverse`, `nycflights13`).
- **Feature Engineering**: Created new variables such as `time_of_day`, and categorized weather conditions.
- **Statistical Analysis**: Performed permutation tests to compare delay distributions across multiple factors.
- **Visualization**: Used `ggplot2` for boxplots and point plots to highlight trends and outliers.

---

## Key Insights
- **Night-time flights** exhibit significantly higher delays compared to mornings.
- **Medium-to-high temperatures** and **low visibility** contribute to increased delays.
- **Wind speed** shows inverse behavior: lower wind speeds often correlate with longer delays.
- **Precipitation** may reduce delays due to flight cancellations or rescheduling rather than operating during adverse conditions.
- **Month of the year** has no significant impact on average delays.

---

## Tools & Technologies
- **Programming Language**: R
- **Libraries**: `dplyr`, `ggplot2`, `tidyverse`, `nycflights13`
- **Techniques**: Permutation Testing, Feature Engineering, Data Visualization

---
