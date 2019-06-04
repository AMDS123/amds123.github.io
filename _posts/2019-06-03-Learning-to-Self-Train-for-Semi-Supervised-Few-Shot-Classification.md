---
layout: post
title: "Learning to Self-Train for Semi-Supervised Few-Shot Classification"
date: 2019-06-03 04:09:32
categories: arXiv_CV
tags: arXiv_CV Optimization Classification Gradient_Descent
author: Qianru Sun, Xinzhe Li, Yaoyao Liu, Shibao Zheng, Tat-Seng Chua, Bernt Schiele
mathjax: true
---

* content
{:toc}

##### Abstract
Few-shot classification (FSC) is challenging due to the scarcity of labeled training data (e.g. only one labeled data point per class). Meta-learning has shown to achieve promising results by learning to initialize a classification model for FSC. In this paper we propose a novel semi-supervised meta-learning method called learning to self-train (LST) that leverages unlabeled data and specifically meta-learns how to cherry-pick and label such unsupervised data to further improve performance. To this end, we train the LST model through a large number of semi-supervised few-shot tasks. On each task, we train a few-shot model to predict pseudo labels for unlabeled data, and then iterate the self-training steps on labeled and pseudo-labeled data with each step followed by fine-tuning. We additionally learn a soft weighting network (SWN) to optimize the self-training weights of pseudo labels so that better ones can contribute more to gradient descent optimization. We evaluate our LST method on two ImageNet benchmarks for semi-supervised few-shot classification and achieve large improvements over the state-of-the-art.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00562](http://arxiv.org/abs/1906.00562)

##### PDF
[http://arxiv.org/pdf/1906.00562](http://arxiv.org/pdf/1906.00562)

