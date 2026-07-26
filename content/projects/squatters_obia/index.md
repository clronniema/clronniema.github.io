---
title: Object Based Image Analysis
summary: To identify squatters
tags:
- Remote Sensing
- eCognition
- Work
date: "2016-09-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Intermediate results from classification
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

This is a proof of concept work, the aim is to identify squatters (or shacks) that illegally occupy an area. Due to the typical squatters being built using steel covers or wood, it sparked an idea of using remote sensing techniques to identify houses. The squatters are also generally disorganized and individual, which object-based image analysis should be able to delineate each squatter effectively.

{{< figure src="obia_image_seg.png" title="Identifying objects" lightbox="true">}}

Classification is a generally used technique in remote sensing, using imagery to identify target areas based on their spectral response. Object-based Image Analysis includes an extra step, which is to delineate objects of similar spectral response with a defined threshold of shape and size. Small areas of noise can be avoided, while the unlikeliness of perfectly connected squatters allow us to obtain a fairly accurate count of squatters. 

{{< figure src="obia_comparison.png" title="Potentially identified squatters in blue" lightbox="true">}}

The results indicate that there are three potential squatters in the area. As this proof of concept work was conducted using only RGB images, it is obvious that the results are flawed. If spectral data can be obtained to differentiate building materials, the results should drastically be improved. The software used is eCognition developed by Trimble. 


**Further Reading:**
[OBIA in eCognition - Whitepaper](http://www.ecognition.com/category/related-tags/obia)