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
- OMI is a MJO index . . .
- 
- Please refer to [Leung et al. (2022)](https://doi.org/ ) for more detail about the calculation procedure and the science behind it.
 <br /> 
 
**Data files**
-----
- **σ<sub>SST_conv</sub> derived based on ERSSTv5 and GPCP**
  - Description: Time-varied SST threshold (σ<sub>SST_conv</sub>, unit: °C) for deep convection of intensity, derived based on SST (from ERSSTv5) and precipitation (GPCP).
  - Location: [data/02-sst_threshold_ersst_gpcp.csv](https://github.com/jeremychleung/Indo-Pacific-Deep-Convection-Favoring-Pool/blob/main/data/02-sst_threshold_ersst_gpcp.csv)
  - Temporal coverage: 1979–2020
  - Rows: Year
  - Columns: Convection intensity (defined based on average monthly precipitation)
  
- **σ<sub>SST_conv</sub> derived based on HadISST and GPCP**
  - Description: Time-varied SST threshold for deep convection (σ<sub>SST_conv</sub>, unit: °C) derived based on SST (from HadISST) and precipitation (GPCP).
  - Location: [data/02-sst_threshold_hadisst_gpcp.csv](https://github.com/jeremychleung/Indo-Pacific-Deep-Convection-Favoring-Pool/blob/main/data/02-sst_threshold_hadisst_gpcp.csv)
  - Temporal coverage: 1979–2020
  - Rows: Year
  - Columns: Convection intensity (defined based on average monthly precipitation)
  
- **σ<sub>SST_conv</sub> derived based on 20 CMIP6 models**
  - Description: Time-varied SST threshold for deep convection (σ<sub>SST_conv</sub>, unit: °C) derived based on model-simulated SST and precipitation.
  - Models: ACCESS-CM2 / CAMS-CSM1-0 / CAS-ESM2-0 / CESM2-WACCM / CMCC-CM2-SR5 / CMCC-ESM2 / EC-Earth3 / EC-Earth3-Veg / FGOALS-f3-L / FGOALS-g3 / GFDL-ESM4 / INM-CM4-8 / INM-CM5-0 / IPSL-CM6A-LR / KACE-1-0-G / MIROC6 / MPI-ESM1-2-HR / MPI-ESM1-2-LR / MRI-ESM2-0 / NESM3 / TaiESM1
  - Experiments: Historical runs / SSP1-2.6 / SSP2-4.5 / SSP5-8.5
  - Location: data/cmip_{modelname}/06-sst_threshold_{modelname}_{experiment}_r1i1p1f1.csv <br /> 
  (e.g., [data/cmip_ACCESS-CM2/06-sst_threshold_ACCESS-CM2_historical_r1i1p1f1.csv](https://github.com/jeremychleung/Indo-Pacific-Deep-Convection-Favoring-Pool/blob/main/data/cmip_ACCESS-CM2/06-sst_threshold_ACCESS-CM2_historical_r1i1p1f1.csv))
  - Temporal coverage: 1850-2014 for Historical runs / 2015-2100 for future projections
  - Rows: Year
  - Columns: Convection intensity (defined based on average monthly precipitation)

- **DCFP derived based on ERSSTv5 and GPCP**
  - Description: Area (unit: 10<sup>7</sup> km<sup>2</sup>) of deep convection favoring pool (DCFP) defined by time-varied σ<sub>SST_conv</sub>), based on SST (from ERSST) and precipitation (GPCP).
  - Location: [data/12-dcfp_ersst_gpcp.csv](https://github.com/jeremychleung/Indo-Pacific-Deep-Convection-Favoring-Pool/blob/main/data/12-dcfp_ersst_gpcp.csv)
  - Temporal coverage: 1979-2020
  - Rows: Year
  - Columns: Convection intensity (defined based on average monthly precipitation)
  
- **DCFP derived based on HadISST and GPCP**
  - Description: Area (unit: 10<sup>7</sup> km<sup>2</sup>) of deep convection favoring pool (DCFP) defined by time-varied σ<sub>SST_conv</sub>), based on SST (from HadISST) and precipitation (GPCP).
  - Location: [data/12-dcfp_hadisst_gpcp.csv](https://github.com/jeremychleung/Indo-Pacific-Deep-Convection-Favoring-Pool/blob/main/data/12-dcfp_hadisst_gpcp.csv)
  - Temporal coverage: 1979-2020
  - Rows: Year
  - Columns: Convection intensity (defined based on average monthly precipitation)

- **DCFP derived based on 20 CMIP6 models**
  - Description: Area (unit: 10<sup>7</sup> km<sup>2</sup>) of deep convection favoring pool (DCFP) defined based on model-simulated time-varied σ<sub>SST_conv</sub>).
  - Models: ACCESS-CM2 / CAMS-CSM1-0 / CAS-ESM2-0 / CESM2-WACCM / CMCC-CM2-SR5 / CMCC-ESM2 / EC-Earth3 / EC-Earth3-Veg / FGOALS-f3-L / FGOALS-g3 / GFDL-ESM4 / INM-CM4-8 / INM-CM5-0 / IPSL-CM6A-LR / KACE-1-0-G / MIROC6 / MPI-ESM1-2-HR / MPI-ESM1-2-LR / MRI-ESM2-0 / NESM3 / TaiESM1
  - Experiments: Historical runs / SSP1-2.6 / SSP2-4.5 / SSP5-8.5
  - Location: data/cmip_{modelname}/16-dcfp_{modelname}_{experiment}_r1i1p1f1.csv <br /> 
  (e.g., [data/cmip_ACCESS-CM2/16-dcfp_ACCESS-CM2_historical_r1i1p1f1.csv](https://github.com/jeremychleung/Indo-Pacific-Deep-Convection-Favoring-Pool/blob/main/data/cmip_ACCESS-CM2/16-dcfp_ACCESS-CM2_historical_r1i1p1f1_.csv))
  - Temporal coverage: 1850-2014 for Historical runs / 2015-2100 for future projections
  - Rows: Year
  - Columns: Convection intensity (defined based on average monthly precipitation)
  
  
<br /> 
  

**Citation**
-----
If you use the GMM index in a publication or for any other purposes, please cite 
<!--
- Leung, J.CH., Qian, W., Zhang, P. et al. Geopotential-based Multivariate MJO Index: extending RMM-like indices to pre-satellite era. Clim Dyn (2022). https://doi.org/10.1007/s00382-022-06142-2
-->
- Leung, J.CH., Zhang, B., Gan, Q. et al. On the differential expansion speeds of Indo-Pacific warm pool and deep convection favoring pool under greenhouse warming.  npj Climate and Atmospheric Science (under Review). 
- Zenodo archive: https://doi.org/10.5281/zenodo.6977567

<br /> 

**References**
-----
<!-- - Wheeler, M.C., Hendon, H.H. An All-Season Real-Time Multivariate MJO Index: Development of an Index for Monitoring and Prediction. Mon Weather Rev 132:1917–1932 (2004). https://journals.ametsoc.org/view/journals/mwre/132/8/1520-0493_2004_132_1917_aarmmi_2.0.co_2.xml -->
- Leung, J.CH., Zhang, B., Gan, Q. et al. On the differential expansion speeds of Indo-Pacific warm pool and deep convection favoring pool under greenhouse warming.  npj Climate and Atmospheric Science (under Review). 
- Hoyos, C.D., Webster, P.J. Evolution and Modulation of Tropical Heating from the Last Glacial Maximum through the Twenty-First Century. Climate Dynamics (2012).
- Johnson, N.C., Xie, S.P. Changes in the Sea Surface Temperature Threshold for Tropical Convection. Nature Geoscience (2010).
<br /> 


**Contact**
-----
If you have any questions about the data, feel free to contact Dr. Jeremy Leung (chleung@pku.edu.cn or liangzx@gd121.cn).
<br /> 
