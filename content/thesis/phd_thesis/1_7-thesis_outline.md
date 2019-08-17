---
title: 1.7	Thesis Outline
linktitle:
toc: false
type: docs
date: "2019-05-05T00:00:00+01:00"
draft: false
menu:
  phd_thesis:
    parent: Chapter 1
    weight: 17

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 10
--- 

Chapter 2 provides an overview of the evolution of the PPP user model over the past two decades, how to process the measure as well as steps needed to expand the mathematical model to facilitate ambiguity resolution in PPP utilizing an uncombined representation. The standard practice in conventional PPP has been to linearly combine two pseudoranges and two carrier-phases to produce ionosphere-free linear pseudoranges and carrier-phase combinations which eliminates the first order ionosphere delay. Originally, the ionosphere delay was considered a nuisance parameter within the positioning community. As a result, the ionosphere-free linear combination was favoured in contrast to the estimation of the slant ionosphere delay. Nowadays, the PPP model permits multi-frequency, multi-constellation, slant ionosphere estimation and ambiguity resolution. Presented in each section is a review of the steps the PPP user model underwent within its evolution.

Chapter 3 examines the interoperability of high-rate satellite equipment delays which enable PPP-AR. Interoperability of PPP-AR products is important, as it can increase the reliability of the user solution while offering similar performance, in regard to precision and accuracy. Interoperability of the products is possible for the PPP user, as the mathematical model to enable an ambiguity resolved solution is similar. The different PPP-AR products contain the same information and would allow for a one-to-one transformation, allowing interoperability of the PPP-AR products. The PPP user will be able to transform independently generated PPP-AR products to seamlessly integrate within their PPP user solution. The seamless integration of the transformed products will allow the PPP user to have multiple solutions, which will increase the reliability of the solution, for, e.g., real-time processing. During real-time PPP processing, if there were an outage in the generation of the PPP-AR products, the user can instantly switch streams to a different provider. A novel component of the research presented is the examination of the interoperability of PPP-AR products with real data, as well as the presentation of the products in combined and uncombined representation.

Chapter 4 investigates the feasibility of combining the products from multiple providers of PPP-AR products. While satellite clock combinations are routinely utilized within the IGS, they currently disregard the fact that some ACs provide satellite clock products that account for the satellite equipment delays. Users have been expected to choose either a robust combined solution or select individual AC solutions that provide PPP-AR products that allow the user to compute an ambiguity resolved solution. The objective of this investigation was to develop and test a robust satellite clock combination, while preserving the underlying integer nature of the clocks and therefore the carrier-phase ambiguities to the user end to enable PPP-AR. The novelty of the research presented with this chapter is the development of a process to combine multiple products which enable robust PPP-AR.

Chapter 5 re-examines the role of ambiguity resolution in multi-GNSS PPP with the advent of quad-constellation, triple-frequency and external atmospheric constraints being provided to the PPP user. The focus and novelty of this chapter is in the quest to answer the question: Is ambiguity resolution in PPP needed for accuracy and/or for integrity? First, a re-examination of the significance between the float and ambiguity resolved PPP user solution is undertaken. Is the improvement significant enough for applications such as precision agriculture and autonomous vehicles to justify the additional cost and computational complexity of producing a PPP-AR solution? A novel component within the realm of PPP-AR is the analysis of ambiguity resolution as a metric to examine the integrity of the user solution.

Finally, Chapter 6 summarizes all the findings and provides recommendations for research in the near future.
