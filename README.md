[![Build Status](https://travis-ci.org/anhoej/qicharts2.svg?branch=master)](https://travis-ci.org/anhoej/qicharts2)
[![CRAN_Status_Badge](http://www.r-pkg.org/badges/version/qicharts2)](https://cran.r-project.org/package=qicharts2)

# Quality improvement charts for R

`qicharts2` is an R package with functions for making run charts, Shewhart control charts and Pareto charts for continuous quality improvement. Included control charts are: I, MR, Xbar, S, T, C, U, U', P, P', and G charts. 

Non-random variation in the form of minor to moderate persistent shifts in data over time is identified by the Anhoej rules for unusually long runs and unusually few crossing.

Non-random variation in the form of larger, possibly transient, shifts is identified by Shewhart's 3-sigma rule.

## Exported functions

* `qic()` Run and control charts.

* `summary.qic()` Summary of qic object.

* `paretochart()` Pareto charts.

## Included datasets

* **hospital_infections** Number of hospital acquired bacteremia, Clostridium difficile infections, and urinary tract infections in six hospitals.

* **cabg** Individual coronary artery bypass graft operations.

* **cdi** Hospital acquired Clostridium difficile infections (CDI) before and after an intervention to reduce the risk of CDI.

* **nhs_accidents** Number of attendances to major accident and emergency hospital departments in the NHS that were seen within 4 hours of arrival over twenty weeks.

* **gtt** Adverse events during hospitalisation found by the Global Trigger Tool.

## Instructions

* Install stable version from CRAN: `install.packages('qicharts2')`.
  
  OR

* Install development version from github: `devtools::install_github('anhoej/qicharts2', build_vignettes = TRUE)`.

* Read documentation: `?qic`.

* Run examples: `example('qic')`, `example('paretochart')`.

* Read vignette: `vignette('qicharts2')`.

* Report issues and suggest improvements on https://github.com/anhoej/qicharts2.

* Website: https://anhoej.github.io/qicharts2/
