---
title: "An assessment of the interoperability of PPP-AR network products"
authors:
- admin
- Sunil Bisnath
date: "2017-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-09-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9=Poster; 10=Web Article
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
#publication: In *Source Themes Conference*
#publication_short: In *STC*

abstract: "Integer ambiguity resolution of carrier-phase measurements from a single receiver can be implemented by applying additional satellite corrections (products) to mitigate unmodelled satellite equipment delays. Interoperability of different PPP-AR products would allow the PPP user to transform independently generated PPP-AR products to obtain multiple fixed solutions of comparable precision and accuracy with limited changes required to user PPP measurement processing software. The ability to provide multiple solutions would increase the reliability of the solution for, e.g., real-time processing; if there were an outage in the generation of one set of PPP-AR products, the user could instantly switch streams to a different provider.

There are currently three main public providers of real-time products that enable PPP-AR. These include School of Geodesy and Geomatics at Wuhan University (SGG-WHU), Natural Resources Canada (NRCan) and Centre National d’Etudes Spatiales (CNES). The presented research examines the PPP-AR products generated from the FCB (Fractional Cycle Bias) model and IRC (Integer Recovery Clock) model that have been transformed into the DC (Decoupled Clock) format and applied within the PPP user solution. Interoperability of the different PPP-AR products is a challenging task due to the public availability of different quality of products, limited literature documenting the conventions adopted within the network solution of the providers and unclear definitions of the corrections. The novelty of the research is in the analysis of using the transformed products. The convergence time (time to first fix and time to a pre-defined performance level), position precision (repeatability), position accuracy and solution outliers are examined. Equivalent performance was noted utilizing the different methods. Of the four solutions, FCB products had the highest accuracy. This is attributed to the products being generated using final IGS orbit and clock products. To confirm this, FCBs generated using GRG orbit and clock products were also examined and comparable performance was observed between the FCBs and IRC (GRG) products. The least accurate solution was obtained using the IRC (CNT) products, which was due to the products being archived real time products."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- PPP-AR
- PPP
- Ambiguity resolution
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://jgps.springeropen.com/track/pdf/10.1186/s41445-017-0009-9
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

