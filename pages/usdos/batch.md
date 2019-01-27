---
title: Running a large batch of simulations
keywords:
last_updated: March 8, 2018
tags:
summary:
sidebar: usdos_sidebar
permalink: batch.html
folder: usdos
---
USDOS can be run from a single configuration file or, more commonly, through batch runs. The pre-processing functions (see below) in the USDOS pipeline will create 100 config files for each county that is indicated in the function. They will also create the subsequent batch files and one job file that will run everything when used. More detail about these functions can be found in the [pipeline](usdos/pipeline) section. The following functions can be used depending on the type of control desired to create these configuration and batch files:    
 * configs_base()    
 * configs_cull()    
 * configs_vax()    
 * configs_sensitivity()    
 
