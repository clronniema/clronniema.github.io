---
title: Hong Kong Height Correction from Ellipsoidal Height to Orthometric Height
summary: A Jupyter Notebook that demonstrates how this could be done in a few easy steps
date: 2022-01-01
authors:
  - me
tags:
  - Jupyter
  - Tutorials
cover:
  # image: cover.jpg  # Auto-detected from cover image in this folder
  icon:
    name: "📔"
image:
  caption: ""
  focal_point: Center
  placement: 1
content_meta:
  trending: false
---

This notebook converts a **WGS84 latitude / longitude / ellipsoidal height** into
**HK80 Grid coordinates (Northing / Easting) with an orthometric height above Hong Kong Principal Datum**.

Please also download the necessary file below:
[Control Points CSV](./data/control_pts_heights.csv)

{{< notebook
    src="hk_height_transformation.ipynb"
    title="Hong Kong Height Transformation"
    show_metadata=false
    line_numbers=false
    dense=false
    download_label="Download notebook"
    show_outputs=true
>}}

