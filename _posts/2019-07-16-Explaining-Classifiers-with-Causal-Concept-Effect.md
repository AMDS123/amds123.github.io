---
layout: post
title: "Explaining Classifiers with Causal Concept Effect"
date: 2019-07-16 17:47:43
categories: arXiv_CV
tags: arXiv_CV Embedding Inference Classification Prediction Relation
author: Yash Goyal, Uri Shalit, Been Kim
mathjax: true
---

* content
{:toc}

##### Abstract
How can we understand classification decisions made by deep neural nets? We propose answering this question by using ideas from causal inference. We define the ``Causal Concept Effect'' (CaCE) as the causal effect that the presence or absence of a concept has on the prediction of a given deep neural net. We then use this measure as a mean to understand what drives the network's prediction and what does not. Yet many existing interpretability methods rely solely on correlations, resulting in potentially misleading explanations. We show how CaCE can avoid such mistakes. In high-risk domains such as medicine, knowing the root cause of the prediction is crucial. If we knew that the network's prediction was caused by arbitrary concepts such as the lighting conditions in an X-ray room instead of medically meaningful concept, this would prevent us from disastrous deployment of such models. 
 Estimating CaCE is difficult in situations where we cannot easily simulate the do-operator. As a simple solution, we propose learning a generative model, specifically a Variational AutoEncoder (VAE) on image pixels or image embeddings extracted from the classifier to measure VAE-CaCE. We show that VAE-CaCE is able to correctly estimate the true causal effect as compared to other baselines in controlled settings with synthetic and semi-natural high dimensional images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.07165](http://arxiv.org/abs/1907.07165)

##### PDF
[http://arxiv.org/pdf/1907.07165](http://arxiv.org/pdf/1907.07165)

