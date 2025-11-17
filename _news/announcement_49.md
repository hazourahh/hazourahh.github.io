---
date: 2025-11-16 15:59:00-0400
inline: false
layout: post
title: Paper accepted at VLDB 2026
---

I am happy to announce that our research paper titled "Fault Lines: Benchmarking the Impact of Label Data Quality on ML Robustness and Fairness" has been accepted for publication at VLDB 2026.

Authors: David Jackson , Paul Groth , and Hazar Harmouch

***

### Abstract
Artificial intelligence systems depend critically on high-quality data, yet real-world datasets are often imperfect. Label noise, such as incorrect or biased labels, can lead to suboptimal model decisions. While label noise has garnered increasing attention, existing research primarily examines random noise, employs simpler models, or relies on limited evaluation criteria. To address this, we introduce FAULT LINES, a comprehensive, model-agnostic benchmark comprising 15 datasets systematically corrupted with diverse types of label noise, paired with an evaluation framework. This resource supports the evaluation of data cleaning pipelines and guides the design of models that are robust, in both performance and fairness, to label noise. We benchmark the robustness to label noise of 22 state-of-the-art classification models, including gradient boosting, transformers, and fairness-oriented models.
Our findings show that many models maintain strong performance under high random noise (e.g., up to 40\% noise leads to only a modest reduction in Robust GBDT performance). However, these models are significantly less robust to even small amounts of biased noise (<10\%), which can cause substantial performance drops (e.g., 7\% noise reduces ResNet’s AUC by 4.4\% on average) or maintain apparent stability at the expense of severe fairness degradation (e.g., MLP’s Predictive Parity difference increases by ~700\% under 30\% biased noise in the ACS Unemployment dataset). We investigate how different model architectures handle the impact of biased noise. Notably, transformer-based models appear more robust than boosting models when handling biased noise, though this advantage depends on tuning and comes with higher variance. Finally, we identify key factors for ML practitioners to mitigate the effects of label noise, including model selection, dataset analysis, and preprocessing.