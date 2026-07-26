---
title: CityEngine and GIS
summary: Learning the usage of CityEngine in city planning
tags:
- CityEngine
- 3D
- Esri
- Work
date: "2018-08-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Example of a procedurally generated building
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

CityEngine is an interesting tool by Esri that aims to help generating realistic 3D cities. Buildings can be imported, but also procedurally generated - like building blocks through coding. Each physical parameter of the building can be manipulated through rules. The building above is actually generated through rules that duplicates the windows and the sides of the buildings. When you wish to change the number of floors you can do so by manipulating a simple integer parameter that represents the number of floors.

{{< figure src="cityengine_scenarios.png" title="Comparing view in two scenarios" lightbox="true" >}}

The power of the software is it allows side by side comparison amongst scenes. This is particularly useful in comparing potential developments in the area of interest. 

{{< figure src="cityengine_gfa.png" title="Gross Floor Area calculated through rules" lightbox="true">}}

Urban planners can also make good use of the flexibility of rules, generating desired buildings based on programmed conditions. The right side of the screenshot above contains a list of parameters that are linked to the rules, generating dynamically the desired building accordingly. Moreover, rules allow reporting of attributes such as gross floor area of the generated building. 

{{< figure src="cityengine_viewshed.png" title="Viewshed comparison with breakdown by landuse" lightbox="true">}}

The software is also powerful in providing further analysis to viewshed. This is best illustrated by the figure above, where the composition of land use in view is calculated. This is achieved by dividing the buildings into layers by landuse.

CityEngine is indeed a powerful piece of tool for regional planning. The freedom provided by rules are extremely helpful to simulate, replicate or a mixture of both. However, it is not easy to convert these physical appearances from buildings to code, as each building may vary slightly. It is quite a tedious task and the learning curve of this software is definitely steep. Luckily, Esri has created plenty of tutorials online to help beginners.

**Further Reading:**

[CityEngine Tutorials](https://doc.arcgis.com/en/cityengine/2019.0/tutorials/introduction-to-the-cityengine-tutorials.htm)

[Tutorial 11: Dynamic Building Generation and Reporting of Attribtues](https://doc.arcgis.com/en/cityengine/2019.0/tutorials/tutorial-11-reporting.htm)