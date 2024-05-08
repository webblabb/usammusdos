---
title: U.S. Disease Outbreak Simulation
keywords:
last_updated: May 7, 2024
tags:
summary: The U.S. Disease Outbreak Simulation model (USDOS) is a national scale model where premises-to-premises transmission occurs by two routes -- long range transmission due to movement of infected animals informed by USAMM or local due to aerosol, fenceline, or fomite transmission.
sidebar:
permalink: usdos.html
folder: usdos
---

# Disease Outbreak Simulation
USDOS is a national scale, premises-level simulation model for livestock disease outbreaks. It incorporates long range transmission, by default using USAMM predictions for transmission via shipment, and local transmission processes via a spatial transmission kernel. Default settings for the spatial transmission kernel are estimated for foot and mouth disease from data from the United Kingdom 2001 outbreak. USDOS also allows for the exploration of outbreak response actions. Default simulations use demographic information for the U.S. from the Farm Location and Animal Population simulator (Burdett et al. 2015). USDOS has been validated by comparison to other FMD model simulations for the UK 2001 FMD outbreak. USDOS has been through the peer-review process via academic publications as well as a model-review process by USDA.
We envision that USDOS can be used to address a number of important issues surrounding livestock disease outbreaks in the U.S. such as:
-	Informing preparedness planning for foreign animal diseases
-	Informing preparedness planning for endemic diseases
-	Evaluating response options
-	There is the potential to fit the model to data to inform responses in an actual outbreak

For more information about USDOS please see the published [literature](https://webblabb.github.io/usammusdos/literature).


# USDOS Code and Documentation
The model can be run to output single outbreaks or many outbreaks in batch formulation. USDOS runs on a laptop or on a high- performance computing system. Run times even on a laptop for a single outbreak are on the order of seconds to a few minutes (minutes for continental scale outbreaks). USDOS is available as a C++ executable with accompanying processing code and documentation linked below.


<a href="https://github.com/webblabb/usdos" class="btn btn-primary">USDOS Source Code</a>

<a href="literature/USDOSv2.1_UserManual.html" class="btn btn-primary">USDOS v2.1 User Manual (HTML)</a>

<a href="literature/main.pdf" class="btn btn-primary">USDOS Workflow Diagram</a>

| <img src = "images/usdos.jpg" style = "width:600px">  |

# Previous USDOS Versions

We strongly recommend working with the latest version of USDOS. Earlier versions of USDOS are unable to run the current versions of USAMM and are more likely to be incompatible with software.

<a href="https://github.com/webblabb/usdosr" class="btn btn-primary">USDOS R Package</a>

<a href="literature/USDOS_UserManual_Tsaoetal.pdf" class="btn btn-primary">USDOS User Manual (PDF)</a>

<a href="literature/USDOS_UserManual_Tsaoetal.html" class="btn btn-primary">USDOS User Manual (HTML)</a>
