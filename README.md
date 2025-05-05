# Kobe Bryant Shot Visualization Dashboard

This project visualizes Kobe Bryant's NBA shooting data across multiple dimensions including shot type, location, time, and efficiency using interactive and animated R visualizations.

**Dataset:**  
This dataset contains all recorded shot attempts by Kobe Bryant from 1996 to 2016, including location, game context, and outcome.  
**Source:** [Kaggle - Kobe Bryant Shot Selection](https://www.kaggle.com/competitions/kobe-bryant-shot-selection)

## Required R Packages

The following R packages are required to run the dashboard and generate the visualizations:

```r
library(flexdashboard)
library(DT)
library(RColorBrewer)
library(tidyverse)
library(gridExtra)
library(knitr)
library(magick)
library(patchwork) 
library(viridis) 
library(gganimate)
library(ggalluvial)
library(scales)
library(plotly)
library(readr)
library(sf)
library(rnaturalearth)
library(dplyr)
library(treemap)
library(GGally)
library(ggplot2)
```

## How to Use

1. Download the dataset from the Kaggle link above and place it in your working directory.
2. Install all the required packages listed above.
3. Run the R script or R Markdown file — the dashboard and all visualizations will be generated automatically.

Enjoy exploring Kobe's legendary shot patterns!
