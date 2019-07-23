---
layout: post
title: "Automatic detection of multiple pathologies in fundus photographs using spin-off learning"
date: 2019-07-22 17:48:27
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Transfer_Learning Deep_Learning Prediction Detection
author: Gwenol&#xe9; Quellec, Mathieu Lamard, Pierre-Henri Conze, Pascale Massin, B&#xe9;atrice Cochener
mathjax: true
---

* content
{:toc}

##### Abstract
In the last decades, large datasets of fundus photographs have been collected in diabetic retinopathy (DR) screening networks. Through deep learning, these datasets were used to train automatic detectors for DR and a few other frequent pathologies, with the goal to automate screening. One challenge limits the adoption of such systems so far: automatic detectors ignore rare conditions that ophthalmologists currently detect. To address this limitation, we propose a new machine learning (ML) framework, called spin-off learning, for the automatic detection of rare conditions. This framework extends convolutional neural networks (CNNs), trained for frequent conditions, with an unsupervised probabilistic model for rare condition detection. Spin-off learning is based on the observation that CNNs often perceive photographs containing the same anomalies as similar, even though these CNNs were trained to detect unrelated conditions. This observation was based on the t-SNE visualization tool, which we decided to include in our probabilistic model. Spin-off learning supports heatmap generation, so the detected anomalies can be highlighted in images for decision support. Experiments in a dataset of more than 160,000 screening examinations from the OPHDIAT screening network show that spin-off learning can detect 37 conditions, out of 41, with an area under the ROC curve (AUC) greater than 0.8 (average AUC: 0.938). In particular, spin-off learning significantly outperforms other candidate ML frameworks for detecting rare conditions: multitask learning, transfer learning and one-shot learning. We expect these richer predictions to trigger the adoption of automated eye pathology screening, which will revolutionize clinical practice in ophthalmology.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.09449](http://arxiv.org/abs/1907.09449)

##### PDF
[http://arxiv.org/pdf/1907.09449](http://arxiv.org/pdf/1907.09449)

