# A3-hcds-hcc-bias

## Goal of the project
This project aims to uncover bias in political wikipedia articles by assessing the quality of wikipedia articles about politicians in relation to the population sizes of the countries in which they were published. Coverage and relative quality are being assessed for several countries and geographic regions.

## Data acquisition
The following publicly available datasets were used: 

* List of wikipedia articles (retrieved from [figshares](https://figshare.com/articles/Untitled_Item/5513449))
* Population size per country and region (retrieved from [Population Reference Bureau(https://www.prb.org/international/indicator/population/table/))
* Article quality (retrieved from the [ORES REST API](https://ores.wikimedia.org/v3/#!/scoring/get_v3_scores_context_revid_model)) 

Detailed information about each dataset can be looked up on the respective web site. All datasets were also downloaded and saved under [data raw](https://github.com/malina-scheuer/A3-hcds-hcc-bias/tree/main/data_raw)

## Data processing & analysis  
All data processing steps and the final data analysis can be performed by running the code in the jupyter notebook file. [A3_Wikipedia_ORES_Bias.ipynb](https://github.com/malina-scheuer/A3-hcds-hcc-bias/blob/main/A3_Wikipedia_ORES_Bias.ipynb)

Just download the complete repository and run the jupyter notebook. It will output you the results and analysis of this project.
