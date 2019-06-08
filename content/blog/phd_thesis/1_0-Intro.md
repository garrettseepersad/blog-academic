--- 
title: 1.0 Introduction into PPP GNSS measurement processing
linktitle:
toc: false
type: docs
date: "2019-05-05T00:00:00+01:00"
draft: false
menu:
  phd_thesis:
    parent: Chapter 1
    weight: 1

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 1
--- 

Navigation is a very ancient skill or art, which has become a complex science. It is essentially about travel and finding the way from one place to another and there are a variety of means by which this objective may be achieved (Britting 1971). Navigation has been evolving since the beginning of human history and has always been a critical aspect in our (society’s) development. Navigation systems have taken many forms, varying from simple ones such as those making use of landmarks, compasses and stars, to more modern techniques such as the utilization of artificial satellites.

Satellite-based navigation technology was introduced in the early 1960s. The first such system was the U.S. Navy Navigation Satellite System (NNSS), known as TRANSIT, in which the receiver measured Doppler shifts of the signal as the satellite transited with a navigational accuracy of 25-500 m. In 1978, the Global Positioning System (GPS) was introduced. GPS is a satellite-based radio-positioning and time transfer system designed to provide all-weather, 24-hour coverage for military users and reduced accuracy for civilian users. Since then, it has become the backbone of a whole body of navigation and positioning technologies.

Currently, the U.S., Russia, the European Union (E.U.), and China are each operating or in the case of the latter two, developing individual Global Navigation Satellite Systems (GNSS’s): GPS, GLONASS, GALILEO and BeiDou, respectively. Evolving GNSSs can provide the worldwide community with several benefits, such as the ability to work in challenging environments with limited visibility of satellites, increased positioning accuracy, more robust detection and exclusion of anomalies, more accurate timing reference as well as improved estimation of tropospheric and ionospheric parameters.

GNSSs can be augmented with other systems which leads to an improvement in the navigation system's attributes, such as accuracy, precision, reliability, availability and integrity through the integration of external information into the adjustment process. These augmentation systems can be broadly grouped into satellite-based augmentation systems (SBAS) and ground-based augmentation system (GBAS). SBAS supports wide-area or regional augmentation through the use of additional satellite-broadcast messages where as GBAS utilizes terrestrial based radio messages. Additional information on augmentation systems can be found in Hofmann-Wellenhof et al. (2007), Kaplan and Hegarty (2006), Kee et al. (1991), Leick (1995) and Van Diggelen (2009).

## 