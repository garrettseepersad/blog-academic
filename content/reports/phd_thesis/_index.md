---
# Course title, summary, and position.
linktitle: Improving Reliability And Assessing Performance Of Global Navigation Satellite System Precise Point Positioning Ambiguity Resolution
summary: "PhD Thesis : Currently being converted from a word document to markdown format
"
weight: 1

# Page metadata.
title: Abstract
date: "2018-09-09T00:00:00Z"
lastmod: "2018-09-09T00:00:00Z"
draft: false  # Is this a draft? true/false
toc: false  # Show table of contents? true/false
type: docs  # Do not modify.

# Add menu entry to sidebar.
# - name: Declare this menu item as a parent with ID `name`.
# - weight: Position of link in menu.
menu:
  phd_thesis:
    name: Abstract
    weight: 1
---

Conventional Precise Point Positioning (PPP) has always required a relatively long initialization period (few tens of minutes at least) for the carrier-phase ambiguities to converge to constant values and for the solution to reach its optimal precision. The classical PPP convergence period is primarily caused by the estimation of the carrier-phase ambiguity from the relatively noisy pseudoranges and the estimation of atmospheric delay. If the underlying integer nature of the ambiguity is known, it can be resolved, thereby reducing the convergence time of conventional PPP. 
To recover the underlying integer nature of the carrier-phase ambiguities, different strategies for mitigating the satellite and receiver dependent equipment delays have been developed, and products made publicly available to enable ambiguity resolution without any baseline restrictions. There has been limited research within the scope of interoperability of the products, combining the products to improve reliability and assessment of ambiguity resolution within the scope of being an integrity indicator. This study seeks to develop strategies to enable each of these and examine their feasibility.
The advantage of interoperability of the different PPP ambiguity resolution (PPP-AR) products would be to permit the PPP user to transform independently generated PPP-AR products to obtain multiple fixed solutions of comparable precision and accuracy. The ability to provide multiple solutions would increase the reliability of the solution for, e.g., real-time processing: if there were an outage in the generation of the PPP-AR products, the user could instantly switch streams to a different provider. 
The satellite clock combinations routinely produced within the International GNSS Service (IGS) currently disregard that analysis centers (ACs) provide products which enable ambiguity resolution. Users have been expected to choose either an IGS product which is a combined product from multiple ACs or select an individual AC solution which provides products that enable PPP-AR. The goal of the novel research presented was to develop and test a robust satellite clock combination preserving the integer nature of the carrier-phase ambiguities at the user end. mm-level differences were noted, which was expected as the strength lies mainly in its reliability and stable median performance and the combined product is better than or equivalent to any single AC’s product in the combination process.
As have been shown in relative positioning and PPP-AR, ambiguity resolution is critical for enabling cm-level positioning. However, what if specifications where at the few dm-level, such as 10 cm and 20 cm horizontal – what role does ambiguity resolution play? The role of ambiguity resolution relies primarily on what are the user specifications. If the user specifications are at the few cm-level, ambiguity resolution is an asset as it improves convergence and solution stability. Whereas, if the user’s specification is at the few dm-level, ambiguity resolution offers limited improvement over the float solution. If the user has the resources to perform ambiguity resolution, even when the specifications are at the few dm-level, it should be utilized.

