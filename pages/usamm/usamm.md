---
title: U.S. Animal Movement Model
keywords:
last_updated: May 8, 2024
tags:
summary: USAMM is a Bayesian Model based software for estimating county-to-county animal shipments. USAMM includes predictions that correct for overdispersion of predicted movements, incorporating seasonality, validating intrastate movement predictions and expanding inference to multiple years.
sidebar:
permalink: usamm.html
folder: usamm
---

# Modeling Animal Movement

The U.S. Animal Movement Model (USAMM) is a Bayesian model software for estimating cattle and swine shipments in the U.S. The latest version of the uses a hierarchical modeling approach to predict the number of non-slaughter shipments within the conterminous U.S. with a high level of detail. The predictions are informed by an analysis of an underlying data set of a 10% stratified sample of 2009 Certificates of Veterinary Inspection for interstate shipments from 47 states, together with multiple National Agricultural Statistics Survey (NASS) covariates.

Multiple versions of USAMM have been produced, and the current latest available for both cattle and swine is USAMMv3. This version is capable of simulating shipments at the level of individual premises (including farms, feedlots and markets) and includes shipment size predictions; corrections for overdispersion of movements; seasonality effects; and expanding inference to multiple years.

USAMM predictions have been validated in a number of ways including tests of out-of-sample prediction using independent datasets for both inter- and intra-state shipments. The multiple versions of USAMM have been through the peer-review process via academic publications as well as a model-review process by the USDA. 

The need for a model such as USAMM arises from the fact that there is no comprehensive database of livestock shipments in the U.S., and the data that exists is patch and difficult to access. USAMM was initially developed with livestock epidemiological modeling in mind, but the predictions made by the model in the form of simulated shipment networks are suitable for any purpose where detailed shipment patterns are needed - for instance in models related to agricultural economics. In the context of infectious livestock disease, we envision that USAMM can be used when addressing a number of important issues that requires a good understanding of the livestock movements in the United States such as:
- Informing prioritization for tracebacks
- Informing surveillance
- Risk assessment and identification
- Informing consequence estimates (biological and economic)
- Evaluation of control options
- Assessing impact of policy decisions on regulatory diseases
- Scenario generation
- Informing livestock movement for livestock disease models



# Visualization Tools
Visualizations of the USAMM outputs are available either through the USAMM Shiny App, or as raw network data in text format. 

The USAMM visualization tool lets you explore an interactive map showing predictions of USAMMv1 Cattle, USAMMv3 Cattle and USAMMv3 Swine models in a convenient way online. Users choose either a county or state of interest and can explore incoming or outgoing shipments. A downloadable summary table provides summarized predictions of the mean number of shipments and range between the focal county/state and those that it ships to or from. The tool was developed using the Shiny package app in R.

<a href="https://hdl.handle.net/10217/194169" class="btn btn-primary">USAMM Cattle v1 Network Realizations</a>

<a href="https://hdl.handle.net/10217/234115" class="btn btn-primary">USAMM Cattle v3 Network Realizations</a>

<a href="https://hdl.handle.net/10217/235130" class="btn btn-primary">USAMM Swine Network Realizations</a>

<a href="https://usamm-gen-net.shinyapps.io/usamm-gen-net/" class="btn btn-primary">USAMM Cattle v1 Shiny Visualization</a>

<a href="https://usamm-gen-net.shinyapps.io/v3ShinyApp_1000Nets/" class="btn btn-primary">USAMM Cattle v3 Shiny Visualization</a>

<a href="https://usamm-gen-net.shinyapps.io/SwineUSAMMShiny/" class="btn btn-primary">USAMM Swine Shiny Visualization</a>
