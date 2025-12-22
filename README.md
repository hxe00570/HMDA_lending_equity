<<<<<<< HEAD
# Fair Lending Analytics and Disparity Framework

## Overview
This repository contains research artifacts for my Ph.D. application. 

The analysis focuses on:
- Mortgage approval rate disparities across states and metropolitan areas.
- Gender-based differences in loan pricing (rate spreads).
- Econometric modeling and geospatial visualization.

## Contents
- **ivy.py**: Python notebook performing HMDA data analysis.
- **data/**: CSV outputs including approval rates, gender gap summaries, and regression results.
- **visuals/**: Choropleth maps, heatmaps, and statistical plots.
- **framework/**: Mind map illustrating the Fair Lending Analytics and Disparity Framework.

## Methods
- Winsorization of rate spreads.
- Welch’s t-tests for gender gap significance.
- Fixed-effects regression with cluster-robust standard errors.
- Geospatial mapping using TIGER/Line shapefiles.

## How to Reproduce
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/hmda-loan-equity-analysis.git

## From Source
As you will see in the code I used colab tools to read this data from google drive. The raw data file is incredibly large and an improvement would be to use the API call. I would like to explore trends over time and this will be much more efficient.

TIGER/Line Shapefiles
Format:
Shapefile - 2007 to Present
TIGER/Line ASCII format - 2006 and earlier
Census 2000 available in both formats
The core TIGER/Line Files and Shapefiles do not include demographic data, but they do contain geographic entity codes that can be linked to the Census Bureau’s demographic data, available on data.census.gov. https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html  


HMDA Dataset Filtering
You can use the HMDA Data Browser to filter and download CSV files of HMDA data. These files contain all data fields available in the public data record and can be used for advanced analysis. You can also access the Data Browser API directly. For questions/suggestions, contact hmdahelp@cfpb.gov.
https://ffiec.cfpb.gov/data-browser/data/2024?category=states 
=======


\# Fair Lending Analytics and Disparity Framework



\## Overview

This repository contains research artifacts for my Ph.D. application. The analysis focuses on:

\- Mortgage approval rate disparities across states and metropolitan areas.

\- Gender-based differences in loan pricing (rate spreads).

\- Advanced econometric modeling and geospatial visualization.



\## Contents

\- \*\*ivy\_gsu.py\*\*: Python notebook performing HMDA data analysis.

\- \*\*data/\*\*: CSV outputs including approval rates, gender gap summaries, and regression results.

\- \*\*visuals/\*\*: Choropleth maps, heatmaps, and statistical plots.

\- \*\*framework/\*\*: Mind map illustrating the Fair Lending Analytics and Disparity Framework.



\## Methods

\- Winsorization of rate spreads.

\- Welch’s t-tests for gender gap significance.

\- Fixed-effects regression with cluster-robust standard errors.

\- Geospatial mapping using TIGER/Line shapefiles.



\## How to Reproduce

1\. Clone the repository:

&nbsp;  ```bash

&nbsp;  git clone https://github.com/<your-username>/hmda-loan-equity-analysis.git

2\. Install Dependencies:

&nbsp;   pip install pandas numpy statsmodels geopandas matplotlib seaborn

3\. Run the analysis:

&nbsp;   python hdma\_loan\_analysis.py


>>>>>>> 567a42c (Push research outputs)

