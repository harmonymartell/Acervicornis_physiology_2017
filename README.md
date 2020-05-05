# Acervicornis_physiology_2017
Data archive

# Methods

Photochemical efficiency, gross photosynthesis and respiration were measured at temperatures spanning 25 ºC to 36 ºC to examine the role of exposure on coral thermal performance.

Photochemical efficiency data was acquired via pulse amplitude modulation fluorometry. Triplicate measurements of variable fluorescence (Fv/Fm) were obtained from measurements of dark adapted Fv/Fm on three distinct locations of the same fragment. These technical replicate values were averaged to give mean colony Fv/Fm. 

Gross photosynthesis and respiration were measured via respirometry at five distinct temperatures between 25 ºC to 36 ºC. Measurements were performed at temperatures from 25.4 ºC to 35.7 ºC, at 2.5 ºC to 3 ºC intervals in each experiment.  Rates of dark respiration and light-saturated net photosynthesis were quantified by measuring O2 evolution with the coral respirometry apparatus. Rates of dark respiration (R), net photosynthesis (PNET) and gross photosynthesis (PGROSS) were calculated from changes in dissolved O2 concentration as in Aichelman, Zimmerman, and Barshis (2019).  Recorded [O2] values were corrected for temperature and salinity based on the correction calculations provided by the PreSens system.  Slopes of dO2/dt (nmol O2 mL-1 min-1) in the dark (R) and in the light (PNET) were calculated from linear sections of each trace by least squares regression.  Metabolic rates were corrected for the combined effects of instrument drift and microbial metabolism from the seawater in a single chamber without coral measured continuously, scaled to chamber volume (mL) and normalized to coral tissue surface area (cm2, see below).  Gross photosynthesis (PGROSS) was calculated as PNET + |R|.

# Usage Notes
All .txt and.csv raw data files used to calculate the numbers presented in each table and figure are included here.
    
# TEMPERATURE
All temperature loggers were calibrated to a common NIST thermometer; temperature data is presented in ESM Figure S3 and tabulated in ESM Table S1; DHM data for both treatements are presented in Fig. 1
acute_measTemp_DHM_holdingTank.csv contains the raw, calibrated in situ temperature data measured by the logger from the holding tank in the acute treatment.
acute_measTemp_DHM_experimentalTank.csv contains the raw, calibrated in situ temperature data measured by the logger from the experimental tank in the acute treatment.
ramp_measTemp_DHM_holdingTank.csv contains the raw, calibrated in situ temperature data measured by the logger from the holding tank in the cumulative treatment.
ramp_measTemp_DHM_experimentalTank.csv contains the raw, calibrated in situ temperature data measured by the logger from the experimental tank in the cumulative treatment.
    
# RESPIROMETRY
All oxygen evolution data was measured using the OXY-mini by PreSens, and was calibrated according to manufacturer protocols.

All raw oxygen evolution data are found with the naming convention trt_tempC P or R - ch# where

- trt is the treatment, acute or cumulative
- temp is the measurement temperature
- P or R is the photosynthesis or respiration measurement (in some cases both) 
    - - ch# corresponds to the chamber 
            e.g., acute_25CP-ch1.txt was from acute treatment, at 25C measuring photosynthesis for chamber 1

timebreaks_acute.txt contains the start and stop times of the raw oxygen evolution for the linear regression calculations of the acute treatment

timebreaks_ramp.txt contains the start and stop times of the raw oxygen evolution for the linear regression calculations of the cumulative treatment

acuteSurfaceArea.csv includes the surface area to calculate oxygen evolved per unit surface area in the acute treatment

rampSurfaceArea.csv includes the surface area to calculate oxygen evolved per unit surface area in the cumulative treatment

# MODEL FITS

All values processed from raw are found in metabData.csv, FvFmData.csv and presented in Figs 2A-C, 3A-C, 4A-B; these values were used for the statistics presented in the text
 & Table 2
