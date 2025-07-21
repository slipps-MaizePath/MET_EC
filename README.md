# MET_EC
Identifying key Environmental Covariates and quantifying their relationship associated with ear rot incidence in a multi-environment hybrid experiment

This manuscript is unpublished.

## a_NASAPower_WeatherDownload
Downloading raw weather data for each environment using NasaPower (R)
Environments with no planting or harvest date are skipped

## b_GenerateECs_AllEnvs
Generating the many ECs I am interested in for the many environments

## c_Format4SlidingWindow
Extensive formatting so that I can run the sliding-window pipeline
Genotypes with no silking date are skipped.

## d_Sliding Window
The sliding window function
Windows are unique to each genotype in each environment.

## e_WindowCorrelations
Correlations between ECs in each window.
Windows are unique to each genotype in each environment.
Correlation coefficients are bootstrapped

## f_EWAS
Chi-squared test between models (1 with a single window-by-ec combination, and null model without)
