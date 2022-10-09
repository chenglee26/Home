---
title: "Analysis of Reference Error in High-Speed SAR ADCs with Capacitive DAC"
authors:
- admin
- 'Chi-Hang Chan'
- 'Yan Zhu'
- 'Rui P. Martins'
author_notes:
- "First author"
- "Corresponding author"
- "author"
- "author"
date: "2018-07-17T00:00:00Z"
doi: "10.1109/TCSI.2018.2861835"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE TRANSACTIONS ON CIRCUITS AND SYSTEMS–I: REGULAR PAPERS"
publication_short: "IEEE TCAS-1"

abstract: The high-speed successive-approximation-register (SAR) analog-to-digital converters (ADCs) rely on the switched capacitive digital-to-analog converter (CDAC) to perform the fast transition, which causes voltage ripples at the output of the reference circuits. Such ripples lead to the reference error that eventually prolongs the time for DAC settling. To minimize such error with a short available time, it either demands a power-hungry reference buffer or large die area for the decoupling. In this paper, we offer a comprehensive analysis of the reference errors in SAR ADCs with a practical reference network circuit (RNC) in consideration. A circuit model is developed in order to quantify the error amplitude for the critical DAC settling condition. Based on the proposed model, the settling behavior of the DAC with reference buffer can be precisely characterized, leading to a better understanding about the design tradeoff of the RNC. Finally, the developed model is verified by both circuit level simulations and measurement results.

# Summary. An optional shortened abstract.
summary: A comprehensive analysis of the reference errors in SAR ADCs with a practical reference network circuit (RNC) in consideration.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://ieeexplore.ieee.org/abstract/document/8439075'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
