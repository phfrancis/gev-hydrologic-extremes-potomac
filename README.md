# Extreme Value Modeling of Hydrologic Block Maxima

## Overview

This repository contains my master's project in Mathematical Sciences at Clemson University.

The project analyzes annual maximum river discharge for the Potomac River at Little Falls (USGS 01646500) using a stationary block-maxima framework and generalized extreme value (GEV) modeling.

The goal is to estimate extreme flood magnitudes, compare tail assumptions, and evaluate finite-sample reliability of return-level inference.

## Methods

- Annual block maxima
- Generalized Extreme Value (GEV) modeling
- Gumbel model comparison
- Maximum likelihood estimation
- Likelihood ratio testing
- Profile-likelihood confidence intervals
- Mann-Kendall trend assessment
- Monte Carlo simulation
- Parametric GEV simulation
- Year-resampling robustness analysis

## Key Findings

- The GEV model was favored over the constrained Gumbel model.
- The fitted GEV model indicated heavier upper-tail behavior.
- Return-level uncertainty increased for longer return periods.
- Simulation results showed that estimation error was driven mainly by sampling variability.
- Longer records improved precision, but profile-likelihood intervals could undercover in moderate samples.

## Tools

- R
- R Markdown
- Extreme value modeling packages
- ggplot2

## Repository Structure

```text
report/
    potomac_analysis_report.pdf
    potomac_analysis_report.html

analysis/
    potomac_analysis_report.Rmd
```