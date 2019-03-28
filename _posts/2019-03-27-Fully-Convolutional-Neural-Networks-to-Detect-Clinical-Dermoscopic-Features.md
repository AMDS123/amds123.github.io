---
layout: post
title: "Fully Convolutional Neural Networks to Detect Clinical Dermoscopic Features"
date: 2019-03-27 03:04:08
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Classification Quantitative
author: Jeremy Kawahara, Ghassan Hamarneh
mathjax: true
---

* content
{:toc}

##### Abstract
The presence of certain clinical dermoscopic features within a skin lesion may indicate melanoma, and automatically detecting these features may lead to more quantitative and reproducible diagnoses. We reformulate the task of classifying clinical dermoscopic features within superpixels as a segmentation problem, and propose a fully convolutional neural network to detect clinical dermoscopic features from dermoscopy skin lesion images. Our neural network architecture uses interpolated feature maps from several intermediate network layers, and addresses imbalanced labels by minimizing a negative multi-label Dice-F$_1$ score, where the score is computed across the mini-batch for each label. Our approach ranked first place in the 2017 ISIC-ISBI Part 2: Dermoscopic Feature Classification Task challenge over both the provided validation and test datasets, achieving a 0.895% area under the receiver operator characteristic curve score. We show how simple baseline models can outrank state-of-the-art approaches when using the official metrics of the challenge, and propose to use a fuzzy Jaccard Index that ignores the empty set (i.e., masks devoid of positive pixels) when ranking models. Our results suggest that (i) the classification of clinical dermoscopic features can be effectively approached as a segmentation problem, and (ii) the current metrics used to rank models may not well capture the efficacy of the model. We plan to make our trained model and code publicly available.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1703.04559](http://arxiv.org/abs/1703.04559)

##### PDF
[http://arxiv.org/pdf/1703.04559](http://arxiv.org/pdf/1703.04559)

