---
layout: post
title: "Learning Optimal Data Augmentation Policies via Bayesian Optimization for Image Classification Tasks"
date: 2019-05-06 15:49:02
categories: arXiv_CV
tags: arXiv_CV Speech_Recognition Image_Classification Optimization Classification Deep_Learning Recognition
author: Chunxu Zhang, Jiaxu Cui, Bo Yang
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, deep learning has achieved remarkable achievements in many fields, including computer vision, natural language processing, speech recognition and others. Adequate training data is the key to ensure the effectiveness of the deep models. However, obtaining valid data requires a lot of time and labor resources. Data augmentation (DA) is an effective alternative approach, which can generate new labeled data based on existing data using label-preserving transformations. Although we can benefit a lot from DA, designing appropriate DA policies requires a lot of expert experience and time consumption, and the evaluation of searching the optimal policies is costly. So we raise a new question in this paper: how to achieve automated data augmentation at as low cost as possible? We propose a method named BO-Aug for automating the process by finding the optimal DA policies using the Bayesian optimization approach. Our method can find the optimal policies at a relatively low search cost, and the searched policies based on a specific dataset are transferable across different neural network architectures or even different datasets. We validate the BO-Aug on three widely used image classification datasets, including CIFAR-10, CIFAR-100 and SVHN. Experimental results show that the proposed method can achieve state-of-the-art or near advanced classification accuracy. Code to reproduce our experiments is available at this https URL.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.02610](https://arxiv.org/abs/1905.02610)

##### PDF
[https://arxiv.org/pdf/1905.02610](https://arxiv.org/pdf/1905.02610)

