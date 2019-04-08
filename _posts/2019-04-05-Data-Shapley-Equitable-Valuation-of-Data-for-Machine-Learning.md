---
layout: post
title: "Data Shapley: Equitable Valuation of Data for Machine Learning"
date: 2019-04-05 04:54:10
categories: arXiv_AI
tags: arXiv_AI Prediction
author: Amirata Ghorbani, James Zou
mathjax: true
---

* content
{:toc}

##### Abstract
As data becomes the fuel driving technological and economic growth, a fundamental challenge is how to quantify the value of data in algorithmic predictions and decisions. For example, in healthcare and consumer markets, it has been suggested that individuals should be compensated for the data that they generate, but it is not clear what is an equitable valuation for individual data. In this work, we develop a principled framework to address data valuation in the context of supervised machine learning. Given a learning algorithm trained on $n$ data points to produce a predictor, we propose data Shapley as a metric to quantify the value of each training datum to the predictor performance. Data Shapley uniquely satisfies several natural properties of equitable data valuation. We develop Monte Carlo and gradient-based methods to efficiently estimate data Shapley values in practical settings where complex learning algorithms, including neural networks, are trained on large datasets. In addition to being equitable, extensive experiments across biomedical, image and synthetic data demonstrate that data Shapley has several other benefits: 1) it is more powerful than the popular leave-one-out or leverage score in providing insight on what data is more valuable for a given learning task; 2) low Shapley value data effectively capture outliers and corruptions; 3) high Shapley value data inform what type of new data to acquire to improve the predictor.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.02868](https://arxiv.org/abs/1904.02868)

##### PDF
[https://arxiv.org/pdf/1904.02868](https://arxiv.org/pdf/1904.02868)

