---
layout: page
title: Power Grid Time Series Forecasting
description: Hybrid EMD-SARIMA predictive modeling on the Polish power system.
img: assets/img/immagine_rete_elettrica.png
importance: 4
category: Data Analysis
---
**Tools:** Python, EMD, SARIMA, FFT, Pandas
*Context: Co-authored Academic Project*

* Developed a comprehensive three-stage signal decoupling strategy to analyze the high-frequency electricity demand of the Polish national grid (2008-2016).
* Extracted the non-linear macroeconomic baseline using Empirical Mode Decomposition (EMD) and isolated deterministic anthropogenic routines via spectral analysis (FFT) and seasonal folding.
* Trained an algorithmically optimized SARIMA model strictly on the resulting stationary, zero-mean residuals. 
* **Result:** Achieved high predictive accuracy over a 15-day horizon with mathematically bounded and stable 95% confidence intervals, successfully preventing the divergence of forecast variance.
* Evaluated the model's physical limitations by stress-testing it against unmodeled exogenous shocks, such as the severe 2012 European cold wave and structural holiday shifts.

[📄 Read the full Paper](/assets/pdf/polish_power_system_DDA.pdf) %}
