---
layout: archive
title: ""
permalink: /research/
author_profile: true
---

<p align="center">
  <img src="/files/sub_grid_scale.png" width="600">
</p>
<p align="center">
<em>Figure is adapted from DOE PNNL SFA ICLASS Project Highlights</em>
</p>

Cloud processes occur across a wide spectrum of scales, ranging from sub-micrometers, such as Cloud Condensation Nuclei (CCN), to thousands of kilometers (cloud systems). However, current numerical models lack the capacity to explicitly address this entire range. Additionally, interactions among numerous aspects, including cloud microphysics, precipitation, moist turbulence, latent heat release, circulation, and radiation, complicate the problem.

Our research focuses on addressing challenges in three main areas: 1) Cloud formation and evolution over heterogeneous land and ocean surfaces, 2) factors that determine the lifecycle of cloud populations, including interactions among clouds and with their surrounding environments, and 3) aerosol-cloud interactions, particularly the impact of aerosols on cloud size distribution and lifecycle. We approach these topics in an integrated manner, utilizing a cloud parcel model, Large Eddy Simulations (LES), mesoscale regional models (such as Weather Research & Forecasting model, WRF), in-situ and remote sensing observational datasets, and cloud chambers.

Topic 1: Interactions among land, the boundary layer, and clouds
-

Landscape heterogeneities induce secondary circulation by modifying surface fluxes and their partitioning into sensible and latent heat fluxes. These modifications contribute to the formation of characteristics in the planetary boundary layer and the development of convective clouds. Variations in the landscape include differences in soil moisture levels and land-use types over land, as well as sea surface temperatures (SST) over the ocean.

<p align="center">
  <img src="/files/schematic_schematic.png" width="500">
</p>
<p align="center">
<em>Figure 9 in Publication [13].</em>
</p>


Our previous research in the Southern Great Plains, U.S., focused on the impacts of soil moisture heterogeneity on the timing, location, and intensities of shallow convective clouds [6,13]. Our studies, utilizing isentropic analysis, revealed that isentropes associated with upward motion are connected to the ground characterized by high latent heat fluxes, while isentropes associated with downward motion link precipitation to the ground characterized by high sensible heat fluxes. The mixing of dry, warm air parcels ascending from areas with high sensible heat fluxes and moist parcels from regions with high latent heat fluxes leads to cloud formation. This new mechanism explains how soil moisture heterogeneity provides the key ingredients, such as buoyancy and moisture, for shallow cloud formation. We also discovered that sub-mesoscale processes dominate upward energy transport in the boundary layer, whereas mesoscale circulations contribute to vertical energy transport above the boundary layer.


We continue to explore various types of heterogeneity, including variations in sea surface temperature (SST) over oceans and urbanization-induced changes in land use [11]. This research explores realistic scenarios at a regional scale by examining the multiple factors influencing sub-grid cloud formation and evolution. It elucidates when, where, and how clouds form and evolve, thereby contributing to our understanding of regional cloud-related phenomena such as local precipitation. This research also guides the development of parameterizations of convective clouds.


Topic 2: Interactions among clouds and surrounding environments
- 

Some puzzles in climate research are related to a limited understanding of the critical factors governing the lifecycle of cumulus clouds. These factors influence both the initiation of clouds and the various mixing processes during their lifecycle. However, current representations of convective clouds are based on 'bulk' environments and 'cylinder' cloud assumptions. These models do not consider the cloud evolution from a 'population' perspective (i.e., interactions among clouds) and often ignore the three-dimensional structure of clouds.

To shed some light on these processes, we tracked the lifecycle of thousands of individual shallow cumulus clouds in a large-eddy simulation during the Department of Energy (DOE) HI-SCALE field campaign in the U.S. Southern Great Plains [12,18]. We found that clouds with growing neighboring clouds tend to form above regions with greater surface heterogeneity. Conversely, clouds with decaying neighboring clouds are typically found above less heterogeneous surfaces. Additionally, those with decaying neighboring clouds experience greater instability and a more humid boundary layer. This suggests that evaporation below the cloud base likely occurs before these clouds are formed. Larger instability leads to higher vertical velocity and convergence within the cloud, resulting in stronger surrounding downdrafts and water vapor removal in the surrounding area. This appears to be the cause of the decay in neighboring clouds. 

<p align="center">
  <img src="/files/schematic_ccinter.png" width="600">
</p>
<p align="center">
<em>Figure 4 in Publication [18].</em>
</p>

Another study, using the same datasets, reveals that an increase in the perimeter of the cloud mask, driven by cloud edge irregularity, strongly correlates with subsequent cloud splitting. This effect is more pronounced than that driven by the growth of the perimeter due to aspect ratio [18]. Smaller gradients in cloud-shell properties across cloud boundaries are associated with a more irregular cloud edge, suggesting enhanced mixing of the clouds with the cloud-free environment. These findings indicate that the evolution of shallow cumulus clouds is partly driven by the irregularity of the cloud edge, through lateral mixing and cloud splitting.

We continue to explore interactions among clouds and with their surrounding cloud-free environments under different cloud regimes, in both idealized and realistic scenarios. These studies will help in parameterizing convective cloud from a 'population' perspective and contribute to a better understanding of the upscale growth and dissipation of clouds throughout their lifecycles.

Topic 3: Aerosol-cloud interactions 
- 

Aerosols, serving as cloud condensation nuclei, impact the evolution of cloud droplets. An increase in aerosol number concentration (Na) leads to an increase in both cloud condensation nuclei (CCN) and cloud droplet number concentration (Nc). This, in turn, reduces droplet sizes and enhances cloud albedo when liquid water content remains unchanged (i.e., the albedo effect). Additionally, the increased Na results in concurrent increases in Nc and relative dispersion (ε) of the cloud droplet size distribution, defined as the ratio of the standard deviation to the mean radius of the droplet size distribution (i.e., the dispersion effect). The enhanced ε negates the number effect and may be partly responsible for the overestimated indirect aerosol effect and the discrepancy among models in estimates of the indirect aerosol effect. Furthermore, increasing aerosols are thought to reduce the cloud droplet size, suppress precipitation, and enhance the suspension time of clouds (i.e., the lifetime effect). Another compensating effect from reduced cloud droplet size relies on entrainment-evaporation feedbacks: smaller droplets are more prone to evaporation, reducing the suspension time of clouds (entrainment-evaporation effect). All these effects mentioned above occur simultaneously, which complicates the net effects of aerosols on clouds.

<p align="center">
  <img src="/files/sketch_copy.png" width="400">
</p>
<p align="center">
<em>Figure 1 in Publication [2].</em>
</p>

Our early work focused on the regime classification of the dispersion effect [1,2]. We showed, using a parcel model, that a combined consideration of Nc (cloud droplet number concentration) and relative dispersion better characterizes the regime dependence of aerosol-cloud interactions than considering Nc alone. Given an updraft velocity (w), ε (relative dispersion) increases with increasing Na (aerosol number concentration) in the aerosol-limited regime, peaks in the transitional regime, and decreases with further increasing Na in the updraft-limited regime. This new finding further reconciles contrasting observations in the literature and reinforces the important role of the dispersion effect. The nonmonotonic behavior of ε further quantifies the relationship between the transitional Na and w, separating the aerosol- and updraft-limited regimes.

<p align="center">
  <img src="/files/entrainment.GIF" width="220">
</p>
<p align="center">
<em>Figure courtesy of Jingxi Sun.</em>
</p>

We continue to explore aerosol-cloud interactions by considering entrained aerosols [5]. Secondary activation of these entrained aerosols is thought to modify the cloud droplet size distribution. Future work aims to examine the effects of entrained aerosols on the evolution of cloud droplet distribution and their associated impacts on precipitation and cloud lifecycle, using a cloud parcel model, large eddy simulations, and cloud chamber experiments.

