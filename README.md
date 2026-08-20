# Time Series Econometrics: Empirical Applications in EViews

## Overview

This repository contains an empirical analysis of economic time series
developed using EViews. The project applies a range of time series
econometric methods to study economic growth, interest rates, and their
dynamic behavior.

The analysis is organized into two empirical applications.

## 1. European GDP Growth

The first application analyzes quarterly real GDP growth rates for
France, Finland, Italy, and Spain over the period 1977Q1--2019Q4.

The analysis includes:

- ARMA models for the individual dynamics of GDP growth.
- VAR models to examine dynamic interactions between economies.
- Granger causality tests.
- Impulse-response analysis.
- Markov-switching models to identify expansionary and recessionary
  regimes.
- Analysis of potential business-cycle leadership relationships.
- A comparison of the results across the two country pairs.
- An analysis of the Great Moderation period for Italy and Spain.

## 2. U.S. and U.K. Interest Rates

The second application examines U.S. and U.K. interest rates and their
term structure dynamics.

The analysis includes:

- Unit root and stationarity tests.
- Interest rate differentials.
- Implied devaluation measures based on forward rates.
- Johansen cointegration analysis.
- The Diebold--Li model of the yield curve.
- State-space representation and Kalman filter estimation.

## Repository Contents

### Report

`report/Time_Series_Econometrics_Empirical_Applications.pdf`

Contains the complete written analysis, including the methodology,
results, figures, and appendices.

### EViews Workfiles

`workfiles/european_gdp_time_series_analysis.wf1`

Contains the EViews objects used for the analysis of European GDP growth,
including the ARMA, VAR, Granger causality, Markov-switching, and Great
Moderation analyses.

`workfiles/us_uk_interest_rates_dynamic_analysis.wf1`

Contains the EViews objects used for the analysis of U.S. and U.K.
interest rates, including the term structure and Diebold--Li analysis.

## Software

- EViews

## Author

Agustina Giménez

2026
