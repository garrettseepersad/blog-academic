---
title: Assessing the Performance of GNSS Receivers with Legacy and Mass Market State Space Correction Services
event: ION GNSS+ 2019
event_url: https://www.ion.org/gnss/abstracts.cfm?paperID=7790
location: Miami, Florida
summary: "Selection of an appropriate GNSS receiver and correction service can become challenging when considering a variety of factors such as network compatibility, correction quality, correction availability, multi-constellation support, latency, bandwidth, power, initialization time, integrity, performance as well as the different business models and distribution channels."

abstract: "
In a rapidly evolving GNSS market, where access to high precision positioning and timing is becoming accessible for mass market applications, the underlying challenge for GNSS users is in the determination of an appropriate correction service for their specific application. Selection of an appropriate GNSS receiver and correction service can become challenging when considering a variety of factors such as network compatibility, correction quality, correction availability, multi-constellation support, latency, bandwidth, power, initialization time, integrity, performance as well as the different business models and distribution channels. GNSS users would prefer a receiver with the capability to facilitate seamless and reliable network integration while satisfying their application’s requirements. 

GNSS correction services message formats generally fall into two categories, based either on the Observation State Representation (OSR) or a State Space Representation (SSR) of the errors. These two representations are used to mitigate key GNSS errors (e.g. satellite orbits, clocks and biases as well as ionospheric and tropospheric delays) in order to enable high precision GNSS performance. Observation Space Representation correction services are supplied by the legacy GNSS correction services providers. The term observation is used because the format is used, for example, to transport pseudorange and carrier phase measurements as recorded by a physical receiver. OSR corrections are also utilised for Network Real Time Kinematic (NRTK) services, where the range measurements are localised for the rover receiver using measurements from receivers in a local network. The downsides for mass-market applications is that dedicated correction generation and high-bandwidth two way communications are necessary for every receiver operating in the network. 
It is standard for global correction providers to utilize State Space Representation for data transmission format which is now being utilized by some Network RTK providers as well. SSR decomposes the errors into meaningful states by utilizing a network of reference stations to decorrelate the different GNSS error components. Generally, SSR corrections are preferred in contrast to OSR primarily because it is more bandwidth efficient and requires only one-way communication. One-way communication is a pre-requisite for satellite distribution as well as scalability with a focus towards mass market adoption to serve large fleets continentally and globally. By decomposing the range terms into state dependent terms, the correction data can be compressed. For example, the state terms can be transmitted at variable rates such as satellite orbits which are transmitted every 30 seconds and satellite clocks transmitted every 10 seconds. Correction services examined will include a localized base station with varying baseline lengths as well as a commercial Network RTK (NRTK) and global correction providers.

The u-blox F9 technology, a multi-band RTK module that can concurrently support all major GNSS constellations has the functionality to support all three types of correction services described (OSR for local base station and network RTK, and global SSR services). Local base stations are typically utilized in applications that require quick deployment who’s primarily interested in relative accuracy. The u-blox F9 module has the ability to also serve as a base station or integrate with other GNSS receiver manufactures whose receiver serves as the base station. Network RTK is based on a permanent reference network and traditional service providers have been unable to service cost sensitive mass market applications due to their intricate pricing schemes and varying levels of accuracy. SSR services such as Safe And Precise CORrection DAta (SAPCORDA), Quasi-Zenith Satellite System (QZSS) Centimeter Level Augmentation Service (CLAS), Trimble Real-Time eXtended (RTX) and Hexagon (HxGN) SmartNet are also based on a permanent reference station network and broadcast corrections using internet and/or satellite links. The u-blox F9 module supports Radio Technical Commission for Maritime Services (RTCM) corrections in the legacy Real Time Kinematic (RTK) and multiple signal messages (MSM) format as well as Safe And Precise Augmentation (SAPA) format for SSR services.
Varying factors from the different correction service providers serves as the motivation of this presentation to illustrate the intricacies around ensuring seamless and reliable network integration within the u-blox F9 module. The objectives of the presentation will be to assess the small, light and power efficient u-blox F9 module in the presence of varying correction services as well as provide recommendation of different correction services for a variety of mass market user applications. As has been commonly presented in literature, reduced station density and increasing baseline length will make it more challenging to successfully resolve ambiguities as a result of unmodelled atmospheric effects. To ensure reliable and robust ambiguity resolution, an adaptive ionospheric modelling strategy is utilized to mitigate against residual ionospheric effects due to long baselines and less dense reference networks. Results consist of solution analysis of convergence time (time to first ambiguity fix and time to a pre-defined performance level), position precision (repeatability) and position accuracy (solution error with respect to a reference system). Pre-defined thresholds are based on specifications utilized in mass market applications such as UAVs, automotive, container handling, robotic lawn mowers and agricultural machinery. Preliminary results show comparable results at the cm-level between the u-blox F9 module and the high end geodetic receivers in kinematic tests when utilizing the different correction services described.
"


# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2019-09-16T13:00:00Z"
date_end: "2019-09-20T15:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**u-blox**](https://www.u-blox.com/en/press-releases/u-blox-announces-u-blox-f9-robust-and-versatile-high-precision-positioning-technology)'
  focal_point: Right

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
- ublox

# Enable math on this page?
math: false
---