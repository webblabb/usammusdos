---
title: Run a Model
keywords:
last_updated: August 24, 2017
tags:
summary: Explore the features of the USAMM and USDOS models.
sidebar:
permalink: run.html
folder: pages
---

<a href="usamm.html" class="btn btn-primary">USAMM</a>

USAMM uses a Bayesian hierarchical modeling approach to estimate the number of shipments between any two counties in the contiguous U.S. together with associated uncertainty.  The underlying data include a 10% stratified sample of 2009 Interstate Certificates of Veterinary Inspection from 47 states together with multiple National Agricultural Statistics Survey covariates.  USAMM predictions have been validated in a number of ways including tests of out-of-sample prediction using independent datasets.  USAMM has been through the peer-review process via academic publications as well as a model-review process by USDA.

We envision that USAMM can be used to address a number of important issues surrounding livestock movement in the United States such as:

* Informing prioritization for tracebacks
* Informing surveillance
* Risk assessment and identification
* Informing consequence estimates (biological and economic)
* Evaluation of control options
* Assessing impact of policy decisions on regulatory diseases
* Scenario generation
* Informing livestock movement for livestock disease models


<a href="usdos.html" class="btn btn-primary">USDOS</a>

USDOS is a national scale, premises-level simulation model for fast-spreading disease outbreaks. USDOS incorporates long range transmission, by default using USAMM predictions for transmission via shipment, and local transmission processes via a spatial transmission kernel. Default settings for the spatial transmission kernel are estimated for foot and mouth disease from data from the United Kingdom 2001 outbreak. Control strategies that can also be investigated using USDOS include county- and state-level movement bans, infectious premises or dangerous contacts culling, multiple vaccination strategies and combined control actions. Default simulations use demographic information for the U.S. from the Farm Location and Animal Population simulator. USDOS has been validated by comparison to other FMD model simulations for the UK 2001 FMD outbreak.  USDOS has been through the peer-review process via academic publications as well as a model-review process by USDA.

We envision that USDOS can be used to address a number of important issues surrounding livestock disease outbreaks in the U.S. such as:

* Informing preparedness planning for foreign animal diseases
* Informing preparedness planning for endemic diseases
* Evaluating control options
* There is the potential to fit the model to data to inform responses in an actual outbreak
