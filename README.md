# Notebook Analysis

These notebooks perform the analysis for the paper:

> Maull, K. E., Ameko, A., Alter, R. _et al_, "OpenIoTwx: A Decentralized Automated IoT Weather Station Architecture", 2025. _Submitted to [MDPI Sensors Journal]()._

## Data

The data for this analysis come from  [National Ecological Observatory Network (NEON)](https://www.neonscience.org/):

### Temperature 

* NEON (National Ecological Observatory Network). Single aspirated air temperature (DP1.00002.001).  https://data.neonscience.org  (accessed October 7, 2023)

    * **Top Level Data Source:** [https://data.neonscience.org/data-products/DP1.00002.001](https://data.neonscience.org/data-products/DP1.00002.001)

### Relative Humidity
* NEON (National Ecological Observatory Network). Relative humidity (DP1.00098.001). https://data.neonscience.org (accessed October 7, 2023)


    * **Top Level Data Source:** [https://data.neonscience.org/data-products/DP1.00098.001](https://data.neonscience.org/data-products/DP1.00098.001) 
    
### PM2.5 / Particulate Matter

* NEON (National Ecological Observatory Network). Dust and particulate size distribution (DP1.00017.001). https://data.neonscience.org (accessed October 7, 2023)

    * **Top Level Data Source:** [https://data.neonscience.org/data-products/DP1.00017.001](https://data.neonscience.org/data-products/DP1.00017.001)

### Precipitation

* NEON (National Ecological Observatory Network). Precipitation (DP1.00006.001). https://data.neonscience.org (accessed October 7, 2023)

    * **Top Level Data Source:** [https://data.neonscience.org/data-products/DP1.00006.001](https://data.neonscience.org/data-products/DP1.00006.001)

## Specific Data Files
    
Specific data files use in the analysis can be obtained here:

* NEON (National Ecological Observatory Network) (2023), AmeriFlux BASE US-xRM NEON Rocky Mountain National Park, CASTNET (RMNP), Ver. 8-5, AmeriFlux AMP, (Dataset). https://doi.org/10.17190/AMF/1579723


## Notebooks

| Notebook | Purpose | Link | 
|:--: | :--- | :--- |
| 1 | Source data loading from CHORDS portal. | [./nb01_data_loading.ipynb](./nb01_data_loading.ipynb) |
| 2 | Basic analysis notebook for graphs used in the Validation section of the paper. | [./nb02_data_analysis.ipynb](./nb02_data_analysis.ipynb) |
