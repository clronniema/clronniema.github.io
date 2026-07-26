---
title: Chinese White Dolphins Distribution Analysis
summary: Dissertation for MSc in Geomatics
tags:
- Dissertation
- R
- Research
date: "2016-12-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo taken from WWF's website
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

Chinese white dolphin is the official mascot of Hong Kong's handover. However, the dolphins' habitats are constantly under disruptions from several construction projects near the Lantau Island, driving them away. This dissertation quantitatively described how they were driven away from their habitats. For this website, I will only illustrate the metrics that were used to describe these changes in habitat. 

{{< figure src="cwd_encounterrate.png" title="Encounter Rate of the Dolphins by Region" lightbox="true">}}

The distribution of dolphins are surveyed by the Agriculture, Fisheries and Conservation Department of Hong Kong few times a week. They derive the encounter rate as the number of dolphins per 100km travelled. These numbers are analyzed on high level by waters that they belong to. The most active region is the West Lantau area which is least disrupted amongst the six regions.

{{< figure src="cwd_encounterrate_breakdown.png" title="Encounter rate analysis by extracting seasonality and trend component" lightbox="true">}}

A further step has been taken through extracting the trend and seasonality component by each region. In the figure above, the grey bar on the right represents the magnitude of the component. It is seen that the encounter rate is not driven by seasonal fluctuations, but driven by the general trend and the large remainder component shows that most variations are not explained. As a result, it is likely that this region has experienced major and constant disruptions over the years of data collected.

{{< figure src="cwd_udchanges.png" title="Utilization distribution changes of a selected dolphin" lightbox="true">}}

The utilization distribution is a commonly used metric in defining the habitat of animals, or in simple words, the home of the animals. Data points of the same dolphins over different time periods were extracted, utilization distributions are then calculated and then compared. The selected dolphin above is one of the few that still remains in more or less the same area after several years of construction works. The sad truth is this comparison cannot be conducted for many dolphins, as many of them are no longer found in the waters of Hong Kong.

**Further Reading:**

[Chinese White Dolphins](https://www.wwf.org.hk/en/reslib/species/chiwhitedolphin/)

