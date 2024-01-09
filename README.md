# Introduciton
This repository provides the codes and summary data of Shibasaki and Terui (2024) "****" [link to prerprint].
All codes are written in R using R studio, and used packages and their versions are available here and on the manuscript.
We also uploaded associated HTML files.

# Data
We provide the summary csv files that contain empirical food web data from Cohen (2010) (Cohen2010_summary_csv) and Web of Life (Summary_WebOf_life.csv).
Additionally, the summary data of baseline models (FCL_Null_model_summary.csv for random graph, and FCL_Cacade_Model_summary.csv for the cascadde model) and simulations (FCL_long/mean/short_simulations.csv) are available.

# Codes
## Summary codes and reproducing figures/tables in the manuscript.
Use Analysis_summary.Rmd. Almost all codes are available here.

## Empirical data processing and simulation codes
For Cohen (2010) data, see FCL_motif.Rmd.
For Web of Lide data, see WebOfLife_analysis.Rmd.
For Processing random graphs or the cascade model data, see NullModel.Rmd.
For simulations, see FCL_motif_simulations.Rmd.
For preliminary data analysis (i.e., including resource availability analysis), see Preliminary_analysis.Rmd The summary data exist in ./preliminary_with_resource.

# Difference in trophic positions wihtin motif
In the supplementary file, we analyzed the differences in trophic positions of species within a food web motif.
See Motif_TP.Rmd for source codes, and data are available in TP_Motif_dat.zip.
