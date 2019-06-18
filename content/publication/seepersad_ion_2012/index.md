---
title: "Reduction of Precise Point Positioning Convergence Period"
authors:
- admin
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

abstract: "Precise Point Positioning (PPP) has become a popular technique to process GNSS receiver data by applying precise satellite orbit and clock information, along with other minor corrections. Although PPP presents definite advantages such as operational flexibility and cost effectiveness for users, it requires tens of minutes for solution initialization, as carrier-phase ambiguities converge to constant values and the solution reaches its optimal precision. Pseudorange multipath and noise are the largest remaining unmanaged error sources in PPP. It is proposed that by reducing the effects of multipath and noise on the pseudorange observable, accurate estimates of carrier-phase float ambiguities will be attained sooner, thus reducing the convergence period of PPP. Given this problem, this study seeks to improve management of the pseudorange errors. The well-known multipath linear combination was used in two distinct ways: 1) to directly correct the raw pseudorange observables, and 2) to stochastically de-weight the pseudorange observables. Corrections to the observables were made in real-time using data from the previous day, and post-processed using data from the same day. The improvements in the solution were calculated with respect to the standard PPP solution, where the raw pseudorange observables were not modified or stochastically de-weighted. Using the post-processed multipath observable has shown improvement in the rate of convergence for 59% of the data, as the pseudorange multipath and noise were effectively mitigated. An improvement in the rate of convergence for 50% of the data was observed when the pseudorange measurements were stochastically de-weighting using the multipath observable. The strength of this model is that it allows for real-time compensation of the effects of the pseudorange multipath and noise in the stochastic model.
"

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- PPP-AR
- PPP
- Multipath
- Measurement noise

featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: publications/Seepersad_et_al_2012.pdf
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

