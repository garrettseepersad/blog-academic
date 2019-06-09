---
title: "Integrity Monitoring for Precise Point Positioning"
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

abstract: "The Precise Point Positioning (PPP) GPS data processing technique has developed over the past 15 years to become a standard method for growing categories of positioning and navigation applications. This includes but is not limited to crustal deformation monitoring, near real-time GPS meteorology, orbit determination of low Earth orbiting satellites and precise positioning of mobile objects. The main commercial applications of PPP are in the agricultural industry for precision farming, marine applications for sensor positioning in support of seafloor mapping and marine construction, and airborne mapping, for photogrammetric sensor positioning. While much research effort has been applied to improving the accuracy of PPP coordinate solutions and the duration of data collection need to achieve such accuracies, very little work has been published on the integrity of PPP solutions. Integrity and monitoring are essential components of any positioning / navigation system. Given that in PPP processing all parameters has to be accounted for, without multiple solutions (as in the case with double-differenced static, multi-baseline networks and network RTK) providing integrity information for PPP single receiver estimates is all that more important. The research presented describes integrity in terms of internally determining realistic measurements of solution accuracy and integrity in terms of internally detecting and removing of outlier measurements. It is important to have integrity monitoring during data processing as this is the only time when all the information used to form the position solution is present for in depth analysis. In the presented work, PPP integrity indicators include post-fit residuals, processing filter convergence, and parameter estimation covariance. Receiver Autonomous Integrity Monitoring (RAIM) is a receiver-internal technique that assesses the integrity of a GNSS signal and removes any outliers. In cases where there are greater than 5 satellites tracked, post-fit residual analysis of the measurements allows for consistency amongst the observations, thus improvement of the overall solution integrity. Through the implementation of one RAIM algorithm variant, a more rigorous PPP residual testing methodology was introduced than the typical use of empirically determined outlier tolerances. The novelty of this development is epoch-by-epoch code-based RAIM algorithm has been expanded to a phase filtered code RAIM algorithm. In testing, the probability of correctly rejecting noisy satellite measurements was improved. Improvements in the initial PPP solution are also seen, which is critical in reduction of filter convergence period. Preliminary results show that by rejecting satellites with above average residuals by using tightened RAIM tolerances improved the initial solution accuracy over the conventional PPP for some sites is observed. This study also proposes a unique technique to indicate in real-time, when sufficient data has been collected to meet the user’s specified accuracy threshold. Aside from measurement outlier detection, the covariance of the estimated position is the main indicator of the solution accuracy in PPP, as a reference solution may not always be available. There have been very few studies that address this integrity monitoring in PPP to answer the questions: How accurate is my epoch PPP position? And, how realistic is the internal PPP uncertainty estimate? To investigate these questions, the PPP processing of a large sample dataset consisting of 300 globally distributed IGS sites, with 7 consecutive days of data at each site was considered. The estimated user position and associated uncertainty from the filter covariance are compared against the IGS weekly SINEX station estimates. The mean horizontal position difference between the two solutions is a few millimeters. Integrity is studied by examining the correlation between the determined PPP position error and the appropriately scaled standard deviation of the estimated user position. Preliminary analysis confirms that estimated covariance parameters are overly optimistic."

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
url_pdf: publications/Seepersad_et_al_2013_Integrity_monitoring_in_PPP.pdf
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

