---
title: Why are GNSS Carrier Signals in the L-Band?
subtitle: 
summary: 
authors:
- admin
tags: []
categories: []
date: "2017-02-05T00:00:00Z"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: "L-band signals"
  focal_point: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

The L band, as defined by the IEEE (Institute of Electrical and Electronics Engineers), is the 1 to 2 GHz range of the radio spectrum. The L band consists of two components, Aviation Radio Navigation Service (ARNS) and Radio Navigation Satellite Service (RNSS) and is utilized in many radar, satellite and terrestrial communications applications.


![png](./l_band_signals.png)

The L band has several advantages which marks it suitable for GNSSs. The L band has a low bandwidth due to its low frequency range. As a result, it is not suitable for streaming applications like video, voice and broadband connectivity. The L band waves penetrate clouds, fog, rain, storms, and vegetation, GNSS receivers can track the L Band signal in most weather conditions. The primary limitation of the L band signal is its inability to penetrate solid objects such as concrete buildings.

The GNSS carrier frequency to transport the data signals were required to meet the following requirements:
* Frequencies should be below 2 GHz, as frequencies above 2 GHz would require beam antennae for the signal reception.
* Ionospheric delays are significant for frequency below 1,000 MHz and above 10 GHz.
* PRN codes require a high bandwidth for code modulation on the carrier frequency. Therefore, a range of high frequencies with the possibility of a high bandwidth had to be chosen.
* Selected frequency should be in a range where the signal propagation is not influenced by weather phenomena like rain, snow, or clouds.

