---
title: 1.2	Review of PPP ambiguity resolution
linktitle:
toc: false
type: docs
date: "2019-05-05T00:00:00+01:00"
draft: false
menu:
  phd_thesis:
    parent: Chapter 1
    weight: 2

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 1
--- 


From the inception of GPS navigation, the largest hindrances to reliable few metre positioning was a result of the ionosphere delay. As a result of the ionosphere delay, two L-band navigation signals at 1575.42 MHz (L1) and 1227.60 MHz (L2) were deployed. After Selective Availability was turned off in 2000, it permitted more precise interpolation of the satellite clocks. As a result of the more precise modelling of the satellite clock error, delays due to the ionosphere became more prominent. The ionosphere delay led to the formation of the ionosphere-free linear combination using GPS data from a single receiver, as some of the early applications were for post-processing of static geodetic data for, e.g., rapid processing of GNSS tracking station data and crustal deformation monitoring. 

With the ionosphere delay mitigated using the ionospheric-free linear combination, conventional PPP’s relatively long convergence time fuelled research in single receiver ambiguity resolution (AR) (Laurichesse and Mercier 2007; Collins 2008; Mervart et al. 2008; Ge et al. 2008; Laurichesse et al. 2009; Teunissen et al. 2010; Bertiger et al. 2010; Geng et al. 2012). If the ambiguities could be isolated and estimated as integers, then there would be more information that could be exploited to accelerate convergence to provide cm-level horizontal accuracy within an hour of data collection, as illustrated in Figure 1.4. Resolution of these ambiguities converts the carrier-phases into precise pseudorange measurements, with measurement noise at the centimetre-to-millimetre level compared to the metre-to-decimetre-level of the direct pseudoranges (Blewitt 1989; Collins et al. 2010). Collins et al. (2008) and Laurichesse et al. (2009) saw improvements in hourly position estimates by 2 cm and Geng et al. (2010a) saw noticeable hourly improvements from 1.5, 3.8 and 2.8 cm to 0.5, 0.5, 1.4 cm for north, east and up, respectively.
 
![](/ch1/fig1_4.png)
*Figure 1.4: Illustration of the difference between the “float” and “fixed” solution in the horizontal component. NRC1 DOY 179, 2016 located in Ottawa, Canada.*

By 2010, the advantages of PPP ambiguity resolution (PPP-AR) in regards to improved convergence and position stability was well examined; however, PPP still required over 30 minutes to attain cm-level accuracy (Geng et al. 2010a). During this period, research in multi-GNSS (GPS and GLONASS) positioning and estimation of slant ionosphere delay began to exponentially increase. Similar to GPS only PPP-AR, multi-GNSS positioning resulted in improved convergence time and solution accuracy (Cai and Gao 2007, 2013; Banville et al. 2013; Li and Zhang 2014; Aggrey 2015). Li and Zhang (2014) showed a reduction in convergence time from 20 to 11 minutes to attain a predefined threshold of 10 cm 3D. Li and Zhang (2014) and Jokinen et al. (2013) showed the integration of GPS and GLONASS sped up initial convergence and increased the accuracy of float ambiguity estimates, which contributed to enhanced success rates and reliability of fixing GPS ambiguities. Estimation of the slant-ionosphere delay permitted instantaneous convergence, if accurate a priori atmospheric corrections were available to the PPP user (Geng et al. 2010a; Collins et al. 2012; Banville 2014). Also, if atmospheric corrections are provided, they assist with improving the reliability of ambiguity-resolved solutions, as uncertainties of the ambiguities will be lower by more than one order of magnitude (to ~0.2 cy 1σ) (Geng et al. 2010a; Collins and Bisnath 2011; Collins et al. 2012; Banville et al. 2014). Naturally, ambiguity resolved triple-frequency was of interest, which promised few minutes convergence, but also required additional linear combinations to be formed (Geng and Bock 2013), while it was possible to perform ambiguity resolution of the uncombined ambiguity terms. The evolution of the PPP user model is presented in Figure 1.5 as the performance converges to become more RTK-like, primarily due to the ability to perform ambiguity resolution within the PPP user model and the ability to introduce a priori atmospheric information.
 
![](/ch1/fig1_5.png)
*Figure 1.5: Evolution of the PPP user model.*

Over the past decade, each of the GNSSs began modernization efforts. The GPS Block IIF is now complete, consisting of 12 satellites transmitting on the L5 band and production of Block III has begun, which will have a 4th civilian signal on L1 (L1C) and promises enhanced signal reliability, accuracy, and integrity. For GLONASS, the third generation GLONASS-K satellites will change from Frequency Division Multiple Access (FDMA) to Code Division Multiple Access (CDMA), which will also transmit five navigation signals on the GLONASS’s L1, L2, and L3 bands. The transition from FDMA to CDMA will eliminate the Inter-frequency Channel Biases (ICBs), which will allow GLONASS to be more consistent with other GNSSs, as well as allowing for easier standardization of GLONASS’s satellite equipment delay products to enable ambiguity resolution. The European GNSS, GALILEO, is currently under development, with 14 operating satellites and 4 satellites under commission. Lastly, BeiDou began its transition towards global coverage in 2015. As of writing, 8 satellites have been launched and they are currently undergoing in-orbit validation (CSNO TARC 2018).

Within the scope of ambiguity resolution, the five core areas of research that are presented in Figure 1.6. The core focus within this research is in regard to the publicly available products that enable ambiguity resolution. Currently, publicly available products are limited to GPS only. Other research topics such as GLONASS ambiguity resolution and triple-frequency ambiguity resolution are reviewed in Sections 2.5 and 2.6 respectively. 
 
![](/ch1/fig1_6.png)
*Figure 1.6 Current research areas within PPP ambiguity resolution.*

