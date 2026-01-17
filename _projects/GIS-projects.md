---
layout: post
title: 'GIS Project Showcase'
thumbnail: /assets/img/projects/GIS/gis-work.png
---
# Description of Showcase
This page presents selected GIS analyses completed in ArcGIS Pro, emphasizing raster analysis, spatial pattern recognition, and quantitative spatial reasoning. Projects are summarized below with key methods and outcomes.

---

## Raster Analysis: Painting Sample Classification
- Analyze painting patterns and authors using the following tools: Contour, slope, aspect, hillshade, viewshed, and focal statistics.

**Methods:**
The table below summarizes the raster-based classification workflow used to distinguish texture, brushwork, and directional features across painting samples.

| Classification Attribute | Primary Raster Metric |
|--------------------------|----------------------|
| Brush Direction          | Aspect               |
| Line Thickness           | Slope                |
| Texture Roughness        | Focal Statistics (Mean) |
| Texture Type             | Smoothed Raster (Focal Mean) |


**Visual Evidence:**
![Painting Classification Statistics]({{ "/assets/img/projects/GIS/paintings-summary.png" | relative_url }})
