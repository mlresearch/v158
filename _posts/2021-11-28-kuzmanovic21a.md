---
title: 'Deconfounding Temporal Autoencoder: Estimating Treatment Effects over Time
  Using Noisy Proxies'
abstract: Estimating individualized treatment effects (ITEs) from observational data
  is crucial for decision-making. In order to obtain unbiased ITE estimates, a common
  assumption is that all confounders are observed. However, in practice, it is unlikely
  that we observe these confounders directly. Instead, we often observe noisy measurements
  of true confounders, which can serve as valid proxies. In this paper, we address
  the problem of estimating ITE in the longitudinal setting where we observe noisy
  proxies instead of true confounders. To this end, we develop the Deconfounding Temporal
  Autoencoder (DTA), a novel method that leverages observed noisy proxies to learn
  a hidden embedding that reflects the true hidden confounders. In particular, the
  DTA combines a long short-term memory autoencoder with a causal regularization penalty
  that renders the potential outcomes and treatment assignment conditionally independent
  given the learned hidden embedding. Once the hidden embedding is learned via DTA,
  state-of-the-art outcome models can be used to control for it and obtain unbiased
  estimates of ITE. Using synthetic and real-world medical data, we demonstrate the
  effectiveness of our DTA by improving over state-of-the-art benchmarks by a substantial
  margin.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: kuzmanovic21a
month: 0
tex_title: 'Deconfounding Temporal Autoencoder: Estimating Treatment Effects over
  Time Using Noisy Proxies'
firstpage: 143
lastpage: 155
page: 143-155
order: 143
cycles: false
bibtex_author: Kuzmanovic, Milan and Hatt, Tobias and Feuerriegel, Stefan
author:
- given: Milan
  family: Kuzmanovic
- given: Tobias
  family: Hatt
- given: Stefan
  family: Feuerriegel
date: 2021-11-28
address:
container-title: Proceedings of Machine Learning for Health
volume: '158'
genre: inproceedings
issued:
  date-parts:
  - 2021
  - 11
  - 28
pdf: https://proceedings.mlr.press/v158/kuzmanovic21a/kuzmanovic21a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
