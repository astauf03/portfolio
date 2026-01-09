---
layout: post
title: 'Chicago Burglary & Pothole Analysis (2017–2018)'
thumbnail: assets/img/projects/chicago-ppa/thumbnail_chicago.png
---

This project evaluates whether 311 alley pothole complaints are predictive of burglary patterns in Chicago using spatial statistics and predictive modeling. The goal is to assess whether non-crime civic signals can meaningfully improve burglary risk prediction beyond baseline spatial methods.

---

### Methods

- 500m × 500m fishnet grid
- Spatial joins and nearest-neighbor feature engineering
- Local Moran’s I and LISA cluster analysis
- Poisson and Negative Binomial regression
- KDE baseline comparison
- Leave-One-Grid-Out spatial cross-validation
- Temporal validation using 2018 burglary outcomes

### Key Findings

- Pothole complaints showed weak independent predictive power after controlling for socioeconomic variables (very expected)
- KDE baselines slightly outperformed regression models in raw predictive accuracy.
- Spatial generalization was moderate, while temporal generalization was weaker.


## Full Report

[View Full HTML Report](https://astauf03.github.io/spatial-analysis-portfolio/chicago_burglary_potholes/)


## Source Code

- RMarkdown analysis file (`stauffer_alex.Rmd`)
- Reproducible spatial modeling workflow

[View source repository](https://github.com/astauf03/spatial-analysis-portfolio)



{% include image.html url="http://www.gratisography.com" image="projects/proj-3/clothes.jpg" %}
