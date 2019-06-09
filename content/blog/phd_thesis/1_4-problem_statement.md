---
title: 1.4	Problem Statement
linktitle:
toc: false
type: docs
date: "2019-05-05T00:00:00+01:00"
draft: false
menu:
  phd_thesis:
    parent: Chapter 1
    weight: 14

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 10
--- 

As previously stated, conventional PPP has always required a relatively long initialization period (few tens of minutes at least) for the carrier-phase ambiguities to converge to constant values and for the solution to reach the sub-dm-level. This situation is primarily caused by the estimation of the carrier-phase ambiguity from the relatively noisy pseudoranges and the estimation of atmospheric delay. The result is PPP can then take full advantage of the precise but ambiguous carrier-phase observations; however, the length of time it takes to reach the optimal solution is a major disadvantage to the wider use of the technique. If the underlying integer nature of the ambiguity is known, it can be resolved, thereby reducing the convergence time of conventional PPP. The challenge of ambiguity resolution in conventional PPP is due to equipment delays that are absorbed by the ambiguity state term within the least squares estimation process. These equipment delays are due to different filters used with the receivers and satellites as well as delays experienced within the antennas and cables.

To recover the underlying integer nature of the carrier-phase ambiguities, different strategies for mitigating the satellite and receiver dependent equipment delays have been developed, and products made publicly available to enable ambiguity resolution without any baseline restrictions. There has been limited research within the scope of interoperability of the products which enable ambiguity resolution. Interoperability of the products can occur within the network solution or within the user solution. The limitation of product interoperability within the user processing engine is ambiguity re-initialization due to changing of ambiguity resolution product providers. In addition, there has been no publish literature examining the performance of product interoperability. If the products are combined within the network processing engine, this will ensure a continuous precise user solution if one of the providers experiences an outage. As PPP and PPP-AR is being adopted by the mass market, which has less stringent accuracy specifications but higher integrity requirements, as a result, a reassessment of the role of ambiguity resolution is needed. 


