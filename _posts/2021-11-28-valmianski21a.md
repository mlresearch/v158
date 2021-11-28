---
title: 'SmartTriage: A system for personalized patient data capture, documentation
  generation, and decision support'
abstract: 'Symptom checkers have emerged as an important tool for collecting symptoms
  and diagnosing patients, minimizing the involvement of clinical personnel. We developed
  a machine-learning-backed system, SmartTriage, which goes beyond conventional symptom
  checking through a tight bi-directional integration with the electronic medical
  record (EMR). Conditioned on EMR-derived patient history, our system identifies
  the patient’s chief complaint from a free-text entry and then asks a series of discrete
  questions to obtain relevant symptomatology. The patient-specific data are used
  to predict detailed ICD-10-CM codes as well as medication, laboratory, and imaging
  orders. Patient responses and clinical decision support (CDS) predictions are then
  inserted back into the EMR. To train the machine learning components of SmartTriage,
  we employed novel data sets of over 25 million primary care encounters and 1 million
  patient free-text reason-for-visit entries. These data sets were used to construct:
  (1) a long short-term memory (LSTM) based patient history representation, (2) a
  fine-tuned transformer model for chief complaint extraction, (3) a random forest
  model for question sequencing, and (4) a feed-forward network for CDS predictions.
  In total, our system supports 337 patient chief complaints, which together make
  up >90% of all primary care encounters at aiser Permanente.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: valmianski21a
month: 0
tex_title: 'SmartTriage: A system for personalized patient data capture, documentation
  generation, and decision support'
firstpage: 75
lastpage: 96
page: 75-96
order: 75
cycles: false
bibtex_author: Valmianski, Ilya and Frost, Nave and Sood, Navdeep and Wang, Yang and
  Liu, Baodong and Zhu, James J. and Karumuri, Sunil and Finn, Ian M. and Zisook,
  Daniel S.
author:
- given: Ilya
  family: Valmianski
- given: Nave
  family: Frost
- given: Navdeep
  family: Sood
- given: Yang
  family: Wang
- given: Baodong
  family: Liu
- given: James J.
  family: Zhu
- given: Sunil
  family: Karumuri
- given: Ian M.
  family: Finn
- given: Daniel S.
  family: Zisook
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
pdf: https://proceedings.mlr.press/v158/valmianski21a/valmianski21a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
