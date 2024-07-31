# Riddell-Young_etal_2024v2

This is the updated Matlab package (v2) that was used in the manuscript entitled “Abrupt changes in biomass burning during the last glacial period”, which is in review at Nature at the time of publishing this code. The code contains a one box methane stable isotope model to estimate the contribution of different sources to the glacial methane budget based on ice core measurements of atmospheric methane concentration and its stable isotope composition. There are three separate codes for the three intervals when the model is run. The three codes used to produce figures 1 through 4 are also included.

Required software: Matlab v2020 or later. Tested on Matlab R2024a. Required Matlab toolboxes: Curve Fitting Toolbox

Expected run time for each code: 1 minute or less

Step 1: Open and run H5_13C_onebox.m, H4_13C_onebox.m, and H1_13C_onebox.m in that order. Input: Rhodes_CFA.xlsx, H5_13C_Diff.xlsx, H4_13C_Diff.xlsx, H1_13C_Diff.xlsx, H4_dD_Diff.xlsx, TAL_age_Ben_BZT2018.xlsx, TD_CH4_Buiron2011_NewBern.xlsx, TD_dD_for_Ben.xlsx, 2box_sensitivity.xlsx, 2box_sensitivity_dd.xlsx. Output: H5_1box.xlsx, H5_1boxR.xlsx, H5_1boxMicVary.xlsx, H4_1box.xlsx, H4_1boxR.xlsx, H1_1box.xlsx, H1_1boxR.xlsx. Several supplemental figures and sensitivity tests. Output figures: H4_13C_onebox.m produces figures 2 and 3 of the main text.

Step 2: Open and run abruptCH4iso_Fig1.m, and BCCM_Fig4.m. Input: jbfill.m (a code designed to add shading to plots), H5_1box.xlsx, H5_1boxR.xlsx, H4_1box.xlsx, H4_1boxR.xlsx, H1_1box.xlsx, H1_1boxR.xlsx, H5_13C_Diff.xlsx, H4_13C_Diff.xlsx, H1_13C_Diff.xlsx, H4_dD_Diff.xlsx, Bock2017_Taldice_C13.xlsx, EDC_13C.xlsx, EDML_13C.xlsx, Bock_NGRIP_dD.xlsx, Bock_EDML_dD_2017.xlsx, Sowers_2006_dD.xlsx, Zhang_2014_HuluH1.csv, Wang2001_Hulu_H1.csv, strikis2018_H1_SAM.csv, Bauska_CO2.csv, NGRIP_18O.csv, Cheng_2016.csv, H4_brazil_wendt.csv, DO8HS4rIPDforBen.csv, Rhodes_CFA.xskx, WD06_CO2.xlsx, Bauska2018_d13C-CO2.csv, BCCM_July2024.csv, Diff_matrix.xlsx, H5diff.xlsx, H4diff.xlsx, and H1diff.xlsx.
Output: Figures 1 and 4 of the main text.
