---
layout: post
title: "Semi-supervised Domain Adaptation via Minimax Entropy"
date: 2019-04-13 05:33:46
categories: arXiv_CV
tags: arXiv_CV Adversarial Classification
author: Kuniaki Saito, Donghyun Kim, Stan Sclaroff, Trevor Darrell, Kate Saenko
mathjax: true
---

* content
{:toc}

##### Abstract
Contemporary domain adaptation methods are very effective at aligning feature distributions of source and target domains without any target supervision. However, we show that these techniques perform poorly when even a few labeled examples are available in the target. To address this semi-supervised domain adaptation (SSDA) setting, we propose a novel Minimax Entropy (MME) approach that adversarially optimizes an adaptive few-shot model. Our base model consists of a feature encoding network, followed by a classification layer that computes the features' similarity to estimated prototypes (representatives of each class). Adaptation is achieved by alternately maximizing the conditional entropy of unlabeled target data with respect to the classifier and minimizing it with respect to the feature encoder. We empirically demonstrate the superiority of our method over many baselines, including conventional feature alignment and few-shot methods, setting a new state of the art for SSDA.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06487](http://arxiv.org/abs/1904.06487)

##### PDF
[http://arxiv.org/pdf/1904.06487](http://arxiv.org/pdf/1904.06487)

