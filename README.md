# Conservation-Games-Meta-Analysis

Raw/ input files are in 'data' folder are output files in 'output' folder.

The sequence for generation of datasets:

1) For reducing player-level data to round level data: [Grouping at Round level.ipynb](https://github.com/ApurvaBhargava/Meta-Analysis-Conservation-Games/blob/master/Grouping%20at%20Round%20Level.ipynb)\
Output: gabon_grp.csv, madgas_grp.csv, madken_grp.csv, orkney_grp.csv

2) For harmonizing all variables and combining all datasets: [Combine Datasets.ipynb](https://github.com/ApurvaBhargava/Meta-Analysis-Conservation-Games/blob/master/Combine%20Datasets.ipynb)\
Output: roundlevel_combined5.csv, roundlevel_combined7.csv

3) For generating final mean and variance z-score file for 5 countries: [Generate Summarized Normalized File 5.ipynb](https://github.com/ApurvaBhargava/Meta-Analysis-Conservation-Games/blob/master/Generate%20Summarized%20Normalized%20File%205%20countries.ipynb)\
Output: meanvar_zscores5.csv

4) For generating final mean and variance z-score file for 7 countries: [Generate Summarized Normalized File 7.ipynb](https://github.com/ApurvaBhargava/Meta-Analysis-Conservation-Games/blob/master/Generate%20Summarized%20Normalized%20File%207%20countries.ipynb)\
Output: meanvar_zscores7.csv

The data dictionary is given [here](https://github.com/ApurvaBhargava/Meta-Analysis-Conservation-Games/blob/master/Data%20Dictionary.xlsx).
