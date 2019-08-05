---
layout: post
title: "Uncertainty Quantification in Computer-Aided Diagnosis: Make Your Model say 'I don't know' for Ambiguous Cases"
date: 2019-08-02 10:31:02
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Prediction
author: Max-Heinrich Laves, Sontje Ihler, Tobias Ortmaier
mathjax: true
---

* content
{:toc}

##### Abstract
We evaluate two different methods for the integration of prediction uncertainty into diagnostic image classifiers to increase patient safety in deep learning. In the first method, Monte Carlo sampling is applied with dropout at test time to get a posterior distribution of the class labels (Bayesian ResNet). The second method extends ResNet to a probabilistic approach by predicting the parameters of the posterior distribution and sampling the final result from it (Variational ResNet).The variance of the posterior is used as metric for uncertainty.Both methods are trained on a data set of optical coherence tomography scans showing four different retinal conditions. Our results shown that cases in which the classifier predicts incorrectly correlate with a higher uncertainty. Mean uncertainty of incorrectly diagnosed cases was between 4.6 and 8.1 times higher than mean uncertainty of correctly diagnosed cases. Modeling of the prediction uncertainty in computer-aided diagnosis with deep learning yields more reliable results and is anticipated to increase patient safety.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.00792](http://arxiv.org/abs/1908.00792)

##### PDF
[http://arxiv.org/pdf/1908.00792](http://arxiv.org/pdf/1908.00792)

