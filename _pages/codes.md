---
layout: archive
title: "Codes and Useful Links"
permalink: /codes/
author_profile: true
---

Cloud Parcel Model
---
This cloud parcel model simulates the updraft cooling of a cloud parcel with entrainment-mixing and entrained aerosols in Fortran 95. 
The initial development of this model was supported by the U.S. Department of Energy’s Earth System Modeling program via the Fast-physics System Testbed and Research project and Atmospheric System Research program through Stony Brook University and Brookhaven National Laboratory. 
The adiabatic version was developed by comparing with two other similar models by Graham Feingold/Huiwen Xue and Yiran Peng in 2014. 
The author would thank them for the kind sharing. The entrainment-mixing version was developed between 2015-2017.

**Associated publications**

- Chen, J., Y. Liu, M. Zhang, and Y. Peng (2016), New understanding and quantification of the regime dependence of aerosol-cloud interaction for studying aerosol indirect effects, Geophysical Research Letter, 43, 1780–1787, doi:10.1002/2016GL067683.

- Chen, J., Y. Liu, M. Zhang, and Y. Peng (2018), Height dependency of aerosol-cloud interaction regimes, Journal of Geophysical Research: Atmospheres, doi: 10.1002/2017JD027431.

- Chen, J., Y. Liu and M. Zhang (2020), Effects of Lateral Entrainment-Mixing with Entrained Aerosols on Cloud Microphysics, Geophysical Research Letter, doi: 10.1029/2020GL087667.

**Github link**: https://github.com/Jingyi-Chen/cloud_parcel_mode

2D Object Tracker
---
The Python FLEXible object TRacKeR (PyFLEXTRKR) is a flexible atmospheric feature tracking software package. 
The software can track any 2D objects and handle merging and splitting explicitly. 
PyFLEXTRKR has specific capabilities to track convective clouds from a variety of observations and model simulations, including: 1) individual convective cells, and 2) mesoscale convective systems (MCSs) using radar, satellite, and model data. The package has scalable parallelization options and has been optimized to work on large datasets including global kilometer-scale data.

**Associated publications**

- Feng, Z., Hardin, J., Barnes, H. C., Li, J., Leung, L. R., Varble, A., and Zhang, Z. (2023): PyFLEXTRKR: a flexible feature tracking Python software for convective cloud analysis, Geosci. Model Dev., doi:10.5194/gmd-16-2753-2023.

- An example to use it for shallow cumulus: Chen, J., S. Hagos, Z. Feng, J. D. Fast, and H. Xiao (2023), The Role of Cloud-Cloud Interactions in the Lifecycle of Shallow Cumulus Clouds, Journal of Atmospheric Science, doi: 10.1175/JAS-D-22-0004.1

**Github link**: https://github.com/FlexTRKR/PyFLEXTRKR

