[![Awesome](images/awesome.svg)](https://github.com/sindresorhus/awesome)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-YES-green.svg)](https://github.com/EthicalML/awesome-production-machine-learning/graphs/commit-activity)
![GitHub](https://img.shields.io/badge/Languages-MULTI-blue.svg)
![GitHub](https://img.shields.io/badge/License-MIT-lightgrey.svg)
[![GitHub](https://img.shields.io/twitter/follow/station10_uk.svg?label=Follow)](https://twitter.com/station10_uk)

# awesome-marketing-machine-learning

A curated list of awesome machine learning libraries for marketing. Inspired by both
[awesome-production-machine-learning](https://github.com/EthicalML/awesome-production-machine-learning)
and
[awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning),
and powered by [Station 10](https://station10.co.uk/).

Note that some packages could fit into more than one section. This has been noted in the descriptions so be sure to Ctrl + F as well as exploring by
sections.

Want to contribute? Please raise a Pull Request or an issue. If you find this useful please drop a ⭐️. This helps motivate us and others to update and 
maintain the list.

All packages are Python based unless otherwise stated. We do however, welcome contributions from R Users!

# Main Content

## Media / Marketing Mix Models

* [pymc-marketing](https://github.com/pymc-labs/pymc-marketing) ![Github Stars](https://img.shields.io/github/stars/pymc-labs/pymc-marketing.svg?style=social)
Bayesian Media Mix, Adstock, Saturation Customer Lifetime Value & Churn models.
* [lightweight-mmm](https://github.com/google/lightweight_mmm) ![Github Stars](https://img.shields.io/github/stars/google/lightweight_mmm.svg?style=social)
Bayesian Media Mix Models by Google.
* [Robyn](https://github.com/facebookexperimental/Robyn) ![Github Stars](https://img.shields.io/github/stars/facebookexperimental/Robyn.svg?style=social)
(R) Bayesian Media Mix Models by Facebook.
* [mmm-stan](https://github.com/sibylhe/mmm_stan) ![Github Stars](https://img.shields.io/github/stars/sibylhe/mmm_stan.svg?style=social)
Multiplicative Media Media Mix Model.
* [mamimo](https://github.com/Garve/mamimo) ![Github Stars](https://img.shields.io/github/stars/Garve/mamimo.svg?style=social)
Small Media Mix Models designed to be used in conjunction with ML libraries (e.g. SKL)

## Churn / CLV

* [lifetimes](https://github.com/CamDavidsonPilon/lifetimes) ![Github Stars](https://img.shields.io/github/stars/CamDavidsonPilon/lifetimes.svg?style=social)
CLV and Churn modelling. Deprecated and incorporated into [pymc-marketing](https://github.com/pymc-labs/pymc-marketing).
* [lucius-ltv](https://github.com/plexagon/lucius-ltv) ![Github Stars](https://img.shields.io/github/stars/plexagon/lucius-ltv.svg?style=social)
CLV for subscriptions.

## Attribution

## Geo Experimentation

* [trimmed_match](https://github.com/google/trimmed_match) ![Github Stars](https://img.shields.io/github/stars/google/trimmed_match.svg?style=social)
Ad effectiveness through the design and analysis of randomized Geo Experiments by Google.
* [matched_markets](https://github.com/google/matched_markets) ![Github Stars](https://img.shields.io/github/stars/google/matched_markets.svg?style=social)
Time-Based regression matched markets approach for designing Geo Experiments by Google.
* [GeoLift](https://github.com/facebookincubator/GeoLift) ![Github Stars](https://img.shields.io/github/stars/facebookincubator/GeoLift.svg?style=social)
Geo Experimentation methodology based on Synthetic Control Methods used to measure lift of ad campaigns by Facebook.

## Time Series

* [prophet](https://github.com/facebook/prophet) ![Github Stars](https://img.shields.io/github/stars/facebook/prophet.svg?style=social)
Additive time series modelling by Facebook.
* [statsforecast](https://github.com/Nixtla/statsforecast) ![Github Stars](https://img.shields.io/github/stars/Nixtla/statsforecast.svg?style=social)
Lightning ⚡️ fast forecasting with statistical and econometric models.
* [sktime](https://github.com/sktime/sktime) ![Github Stars](https://img.shields.io/github/stars/sktime/sktime.svg?style=social)
A unified framework for ML with Time Eeries.
* [temporian](https://github.com/google/temporian) ![Github Stars](https://img.shields.io/github/stars/google/temporian.svg?style=social)
Temporian is an open-source Python library for preprocessing ⚡ and feature engineering 🛠 temporal data 📈 for machine learning applications 🤖.

## Causal Inference

* [CausalPy](https://github.com/pymc-labs/CausalPy) ![Github Stars](https://img.shields.io/github/stars/pymc-labs/CausalPy.svg?style=social)
Causal Inference & Synthetic Control. Supports fitting with `scikit-learn` and `PyMC` models.
* [CausalImpact](https://github.com/google/CausalImpact) ![Github Stars](https://img.shields.io/github/stars/google/CausalImpact.svg?style=social)
(R) Causal Inference using Bayesian structural time-series models by Google.
* [tfcausalimpact](https://github.com/WillianFuks/tfcausalimpact) ![Github Stars](https://img.shields.io/github/stars/WillianFuks/tfcausalimpact.svg?style=social)
Google's [CausalImpact](https://github.com/google/CausalImpact) Algorithm implemented on top of [TensorFlow Probability](https://github.com/tensorflow/probability).
* [dowhy](https://github.com/py-why/dowhy) ![Github Stars](https://img.shields.io/github/stars/py-why/dowhy.svg?style=social)
Causal Inference that supports explicit modeling and testing of causal assumptions.
* [causalml](https://github.com/uber/causalml) ![Github Stars](https://img.shields.io/github/stars/uber/causalml.svg?style=social)
Uplift modeling and causal inference with ML by Uber.
* [SyntheticControlMethods](https://github.com/OscarEngelbrektson/SyntheticControlMethods) ![Github Stars](https://img.shields.io/github/stars/OscarEngelbrektson/SyntheticControlMethods.svg?style=social) -
Causal inference using Synthetic Control.

## Econometrics

* [statsmodels](https://github.com/statsmodels/statsmodels) ![Github Stars](https://img.shields.io/github/stars/statsmodels/statsmodels.svg?style=social)
Statistical modeling including time series and econometrics.
* [EconML](https://github.com/py-why/EconML) ![Github Stars](https://img.shields.io/github/stars/py-why/EconML.svg?style=social)
AI, Econometrics and Causal Inference modelling.

## Synthetic Control

* [SparseSC](https://github.com/microsoft/SparseSC) ![Github Stars](https://img.shields.io/github/stars/microsoft/SparseSC.svg?style=social)
Sparse Synthetic Control Models in Python by Microsoft.
* [pysyncon](https://github.com/sdfordham/pysyncon) ![Github Stars](https://img.shields.io/github/stars/sdfordham/pysyncon.svg?style=social)
Multiple Synthetic Control implementations.

## APIs & Wrappers

