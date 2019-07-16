---
layout: post
title: "Bayesian Synthesis of Probabilistic Programs for Automatic Data Modeling"
date: 2019-07-14 17:12:55
categories: arXiv_AI
tags: arXiv_AI Inference Prediction
author: Feras A. Saad, Marco F. Cusumano-Towner, Ulrich Schaechtle, Martin C. Rinard, Vikash K. Mansinghka
mathjax: true
---

* content
{:toc}

##### Abstract
We present new techniques for automatically constructing probabilistic programs for data analysis, interpretation, and prediction. These techniques work with probabilistic domain-specific data modeling languages that capture key properties of a broad class of data generating processes, using Bayesian inference to synthesize probabilistic programs in these modeling languages given observed data. We provide a precise formulation of Bayesian synthesis for automatic data modeling that identifies sufficient conditions for the resulting synthesis procedure to be sound. We also derive a general class of synthesis algorithms for domain-specific languages specified by probabilistic context-free grammars and establish the soundness of our approach for these languages. We apply the techniques to automatically synthesize probabilistic programs for time series data and multivariate tabular data. We show how to analyze the structure of the synthesized programs to compute, for key qualitative properties of interest, the probability that the underlying data generating process exhibits each of these properties. Second, we translate probabilistic programs in the domain-specific language into probabilistic programs in Venture, a general-purpose probabilistic programming system. The translated Venture programs are then executed to obtain predictions of new time series data and new multivariate data records. Experimental results show that our techniques can accurately infer qualitative structure in multiple real-world data sets and outperform standard data analysis methods in forecasting and predicting new data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.06249](http://arxiv.org/abs/1907.06249)

##### PDF
[http://arxiv.org/pdf/1907.06249](http://arxiv.org/pdf/1907.06249)

