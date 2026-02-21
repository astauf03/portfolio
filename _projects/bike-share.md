---
layout: post
title: 'Forecasting Indego Bike Share Demand in Philadelphia (2024)'
thumbnail: assets/img/projects/bike-share/thumbnail-temporal.png
---

**Takeaway:** Temporal lag features drive forecast accuracy, while spatial errors reveal where demand is hardest to predict.

---

**Overview**
This project forecasts hourly Indego bike-share demand across Philadelphia using 2024 trip data, weather, temporal lag features, and neighborhood demographics, with a focus on understanding where and why forecasts fail.

---

**Key Outputs**
- [**Analytical report**](https://astauf03.github.io/musa5080---lab5/lab5-again.html)
- **Code repository:** [GitHub repository](https://github.com/astauf03/musa5080---lab5)

---

**Methods**
- Temporal + spatial feature engineering
- Five baseline predictive models (time-only, weather-only, lags, station FE, demographics)
- Model comparison using MAE
- Spatial error mapping + demographic context

---

**Key Findings**
- Seasonal differences across Q1–Q4 strongly influence model accuracy.
- Temporal lag features produced the largest improvement (lowest MAE).
- Errors cluster in university areas, tourist-heavy zones, and high-variability stations.

---

**Visual Evidence**

![Model performance comparison]({{ "/assets/img/projects/bike-share/best-model.png" | relative_url }})
According to the figure, the model incorporating temporal lag features outperforms others in terms of MAE across all quarters, despite best intentions to enhance the model with fixed effects and rush hour anticipation.




![Spatial error patterns]({{ "/assets/img/projects/bike-share/spatial-error.png" | relative_url }})
Most of the spatial error clusters appear around university campuses (e.g., University of Pennsylvania, Temple University), tourist-heavy areas (e.g., Center City, Old City), and stations with high demand variability.

---

## Tools: R, RMarkdown, ggplot2, sf
