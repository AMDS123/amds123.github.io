---
layout: post
title: "Visual Space Optimization for Zero-shot Learning"
date: 2019-06-30 06:44:24
categories: arXiv_CV
tags: arXiv_CV Embedding Optimization
author: Xinsheng Wang, Shanmin Pang, Jihua Zhu, Zhongyu Li, Zhiqiang Tian, Yaochen Li
mathjax: true
---

* content
{:toc}

##### Abstract
Zero-shot learning, which aims to recognize new categories that are not included in the training set, has gained popularity owing to its potential ability in the real-word applications. Zero-shot learning models rely on learning an embedding space, where both semantic descriptions of classes and visual features of instances can be embedded for nearest neighbor search. Recently, most of the existing works consider the visual space formulated by deep visual features as an ideal choice of the embedding space. However, the discrete distribution of instances in the visual space makes the data structure unremarkable. We argue that optimizing the visual space is crucial as it allows semantic vectors to be embedded into the visual space more effectively. In this work, we propose two strategies to accomplish this purpose. One is the visual prototype based method, which learns a visual prototype for each visual class, so that, in the visual space, a class can be represented by a prototype feature instead of a series of discrete visual features. The other is to optimize the visual feature structure in an intermediate embedding space, and in this method we successfully devise a multilayer perceptron framework based algorithm that is able to learn the common intermediate embedding space and meanwhile to make the visual data structure more distinctive. Through extensive experimental evaluation on four benchmark datasets, we demonstrate that optimizing visual space is beneficial for zero-shot learning. Besides, the proposed prototype based method achieves the new state-of-the-art performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.00330](http://arxiv.org/abs/1907.00330)

##### PDF
[http://arxiv.org/pdf/1907.00330](http://arxiv.org/pdf/1907.00330)

