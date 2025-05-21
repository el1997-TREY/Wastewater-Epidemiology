**Wastewater Epidemiology: SARS-CoV-2 Case Estimation**

**Overview**
This project presents two end-to-end guided analyses in wastewater-based epidemiology, aiming to estimate SARS-CoV-2 (COVID-19) case counts from wastewater data in the city of Houston, Texas. The analyses utilize weekly viral load measurements from the Houston Health Department (HHD) and explore the relationship between virus levels in wastewater and reported syndromic cases.

**Objective**
To determine whether virus levels in wastewater can be used to estimate the number of COVID-19 cases (SARS-CoV-2) in the community.

**Dataset**
The analysis is based on the ww_sc2_ave.RDS file, a tibble containing the following variables:
	•	date: Week-ending Monday date
	•	sc2_cases: Number of syndromic COVID-19 cases reported by HHD
	•	ww_sc2: Citywide estimate of virus levels in wastewater (WW) for the week
	•	ww_lag1: One-week lag of ww_sc2
	•	ww_lag2: Two-week lag of ww_sc2

**Methods**
	•	Time series visualization
	•	Lag correlation analysis
	•	Predictive modeling using lagged wastewater indicators

**Output**
This project is structured as a reproducible analysis. It includes:
	•	A rendered .html or .pdf report (created using R Markdown or Quarto)
	•	Annotated code for data exploration, modeling, and interpretation

**Key Questions Explored**
	•	How strongly do virus levels in wastewater correlate with syndromic COVID-19 cases?
	•	Can lagged wastewater signals be used to anticipate case surges?

**Tools Used**
	•	R
	•	tidyverse (dplyr, ggplot2, tibble)
	•	lubridate
	•	readr
	•	R Markdown or Quarto
