---
title: Processing a large batch of simulations
keywords:
last_updated: March 8, 2018
tags:
summary:
sidebar: usdos_sidebar
permalink: processing.html
folder: usdos
---
The post-processing pipeline is used to process all results, creating useful maps and graphics. Currently, the following maps are generated for the base run and each control type:
* For infections that were originally seeded in the given county:
  - Number of animals infected
  - Number of premises infected
  - Epidemic Extent (number of counties infected)
  - Duration of Infection
* County Risk (number of times the given county was infected given that it was not the seeded county)
* Proportion of infections attributed to local spread
* Proportion of infections attributed to shipment spread
* Most common routes of infection
* Least common routes of infection

Along with the maps, the post-processing code generates a variety of tables and graphs. A general list of these is as follows:
* Table of summary statistics to compare control types.
* QQplots comparing the distributions of each control type.
* Violin plots for exploratory analysis of the effect of control types.
* Regression and graphics to determine the effect of premise density, clustering, in-shipment number, and out-shipment number on the effectiveness of control.
