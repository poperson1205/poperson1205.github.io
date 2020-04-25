---
title: Render volume data with Python
categories:
 - Memo
tags:
 - volume data
 - volume rendering
 - jupyter notebook
 - plotly
 - python
---

# Motivation

I created a 3d heatmap visualizing distribution of a point cloud.

I used matplotlib for visualizing histograms and 2d heatmaps, but it doesn't have a good feature to visualize my 3d heatmap.

I found a nice tool called plotly, which supports a nice volume rendering.

# Install plotly

Reference: <https://plotly.com/python/getting-started/>

```bash
conda install -c plotly plotly=4.6.0
```