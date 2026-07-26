---
title: Defective Signboards Diagnostics System
summary: Street level signboards detection through photogrammetric principles
tags:
- 3D
- ContextCapture
- Remote Sensing
- Work
date: "2021-10-16T00:00:00Z"
weight: 1

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 3D Model of a Tiled Roof from Drone Imagery
  focal_point: Smart

links:
url_code: ""
url_pdf: ""
url_slides: ""
url_video: "https://www.facebook.com/watch/?v=580099086800731&ref=sharing"

---

Link to video of our client explaining the project, in Cantonese only.

On the other hand, data is collected from a camera rig mounted on top of a vehicle to collect street level images, particularly signboards near ground level. The integration of navigation module, including GPS capturing, image capturing, face blurring and data upload were also part of my duties. Afterwards, data collected are sent through our automated data processing pipelines. In particular, I was heavily involved with automating 3D model reconstructions through ContextCapture SDK. 

{{< figure src="street_img.png" title="Rough Photogrammetry Model from Street Level Data" lightbox="true" >}}

Afterwards, the images and features on them are localised through an internal API. Through such API, users can locate features that they have spotted on images and map to real world location.