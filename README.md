# Betelgeuse-NC
Public MCMC code and data analized during the study of the dimming of Betelgeuse in 2019/20

The code allows to get corner plots with optimal parameters. The uncertainty is taken as the difference between the 84th and 50th percentile as the upper limit, and the difference between the 50th and 16th percentile as the lower limit for all model parameters. If the posterior distributions follow normal (Gaussian) distributions then this equates to the 1σ uncertainty for each parameter.

# Installation Requirements

Most of the data analysis was performed using python 3.7.4. 

 Python packages included:
* numpy [v 1.15.1]
* matplotlib [v 2.2.3]
* corner [v 2.1.0] 
* emcee [v 3.0rc2] (ref.1)
  

[1] Foreman-Mackey, D., Hogg, D. W., Lang, D. & Goodman, J. emcee: The MCMC Hammer. Publications ASP 125, 306 (2013). 


# System requirements

Code was written and execuded on Ubuntu 18.04.4 LTS

# Installation

All python packages should be easily being installed via pip [https://pypi.org/project/pip/] e.g. pip install <package_name>


# Data 

All data to run the individual scripts should be within the respective /data/folders. 

# How to run 

Print in terminal

 python <name of script>.py
 
 
 
