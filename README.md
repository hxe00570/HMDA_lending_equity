# Fair Lending Analytics and Disparity Framework

## Overview
This repository contains research artifacts for my Ph.D. application. 

The analysis focuses on:
- Mortgage approval rate disparities across states and metropolitan areas.
- Gender-based differences in loan pricing (rate spreads).
- Econometric modeling and geospatial visualization.

## Contents
- **ivy_gsu.py**: Python notebook performing HMDA data analysis.
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

## As you will see in the code I used colab tools to read this data from google drive. The raw data file is incredibly large and an improvement would be to use the API call. I would like to explore trends over time and this will be much more efficient.


## From Source




