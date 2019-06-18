---
title: "Examining the interoperability of PPP-AR products"
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

abstract: "Integer ambiguity resolution of carrier-phase measurements from a single receiver can be implemented by applying additional satellite products to mitigate the unmodeled satellite hardware delay. Interoperability of different PPP-AR products would allow the PPP user to transform independently generated PPP-AR products to obtain multiple fixed solutions of comparable precision and accuracy with limited changes required to the core PPP software. The ability to provide multiple solutions would increase the reliability of the solution for, e.g., real-time processing; if there were an outage in the generation of one set of PPP-AR products, the user could instantly switch streams to a different provider. There are currently three main public providers of real-time products that enable PPP-AR. These included Scripps Institution of Oceanography, Natural Resources Canada and Centre national d'études spatiales. The research presented examines the PPP-AR products generated from the FCB (Fractional Cycle Bias) and IRC (Integer Receover Clock) model that have been transformed into the DC (Decoupled Clock) format and applied within the PPP user solution. The novelty of the research is the solution analysis using the transformed product. The convergence time (time to first fix and time to a pre-defined performance level), position precision (repeatability), position accuracy and solution outliers are examined. The temporal and spatial behaviour of these estimated terms are examined for the different products applied to understand the unmodeled effects that introduce incorrect solution fixes. Unlike the fixed solution using the DC products, instantaneous convergence was not attained in the horizontal and vertical component when the transformed IRC and FCB products were utilized. In the horizontal component, the transformed IRC product took 10 minutes to attain the predefined threshold while the FCB product took 31 minutes in the horizontal component. A steady state was never attained, as jumps in the solution occurred at frequent intervals. The transformed IRC product had solution jumps every 15 minutes and the transformed FCB products had jumps in the solution every 30 to 45 minutes. The unstable solution from both transformed products are attributed to the magnitude of transformed products, as they were sub-nanoseconds in magnitude, whereas the DC products were few nanoseconds in magnitude.
"

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- PPP-AR
- PPP
- Ambiguity resolution
- IGS products
- Clock combination

featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: publications/Seepersad_G_and_Bisnath_S_2015.pdf
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

