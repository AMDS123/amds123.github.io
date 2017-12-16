---
layout: post
title: "Robust, Deep and Inductive Anomaly Detection"
date: 2017-07-30 08:47:45
categories: arXiv_CV
tags: arXiv_CV Detection
author: Raghavendra Chalapathy (University of Sydney and Capital Markets Cooperative Research Centre (CMCRC)), Aditya Krishna Menon (Data61/CSIRO and the Australian National University), Sanjay Chawla (Qatar Computing Research Institute (QCRI), HBKU)
mathjax: true
---

* content
{:toc}

##### Abstract
PCA is a classical statistical technique whose simplicity and maturity has seen it find widespread use as an anomaly detection technique. However, it is limited in this regard by being sensitive to gross perturbations of the input, and by seeking a linear subspace that captures normal behaviour. The first issue has been dealt with by robust PCA, a variant of PCA that explicitly allows for some data points to be arbitrarily corrupted, however, this does not resolve the second issue, and indeed introduces the new issue that one can no longer inductively find anomalies on a test set. This paper addresses both issues in a single model, the robust autoencoder. This method learns a nonlinear subspace that captures the majority of data points, while allowing for some data to have arbitrary corruption. The model is simple to train and leverages recent advances in the optimisation of deep neural networks. Experiments on a range of real-world datasets highlight the model's effectiveness.

##### Abstract (translated by Google)
PCA是一种经典的统计技术，其简单性和成熟性被广泛用作异常检测技术。然而，在这方面，由于对输入的总体干扰敏感，并且寻求一个捕捉正常行为的线性子空间，所以受到限制。第一个问题已经由稳健的PCA处理，PCA的变体明确允许一些数据点被任意地破坏，但是这不能解决第二个问题，并且确实引入了不能再通过归纳找到的新问题测试集上的异常。本文讨论了单一模型中的两个问题，即健壮的自动编码器。这种方法学习一个非线性子空间，捕获大部分数据点，同时允许一些数据有任意的腐败。该模型很容易训练和利用最近在深度神经网络优化方面的进展。对一系列实际数据集进行的实验突出了模型的有效性。

##### URL
[https://arxiv.org/abs/1704.06743](https://arxiv.org/abs/1704.06743)

##### PDF
[https://arxiv.org/pdf/1704.06743](https://arxiv.org/pdf/1704.06743)

