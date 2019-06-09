---
title: "Examining precise point positioning now and in the future"
authors:
- Sunil Bisnath
- John Aggrey
- admin
- Maninder Gill

date: "2013-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9=Poster; 10=Web Article
publication_types: ["10"]

# Publication name and optional abbreviated publication name.
#publication: In *Source Themes Conference*
#publication_short: In *STC*

abstract: "PPP. It’s one of the many acronyms (or initialisms, if you prefer) associated with the uses of global navigation satellite systems. It stands for precise point positioning. But what is that? Isn’t all GNSS positioning precise? Well, it’s a matter of degree.

Take GPS, for example. The most common kind of GPS signal use, that implemented in vehicle “satnav” units; mobile phones; and hiking, golfing and fitness receivers, is to employ the L1 C/A-code pseudorange (code) measurements along with the broadcast satellite orbit and clock information to produce a point position.

Officially, this is termed use of the GPS Standard Positioning Service (SPS). It is capable of meter-level positioning accuracy under the best conditions. There is a second official service based on L1 and L2 P-code measurements and broadcast data called the Precise Positioning Service (PPS).

In principle, because the P-code provides somewhat higher precision code measurements and the use of dual-frequency data removes virtually all of the ionospheric effect, PPS is capable of slightly more precise (and accurate) positioning. But because the P-code is encrypted, PPS is only available to so-called authorized users.

While meter-level positioning accuracy is sufficient for many, if not most applications, there are many uses of GNSS such as machine control, surveying and various scientific tasks, where accuracies better than 10 centimeters or even 1 centimeter are needed. Positioning accuracies at this level can’t be provided by pseudoranges alone and the use of carrier-phase measurements is required. Phase measurements are much more precise than code measurements although they are ambiguous and this ambiguity must be estimated and possibly resolved to the correct integer value.

Traditionally, phase measurements (typically dual-frequency) made by a potentially moving user receiver have been combined with those from a reference receiver at a well-known position to produce very precise (and accurate) positions. If done in real time (through use of a radio link of some kind), this technique is referred to as real-time kinematic or RTK.

A disadvantage of RTK positioning is that it requires reference station infrastructure including a radio link (such as mobile phone communications) for real-time results. Is there another way? Yes, and that’s PPP. PPP uses the more precise phase measurements (along with code measurements initially) on at least two carrier frequencies (typically) from the user’s receiver along with precise satellite orbit and clock data derived, by a supplier, from a global network. Precision, in this case, means a horizontal position accuracy of 10 centimeters or better.

In this month’s column, we travel along the road of PPP development, examine its current status, and look at where it might go in the near future."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- PPP-AR
- PPP
- Ambiguity resolution
- Integrity monitoring
- Single Frequency
- Multi-GNSS
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://www.gpsworld.com/innovation-examining-precise-point-positioning-now-and-in-the-future/
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

