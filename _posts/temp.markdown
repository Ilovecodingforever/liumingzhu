---
layout: post
title:  "Deep Survival Models Can Improve Long-Term Mortality Risk Estimates from Chest Radiographs"
date:   2024-05-26
image: /images/chest.png
categories: others
author: "Mingzhu Liu"
venue: "MDPI Forecasting"
authors: "<strong>Mingzhu Liu</strong>, Chirag Nagpal, Artur Dubrawski"
# subtitle: "Dynamics based 3D skeletal hand tracking"
paper: https://www.mdpi.com/2571-9394/6/2/22
code: https://github.com/autonlab/Deep_Chest_Survival
---

Deep learning for survival analysis.

<blockquote>
  <p>
  Deep learning has recently demonstrated the ability to predict long-term patient risk and its stratification when trained on imaging data such as chest radiographs. However, existing methods formulate estimating patient risk as a binary classification, typically ignoring or limiting the use of temporal information, and not accounting for the loss of patient follow-up, which reduces the fidelity of estimation and limits the prediction to a certain time horizon. In this paper, we demonstrate that deep survival and time-to-event prediction models can outperform binary classifiers at predicting mortality and risk of adverse health events. In our study, deep survival models were trained to predict risk scores from chest radiographs and patient demographic information in the Prostate, Lung, Colorectal, and Ovarian (PLCO) cancer screening trial (25,433 patient data points used in this paper) for 2-, 5-, and 10-year time horizons. Binary classification models that predict mortality at these time horizons were built as baselines. Compared to the considered alternative, deep survival models improve the Brier score (5-year: 0.0455 [95% CI, 0.0427–0.0482] vs. 0.0555 [95% CI, (0.0535–0.0575)], p < 0.05) and expected calibration error (ECE) (5-year: 0.0110 [95% CI, 0.0080–0.0141] vs. 0.0747 [95% CI, 0.0718–0.0776], p < 0.05) for those fixed time horizons and are able to generate predictions for any time horizon, without the need to retrain the models. Our study suggests that deep survival analysis tools can outperform binary classification in terms of both discriminative performance and calibration, offering a potentially plausible solution for forecasting risk in clinical practice.
  </p>
</blockquote>
