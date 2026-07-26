---
title: 3D Visualization of Buildings
summary: Through conversion from data of various sources
tags:
- ArcGIS Pro
- ArcGIS Online
- 3D
- Work
- Esri
date: "2018-08-01T00:00:00Z"
weight: 80

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: A building extruded from CAD
  focal_point: Smart

links:
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

GIS is a field that often collaborates with the construction industry, often data requires conversion before viewing in GIS applications. The image above is a typical case of data originating from CAD containing textual information on height and material type. Using these attributes available, the buildings can be extruded into 3 dimensional objects with color coded displays to display important information for the audience visualization. The audience could also be given ability to interact the model and examine textual information that is stored within each object.

{{< figure src="hke_3d.png" title="Display of 3D building data from Lands Department of Hong Kong" lightbox="true" >}}

Visualization through GIS is an efficient method in providing spatial context. In a hypothetical scenario of constructing a new building, these visualizations can provide information on how the landscape around is changed. In Hong Kong, one of the sources of 3D ready-made buildings can be obtained through Lands Department 3D-BIT00 series data. Another source would be from the BIM models that are used by the architects and engineers. With Esri's improving software, Revit models can be imported directly with the hassle of conversions. However, it could be computationally costly if the model contains large amount of details.

ArcGIS Pro was used for data import, data processing and then published to ArcGIS Online for viewing on the cloud.

**Further Reading:**

[Importing Revit Data](https://pro.arcgis.com/en/pro-app/help/data/revit/adding-revit-data-to-arcgis-pro.htm)
[Information on 3D-BIT00](https://www.landsd.gov.hk/mapping/en/news/3DSD/news20120718.html)


