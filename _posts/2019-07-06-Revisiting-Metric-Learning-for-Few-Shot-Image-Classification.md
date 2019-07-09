---
layout: post
title: "Revisiting Metric Learning for Few-Shot Image Classification"
date: 2019-07-06 12:19:01
categories: arXiv_CV
tags: arXiv_CV Embedding Image_Classification Represenation_Learning Classification Relation
author: Xiaomeng Li, Lequan Yu, Chi-Wing Fu, Meng Fang, Pheng-Ann Heng
mathjax: true
---

* content
{:toc}

##### Abstract
The goal of few-shot learning is to recognize new visual concepts with just a few amount of labeled samples in each class. Recent effective metric-based few-shot approaches employ neural networks to learn a feature similarity comparison between query and support examples. However, the importance of feature embedding, i.e., exploring the relationship among training samples, is neglected. In this work, we present a simple yet powerful baseline for few-shot classification by emphasizing the importance of feature embedding. Specifically, we revisit the classical triplet network from deep metric learning, and extend it into a deep K-tuplet network for few-shot learning, utilizing the relationship among the input samples to learn a general representation learning via episode-training. Once trained, our network is able to extract discriminative features for unseen novel categories and can be seamlessly incorporated with a non-linear distance metric function to facilitate the few-shot classification. Our result on the miniImageNet benchmark outperforms other metric-based few-shot classification methods. More importantly, when evaluated on completely different datasets (Caltech-101, CUB-200, Stanford Dogs and Cars) using the model trained with miniImageNet, our method significantly outperforms prior methods, demonstrating its superior capability to generalize to unseen classes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.03123](http://arxiv.org/abs/1907.03123)

##### PDF
[http://arxiv.org/pdf/1907.03123](http://arxiv.org/pdf/1907.03123)

