---
title: 1.6	Research Contributions
linktitle:
toc: false
type: docs
date: "2019-05-05T00:00:00+01:00"
draft: false
menu:
  phd_thesis:
    parent: Chapter 1
    weight: 16

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 10
--- 

The research presented has been fuelled by the advancements made in ambiguity resolution by Laurichesse and Mercier (2007); Collins (2008); and Ge et al. (2008). To allow PPP GNSS measurement processing to be adopted into mass market applications that involves safety of life for e.g., the operation of autonomous vehicles, there is now increased requirement on the reliability, robustness and integrity of the user solution. To enable research within the realm of PPP ambiguity resolution it was required to expand of pre-existing PPP infrastructure to facilitate ambiguity resolution. Presented, is an overview of the implementation process to enable ambiguity resolution utilizing PPP-AR products. Receiver dependent equipment delays were mitigated by performing implicit single (satellite-to-satellite) differencing. Implicit differencing was selected to permit estimation of the receiver code clock, phase clock and relative carrier-phase L1-L2 measurement equipment delay. Satellite equipment delays were mitigated by utilizing products from different public providers to examine performance and interoperability.

PPP users have been expected to choose between either robust satellite orbit and clock products, which represents a combination from multiple analysis centres or select solutions from individual analysis centre that provides PPP-AR products. If PPP users selected combined satellite orbit and clock products they would not be able to resolve the ambiguity terms as the satellite equipment delays were not mitigated. If the PPP users opted for products from individual analysis centre that provided PPP-AR products they would be able to attain a more accurate and precise user solution but be vulnerable to network outages which is the motivational factor behind the novel research presented. The novel contributions are comprised of an in-depth analysis of the PPP-AR products in a combined and uncombined representation, mathematical representation of how to utilize the products in the different representations, examination of the performance of the PPP-AR products from different providers, the challenges involved in utilizing the PPP-AR products from the different providers and the strategies required to allow interoperability of the different products. 

As a result of the advancements made in the interoperability of PPP-AR products, permitted another significant novel contribution, development of a technique to combine multiple PPP-AR products. The combination of the PPP-AR products resulted in improved reliability of the user solution and robustness of the products as the user is no longer dependent on a single analysis centre. Combining of the PPP-AR products will be performed within the network processing engine which will ensure a continuous precise user solution
PPP and PPP-AR processing has become routinely utilized within applications such as crustal deformation monitoring, near real-time GNSS meteorology, orbit determination of LEO satellites as well as control and engineering surveys where requires few cm-level positioning accuracy. If PPP-AR is to be adopted in techniques such as lane navigation which requires 10 to 20 cm horizontal positioning accuracy, a re-examination of the role of ambiguity resolution in PPP is needed. Within this scope another novel contribution within this research exists as there has been limited focus on the utilization of ambiguity resolution as an integrity indicator as having a successfully resolved and validated solution indicates to the user increased accuracy, precision and reliability of the user solution thereby increasing the amount of trust that can be placed in the information supplied by the ambiguity resolved PPP data processing engine.


