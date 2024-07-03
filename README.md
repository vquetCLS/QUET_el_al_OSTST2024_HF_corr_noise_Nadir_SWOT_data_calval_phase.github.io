# New Definition for high frequency correlated noise in the Global Mean Sea Level uncertainty budget

## Context

The current GMSL uncertainty budget is described in [Guerou et al 2023](https://egusphere.copernicus.org/preprints/2022/egusphere-2022-330/egusphere-2022-330.pdf) and presented in the following figure.

![alt text](https://github.com/vquetCLS/QUET_el_al_OSTST2024_HF_corr_noise_Nadir_SWOT_data_calval_phase.github.io/blob/main/uncertainty_budget.jpg?raw=true)

This uncertainty budget leads to uncertainties associated to the GMSL parameters' of **$0.3 mm.yr^{-1}$** for the trend and **$0.05 mm.yr^{-2}$** for the acceleration over the whole altimetry era (approximately 30 years).
**Scientific goals** are to obtain an uncertainty associated with the trend of the GMSL of **$0.1 mm.yr^{-1}$** over a 10 years period (Meyssignac et al 2023). To do so, it is mandatory to better understand the measurement and associated errors.

In this study, we focus on the two first line of the GMSL uncertainty budget: High Frequency correlated noise (2-months and 1-year). The following figure (also from Guerou et al 2023) describes the relative contribution of all sources of uncertainty to the total uncertainty associated with the trend over 10 years periods.

![alt text](https://github.com/vquetCLS/QUET_el_al_OSTST2024_HF_corr_noise_Nadir_SWOT_data_calval_phase.github.io/blob/main/relative_contributions_uncertainty_budget.jpg?raw=true)

A better characterization of those high frequency correlated noise (red and orange curves) could lead to a decrease of their contribution and thus decrease the total uncertainty to get closer to the objective fixed by the climate scientists community.

## Data

Data used for this study was : Nadir SWOT SSHA (Sea Surface Height Anomaly) measurements from Cal/Val phase and DUACS SSHA grids.

The variable used was : $\Delta SSHA = SSHA_{SWOT} - SSHA_{DUACS}$. This variable contains **altimetry errors** and **natural oceanic variability** (not resolved by DUACS grids). 
The objective is to characterize the **variance** of $\Delta SSHA$.
