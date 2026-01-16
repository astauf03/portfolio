---
layout: post
title: 'Forecasting Indego Bike Share Demand in Philadelphia (2024)'
thumbnail: /assets/img/projects/bike-share/temporal.png
---

# Goal: Forecast hourly Indego bike-share demand in Philadelphia
This project forecasts hourly Indego bike-share demand across Philadelphia using 2024 trip data, weather, and neighborhood demographics. I compare baseline models using MAE and map spatial error patterns to understand where and why forecasts break down.

Understanding where forecasts fail helps planners/operators prioritize rebalancing and station capacity.

[**Full report:**](https://astauf03.github.io/musa5080---lab5/lab5-again.html)

---

**Key Methods**:
- Temporal + spatial feature engineering
- Five baseline predictive models (time-only, weather-only, lags, station FE, demographics)
- Model comparison using MAE
- Spatial error mapping + demographic context

![Model performance comparison]({{ "/assets/img/projects/bike-share/best-model.png" | relative_url }})

---

**Key Findings**:
- Seasonal differences across Q1–Q4 strongly influence model accuracy.
- Temporal lag features produced the largest improvement (lowest MAE).
- Errors cluster in university areas, tourist-heavy zones, and high-variability stations.

![Spatial error patterns]({{ "/assets/img/projects/bike-share/spatial-error.png" | relative_url }})

**Tools**: R, RMarkdown, ggplot2, sf, tidymodels
