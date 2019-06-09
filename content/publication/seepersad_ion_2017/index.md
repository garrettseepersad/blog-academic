---
title: "Do we need ambiguity resolution in multi-GNSS PPP for accuracy or integrity?"
authors:
- admin
- John Aggrey
- Sunil Bisnath
date: "2013-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9=Poster; 10=Web Article
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
#publication: In *Source Themes Conference*
#publication_short: In *STC*

abstract: "With the advent of quad-constellation, triple-frequency and external atmospheric constraints being provided to the PPP user, the novelty and focus of this paper is in the quest to answer the question: Do we really need ambiguity resolution in multi-GNSS PPP for accuracy or for integrity? To address the first component of the question, which is also an area of research that has lacked attention, is an examination of the significance between the float and ambiguity resolved PPP user solution. Is the improvement significant enough for applications such as precision agriculture and autonomous vehicles to justify the additional cost and computational complexity of producing a multi-GNSS PPP-AR solution? Results consist of solution analysis of convergence time (time to a pre-defined performance level), position precision (repeatability), position accuracy (solution error with respect to analysis centre’s weekly Site Independent Exchange (SINEX) solution) and residual analysis. Pre-defined user thresholds were selected based on specifications for lane navigation and machine guidance for agriculture. A novel component within the realm of PPP-AR is the analysis of ambiguity resolution as a metric to examine the integrity of the user solution. 
The role of ambiguity resolution relies primarily on what are the user specifications. If the user specifications are at the few cm-level, ambiguity resolution is an asset, as it improves convergence and solution stability. Whereas, if the user’s specification is at the few dm-level, ambiguity resolution offers limited improvement over the float solution. If the user has the resources to perform ambiguity resolution, even when the specifications are at the few dm-level, it should be utilized. To have a high probability of correctly resolving the integer ambiguities, the residual measurement error should be less than a quarter of a wavelength. Having a successfully resolved and validated solution can indicate to user the solution strength and reliability.
"

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- PPP-AR
- PPP
- Ambiguity resolution
- Integrity monitoring
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: publications/Seepersad_G_et_al_2017.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

