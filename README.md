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

Data used for this study was : Nadir SWOT SSHA (Sea Surface Height Anomaly) measurements from Cal/Val phase and DUACS SSHA grids. SWOT theoretical ground track is illustrated on the following figure (sampling of the ocean available in this study):

![alt text](https://github.com/vquetCLS/QUET_el_al_OSTST2024_HF_corr_noise_Nadir_SWOT_data_calval_phase.github.io/blob/main/SWOT_theoretical_ground_track.jpg?raw=true)

The variable used was : $\Delta SSHA = SSHA_{SWOT} - SSHA_{DUACS}$ (DUACS data are interpolated on the SWOT theoretical ground track). This variable contains **altimetry errors** and **natural oceanic variability** (not resolved by DUACS grids). 
The objective is to characterize the **variance** of $\Delta SSHA$.

## Description of results obtained 

### Time Correlation and Variance Gain

The variance of differences between measures from day $N$ and day $N+P$ was computed for all values of $P$ between 1 and 60 days. The result is illustrated in the following figure.
![alt text](https://github.com/vquetCLS/QUET_el_al_OSTST2024_HF_corr_noise_Nadir_SWOT_data_calval_phase.github.io/blob/main/time_corr_and_var_gain.jpg?raw=true)

A first order system model and the alisasing of the tide signal (13-days periodic signal) is fitted to compute a **total variance** gain ($\Delta V$), and a **correlation time** ($5\tau$: $99\%$ of the variance gain is obtained).
This leads to a characteristic correlation time of **$16.5 days$** and a total variance gain **$17 cm^{2}$**.

A similar analysis was performed on crossover points from several altimetry missions (J3, S3A, S3B, S6A, AL) to obtain differences at larger temporal scales (1-month to 1-year differences). Results are presented in the following figure:
![alt text](https://github.com/vquetCLS/QUET_el_al_OSTST2024_HF_corr_noise_Nadir_SWOT_data_calval_phase.github.io/blob/main/time_corr_and_var_gain_xovers.jpg?raw=true)

There are no significant additional error between 1-month and 1-year differences: the 2-months correlated noise will be replaced by **1-month correlated noise** ; and the **1-year correlated noise** will be **removed entirely** from the uncertainty budget of this study.

### Spatial Correlation

![alt text](https://github.com/vquetCLS/QUET_el_al_OSTST2024_HF_corr_noise_Nadir_SWOT_data_calval_phase.github.io/blob/main/mean_per_box_SLA.jpg?raw=true)
![alt text](https://github.com/vquetCLS/QUET_el_al_OSTST2024_HF_corr_noise_Nadir_SWOT_data_calval_phase.github.io/blob/main/explonation_of_the_method_spatial_correlation.jpg?raw=true)
![alt text](https://github.com/vquetCLS/QUET_el_al_OSTST2024_HF_corr_noise_Nadir_SWOT_data_calval_phase.github.io/blob/main/spatial_corr.jpg?raw=true)

### Impact on the GMSL parameters' associated uncertainties

![alt text](https://github.com/vquetCLS/QUET_el_al_OSTST2024_HF_corr_noise_Nadir_SWOT_data_calval_phase.github.io/blob/main/evolution_uncertainties_triangle_trend.jpg?raw=true)
![alt text](https://github.com/vquetCLS/QUET_el_al_OSTST2024_HF_corr_noise_Nadir_SWOT_data_calval_phase.github.io/blob/main/evolution_uncertainties_triangle_acceleration.jpg?raw=true)

![alt text](https://github.com/vquetCLS/QUET_el_al_OSTST2024_HF_corr_noise_Nadir_SWOT_data_calval_phase.github.io/blob/main/resulting_10years_trend_uncertainties.jpg?raw=true)
