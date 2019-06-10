---
title: "Improving Reliability and Assessing Performance of Global Navigation Satellite System Precise Point Positioning Ambiguity Resolution"
authors:
- admin
date: "2018-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9=Poster; 10=Web Article
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
#publication: In *Source Themes Conference*
#publication_short: In *STC*

abstract: "
Conventional Precise Point Positioning (PPP) has always required a relatively long initialization period (few tens of minutes at least) for the carrier-phase ambiguities to converge to constant values and for the solution to reach its optimal precision. The classical PPP convergence period is primarily caused by the estimation of the carrier-phase ambiguity from the relatively noisy pseudoranges and the estimation of atmospheric delay. If the underlying integer nature of the ambiguity is known, it can be resolved, thereby reducing the convergence time of conventional PPP. 

To recover the underlying integer nature of the carrier-phase ambiguities, different strategies for mitigating the satellite and receiver dependent equipment delays have been developed, and products made publicly available to enable ambiguity resolution without any baseline restrictions. There has been limited research within the scope of interoperability of the products, combining the products to improve reliability and assessment of ambiguity resolution within the scope of being an integrity indicator. This study seeks to develop strategies to enable each of these and examine their feasibility.

The advantage of interoperability of the different PPP ambiguity resolution (PPP-AR) products would be to permit the PPP user to transform independently generated PPP-AR products to obtain multiple fixed solutions of comparable precision and accuracy. The ability to provide multiple solutions would increase the reliability of the solution for, e.g., real-time processing: if there were an outage in the generation of the PPP-AR products, the user could instantly switch streams to a different provider. 

The satellite clock combinations routinely produced within the International GNSS Service (IGS) currently disregard that analysis centers (ACs) provide products which enable ambiguity resolution. Users have been expected to choose either an IGS product which is a combined product from multiple ACs or select an individual AC solution which provides products that enable PPP-AR. The goal of the novel research presented was to develop and test a robust satellite clock combination preserving the integer nature of the carrier-phase ambiguities at the user end. mm-level differences were noted, which was expected as the strength lies mainly in its reliability and stable median performance and the combined product is better than or equivalent to any single ACs product in the combination process.

As have been shown in relative positioning and PPP-AR, ambiguity resolution is critical for enabling cm-level positioning. However, what if specifications where at the few dm-level, such as 10 cm and 20 cm horizontal what role does ambiguity resolution play? The role of ambiguity resolution relies primarily on what are the user specifications. If the user specifications are at the few cm-level, ambiguity resolution is an asset as it improves convergence and solution stability. Whereas, if the users specification is at the few dm-level, ambiguity resolution offers limited improvement over the float solution. If the user has the resources to perform ambiguity resolution, even when the specifications are at the few dm-level, it should be utilized.
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
url_pdf: https://yorkspace.library.yorku.ca/xmlui/handle/10315/35570
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

