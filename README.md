<!-- # OMI_20th_century -->
Outgoing Longwave Radiation based MJO index (OMI) for the 20th century 
=====
<!-- [![DOI](https://zenodo.org/badge/520879810.svg)](https://zenodo.org/badge/latestdoi/520879810) <br /> -->
This repository contains the data files of Outgoing Longwave Radiation based MJO index (OMI) that span from 1900-2010.
<br /> <br />
 
<!-- 
**Overview**
-----
- This repository contains the data of the Indo-Pacific Deep Convection Favoring Pool (Indo-Pacific Warm Pool defined with time-varied SST threshold).
 <br />  
 -->

**About the 20th century OMI**
-----
- The OMI is a RMM-like index derived solely from outgoing longwave radiation (OLR) reanalyzed in the 20th century. It provides a more accurate representation of the convective characteristics of the Madden-Julian Oscillation (MJO) and can be applied to the pre-satellite era, where satellite-based OLR data was unavailable.
- The RMM index (Wheeler and Hendon, 2004) focuses on the circulation of MJO rather than its convective characteristics (Leung et al., 2022). Meanwhile, the limited duration of OLR observations limits the data length of the RMM index. These limitations present a challenge for studying the long-term changes in MJO convective activity over the past century. Therefore, the OMI, constructed using OLR data from 20th century reanalysis, is utilized to address these issues.
- The construction method of the OMI is introduced by Kiladis et al. (2014), which includes the following steps: (1) applying a 30-96-day eastward filter on daily OLR between 20°S and 20°N; (2) performing Empirical Orthogonal Function (EOF) onto the filtered OLR and obtain the first two principal components (PCs); (3) to project the PCs onto the OLR, which has been filtered for 20-96-day, to obtain OMI1 (PC1) and OMI2 (PC2).
- Please refer to [Kiladis et al. (2014)]([https://doi.org/10.1175/MWR-D-13-00301.1](https://doi.org/10.1175/MWR-D-13-00301.1)/ ) for more detail about the calculation procedure and the science behind it.
 <br /> 
 
**Data files**
-----
- **OMI-ERA20C**
  - Description: OMI derived based on the ERA-20C reanalysis.
  - Location: [data/OMI-ERA20C.xlsx](https://github.com/jeremychleung/OMI_20th_century/tree/main/data/OMI-ERA20C.xlsx)
  - Temporal coverage: 1900–2010

  
- **OMI-NOAA20CR**
  - Description: OMI derived based on the NOAA-20CRv2c reanalysis.
  - Location: [data/OMI-NOAA20CR.xlsx](https://github.com/jeremychleung/OMI_20th_century/tree/main/data/OMI-NOAA20CR.xlsx)
  - Temporal coverage: 1900–2015
  
<br /> 
  

**Citation**
-----
If you use the OMI-ERA20C or OMI-NOAA20CR in a publication or for any other purposes, please cite (to be uploaded)
<!--

-->

<br /> 

**References**
-----
<!-- - Wheeler, M.C., Hendon, H.H. An All-Season Real-Time Multivariate MJO Index: Development of an Index for Monitoring and Prediction. Mon Weather Rev 132:1917–1932 (2004). https://journals.ametsoc.org/view/journals/mwre/132/8/1520-0493_2004_132_1917_aarmmi_2.0.co_2.xml -->
- Wheeler, M.C., Hendon, H.H. An All-Season Real-Time Multivariate MJO Index: Development of an Index for Monitoring and Prediction. Mon Weather Rev 132:1917–1932 (2004). https://journals.ametsoc.org/view/journals/mwre/132/8/1520-0493_2004_132_1917_aarmmi_2.0.co_2.xml
- Leung, J.CH., Qian, W., Zhang, P. et al. Geopotential-based Multivariate MJO Index: extending RMM-like indices to pre-satellite era. Clim Dyn (2022). 
https://doi.org/10.1007/s00382-022-06142-2
- Kiladis, George N., Juliana Dias, Katherine H. Straub, Matthew C. Wheeler, Stefan N. Tulich, Kazuyoshi Kikuchi, Klaus M. Weickmann, and Michael J. Ventrice. "A Comparison of OLR and Circulation-Based Indices for Tracking the MJO", Monthly Weather Review 142, 5 (2014): 1697-1715, 
https://doi.org/10.1175/MWR-D-13-00301.1
<br /> 


**Contact**
-----
If you have any questions about the data, feel free to contact Dr. Jeremy Leung (chleung@pku.edu.cn or liangzx@gd121.cn).
<br /> 
