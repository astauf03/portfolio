---
layout: post
title: 'Chicago Burglary & Pothole Analysis (2017–2018)'
thumbnail: /assets/img/projects/chicago-ppa/temporal-error.png
---

**Takeaway:** Non-crime civic signals (311 pothole complaints) add little predictive power to burglary risk once neighborhood context is considered.

---

**Overview**
This project evaluates whether 311 alley pothole complaints can improve burglary prediction in Chicago beyond baseline spatial models, testing the usefulness of non-crime civic data in predictive policing contexts.

---

**Key Outputs**
- **Full analytical report:** [Chicago Burglary & Pothole Analysis](https://astauf03.github.io/spatial-analysis-portfolio/chicago_burglary_potholes/stauffer_alex.html)
- **Code repository:** [GitHub repository](https://github.com/astauf03/spatial-analysis-portfolio)

---

**Methods**

- 500m × 500m fishnet grid
- Spatial joins and nearest-neighbor feature engineering
- Local Moran’s I and LISA cluster analysis
- Poisson and Negative Binomial regression
- KDE baseline comparison
- Leave-One-Grid-Out spatial cross-validation
- Temporal validation using 2018 burglary outcomes

---

**Key Findings:**
- Pothole complaints showed weak independent predictive power after controlling for socioeconomic variables (very expected)
- KDE baselines slightly outperformed regression models in raw predictive accuracy.
- Spatial generalization was moderate, while temporal generalization was weaker.

---

**Visual Evidence**
![Burglary and pothole density comparison](link)

---

## Limitations: Pothole complaints may not capture all relevant civic signals.


