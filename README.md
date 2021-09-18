# Meta Analysis and Harmonization of Conservation Games Data

Raw/ input files are in 'data' folder are output files in 'output' folder.

'Data Dictionary.xlsx' is the data dictionary file containing the variables and their descriptions.

The sequence for generation of datasets:

STEP | Description | Jupyer Notebook | Output files
--- | --- | --- | ---
1 |  Reducing player-level data to round level data | Grouping at Round level.ipynb | gabon_grp.csv, madgas_grp.csv, madken_grp.csv, orkney_grp.csv
2 | Harmonizing all variables and combining all datasets | Combine Datasets.ipynb | roundlevel_combined5.csv, roundlevel_combined7.csv
3 | Generating final mean and variance z-score file for 5 countries | Generate Summarized Normalized File 5.ipynb | meanvar_zscores5.csv
4 | For generating final mean and variance z-score file for 7 countries | Generate Summarized Normalized File 7.ipynb | meanvar_zscores7.csv
