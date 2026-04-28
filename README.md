# Extreme Value Modeling of Hydrologic Block Maxima

## Overview

This project applies extreme value theory (EVT) to analyze and model flood risk using annual maximum river discharge data from the Potomac River at Little Falls (USGS 01646500).

Using a 95-year record, the analysis employs a stationary block-maxima framework and generalized extreme value (GEV) modeling to estimate extreme flood magnitudes, compare tail behavior, and quantify uncertainty in return-level predictions.

**Key takeaway:** Extreme flood behavior exhibits heavy-tailed characteristics, and uncertainty increases substantially for longer return periods, highlighting challenges in predicting rare hydrologic events.

---

## 📄 Full Report

To view the complete analysis:

- **Recommended:**  
  👉 [Open the PDF report](report/potomac_analysis_report.pdf)

- **HTML version (better formatting):**  
  👉 [Download and open the HTML report](report/potomac_analysis_report.html)

> Note: GitHub cannot preview large HTML files directly. After downloading, open the file in your browser.

---

## Methods

- Annual block maxima extraction
- Generalized Extreme Value (GEV) modeling
- Gumbel (ξ = 0) model comparison
- Maximum likelihood estimation (MLE)
- Likelihood ratio testing (LRT)
- Profile-likelihood confidence intervals
- Mann–Kendall trend assessment
- Monte Carlo simulation study
- Parametric GEV simulation
- Year-resampling robustness analysis

---

## Key Findings

- The GEV model was favored over the constrained Gumbel model.
- The fitted GEV model indicated heavier upper-tail behavior.
- Return-level uncertainty increased with longer return periods.
- Simulation results showed that estimation error was primarily driven by sampling variability.
- Longer records improved precision, though profile-likelihood intervals could undercover in moderate samples.

---

## Tools & Techniques

- R  
- R Markdown  
- Extreme value modeling packages (e.g., `extRemes`, `ismev`)  
- ggplot2  

---

## Repository Structure

```text
report/
    potomac_analysis_report.pdf
    potomac_analysis_report.html

analysis/
    potomac_analysis_report.Rmd
```
