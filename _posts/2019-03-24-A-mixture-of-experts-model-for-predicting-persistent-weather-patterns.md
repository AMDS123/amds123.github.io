---
layout: post
title: "A mixture of experts model for predicting persistent weather patterns"
date: 2019-03-24 16:17:07
categories: arXiv_AI
tags: arXiv_AI Prediction
author: Maria Perez-Ortiz, Pedro A. Gutierrez, Peter Tino, Carlos Casanova-Mateo, Sancho Salcedo-Sanz
mathjax: true
---

* content
{:toc}

##### Abstract
Weather and atmospheric patterns are often persistent. The simplest weather forecasting method is the so-called persistence model, which assumes that the future state of a system will be similar (or equal) to the present state. Machine learning (ML) models are widely used in different weather forecasting applications, but they need to be compared to the persistence model to analyse whether they provide a competitive solution to the problem at hand. In this paper, we devise a new model for predicting low-visibility in airports using the concepts of mixture of experts. Visibility level is coded as two different ordered categorical variables: cloud height and runway visual height. The underlying system in this application is stagnant approximately in 90% of the cases, and standard ML models fail to improve on the performance of the persistence model. Because of this, instead of trying to simply beat the persistence model using ML, we use this persistence as a baseline and learn an ordinal neural network model that refines its results by focusing on learning weather fluctuations. The results show that the proposal outperforms persistence and other ordinal autoregressive models, especially for longer time horizon predictions and for the runway visual height variable.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10012](http://arxiv.org/abs/1903.10012)

##### PDF
[http://arxiv.org/pdf/1903.10012](http://arxiv.org/pdf/1903.10012)

