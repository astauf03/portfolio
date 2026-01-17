---
layout: post
title: 'GIS Project Showcase'
---
# Description of Showcase
This page presents selected GIS analyses completed in ArcGIS Pro, emphasizing raster analysis, spatial pattern recognition, and quantitative spatial reasoning. Projects are summarized below with key methods and outcomes.

---

## Raster Analysis: Painting Sample Classification
- Analyze painting patterns and authors using the following tools: Contour, slope, aspect, hillshade, viewshed, and focal statistics.

**Methods:**
| Classification Attribute | Step 1 / Metric                | Step 2 / Metric                          | Step 3 / Operation | Step 4 / Operation                          | Final Action |
|--------------------------|--------------------------------|------------------------------------------|--------------------|----------------------------------------------|--------------|
| Brush Direction          | Aspect                         | Focal Statistics (SD)                    | —                  | —                                            | —            |
| Line Thickness           | Slope                          | Reclass via global slope mean            | Regroup            | —                                            | —            |
| Texture Roughness        | Focal Statistics (Mean)        | —                                        | —                  | —                                            | —            |
| Texture Type             | Smoothed raster (Focal Mean)   | Raster Calculator: (smooth − original)  | Focal Stats (SD)   | Raster Calc: (diff + focal SD) / 2           | Reclassify   |


**Visual Evidence:**
![Painting Classification Statistics]({{ "/assets/img/projects/gis-projects/paintings-summary.png" | relative_url }})
