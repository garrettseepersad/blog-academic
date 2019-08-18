---
# Course title, summary, and position.
linktitle: Reduction Of Initial Convergence Period In GPS PPP Data Processing
summary: "PhD Thesis : Currently being converted from a word document to markdown format
"
weight: 1

# Page metadata.
title: Abstract
date: "2012-09-09T00:00:00Z"
lastmod: "2012-09-09T00:00:00Z"
draft: true  # Is this a draft? true/false
toc: false  # Show table of contents? true/false
type: docs  # Do not modify.

# Add menu entry to sidebar.
# - name: Declare this menu item as a parent with ID `name`.
# - weight: Position of link in menu.
menu:
  msc_thesis:
    name: Abstract
    weight: 1
---

Precise Point Positioning (PPP) has become a popular technique to process data from GPS receivers by applying precise satellite orbit and clock information, along with other minor corrections to produce cm to dm-level positioning. Although PPP presents definite advantages such as operational flexibility and cost effectiveness for users, it requires 15-25 minutes initialization period as carrier-phase ambiguities converge to constant values and the solution reaches its optimal precision.
Pseudorange multipath and noise are the largest remaining unmanaged errors source in PPP. It is proposed that by reducing these effects carrier-phase ambiguities will reach the correct steady state at an earlier time, thus reducing the convergence period of PPP. Given this problem, this study seeks to improve management of these pseudorange errors.
The well-known multipath linear combination was used in two distinct ways: 1) to directly correct the raw pseudorange observables, and 2) to stochastically de-weight the pseudorange observables. Corrections to the observables were made in real-time using data from the day before, and post-processed using data from the same day. Post-processing has shown 47% improvement in the rate of convergence, as the pseudorange multipath and noise were effectively mitigated. A 36% improvement in the rate of convergence was noted when the pseudorange measurements were stochastically de-weighting using the multipath observable. The strength of this model is that it allows for real-time compensation of the effects of the pseudorange multipath and noise in the stochastic model.
