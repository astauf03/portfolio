---
layout: post
title: 'Philadelphia Indego Bike Share Assignment'
thumbnail: /assets/img/projects/proj-5/thumbnail.jpg
---

# Goal: Forecast hourly Indego bike-share demand in Philadelphia
This project builds a space-time predictive model of hourly Indego bike-share demand across Philadelphia.
Using 2024 trip data, weather data, and census characteristics, the analysis forecasts demand across neighborhoods and time periods.

This work demonstrates practical forecasting techniques with an emphasis on interpretability, model comparison, spatial–temporal error patterns, and feature engineering.

[View full report](https://astauf03.github.io/musa5080---lab5/lab5-again.html)

## Key Methods:
- Temporal & spatial feature engineering
- Five baseline predictive models (time-only, weather-only, lags, station FE, demographics)
- Model comparison using MAE
- Spatial error mapping & demographic context

{% include image.html url="http://www.gratisography.com" image="projects/proj-5/gun-pants.jpg" %}

**add image**

## Key Findings: 
- Seasonal differences across Q1–Q4 strongly influence model accuracy.
- Temporal lag features produced the largest improvement (lowest MAE).
- Errors cluster in university areas, tourist-heavy zones, and high-variability stations.
- Engineering new features (rain lag, university distance, station clustering) further improved MAE.
