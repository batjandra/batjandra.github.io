---
title: "On Graph Neural Network Ensembles for Large-Scale Molecular Property Prediction"
collection: publications
category: preprints
permalink: /publication/tgnv2
excerpt: 'We conducted experiments using graph neural network ensembles to predict molecular HOMO-LUMO gaps.'
date: 2021-01-01
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2106.15529'
---

In order to advance large-scale graph machine learning, the Open Graph Benchmark Large Scale Challenge (OGB-LSC) was proposed at the KDD Cup 2021. The PCQM4M-LSC dataset defines a molecular HOMO-LUMO property prediction task on about 3.8M graphs. In this short paper, we show our current work-in-progress solution which builds an ensemble of three graph neural networks models based on GIN, Bayesian Neural Networks and DiffPool. Our approach outperforms the provided baseline by 7.6%. Moreover, using uncertainty in our ensemble's prediction, we can identify molecules whose HOMO-LUMO gaps are harder to predict (with Pearson's correlation of 0.5181). We anticipate that this will facilitate active learning.