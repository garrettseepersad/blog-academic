---
title: "Relative Positioning Using RTK Measurement Filtering and PPP"
authors:
- admin
- John Aggrey
- Maninder Gill
- Sunil Bisnath
- Don Kim
- H. Tang

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

abstract: "Typical RTK performance is limited to baselines of <10-15 km, as longer distances cause increased measurement errors, which cannot be successfully managed by processing software. The objective of relative positioning is to reduce or eliminate error sources by mathematically differencing simultaneous GNSS measurements from multiple receivers. Accuracy is correlated with baseline length and amounts to approximately 0.1 to 1 ppm for baselines up to some 100 km and then less for longer baselines. The great benefit of PPP is that this technique relies on only single receiver point positioning combined with precise satellite orbit and clock information, code and phase observable filtering, and additional error modelling. PPP is limited by the need for tens of minutes of measurements in order for dm-level positioning, and hours of measurements for cm- and mm-level positioning. Compared to conventional RTK, the RTK measurement filtering approach not only simplifies the implementation of data processing algorithms, but also avoids the risks induced by the commonality assumption. As the measurement filtering approach does not rely on common (correlated) error sources between satellites and receivers, as is the case with conventional RTK, it is immune to long baseline conditions as well as localized anomalous atmospheric conditions. Unlike the PPP approaches, this filtering approach requires neither sophisticated error modelling nor high quality products from international geodetic science organizations (e.g., IGS precise orbit and clock products), as most of the significant error sources can be filtered out using an appropriate signal filter. Although PPP and RTK techniques are now being used as inter-changeable approaches, both have their advantages with regards to long baseline relative positioning. Presented in this paper are novel approaches using RTK with filtered measurements that reduces noise, and inadvertently, eliminates associated errors. The approach saw significant improvement over the traditional RTK technique from the metre level to sub-decimeter level. The PPP approach was used as a comparison tool to ascertain how long a baseline or large a height difference can be processed by the RTK technique, before PPP would become a reliable alternative.
"

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- PPP
- RTK
- Measurement filtering

featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: publications/Seepersad_et_al_2015.pdf
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

