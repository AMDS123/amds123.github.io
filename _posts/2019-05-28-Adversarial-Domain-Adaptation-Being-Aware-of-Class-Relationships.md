---
layout: post
title: "Adversarial Domain Adaptation Being Aware of Class Relationships"
date: 2019-05-28 16:52:08
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial Transfer_Learning Relation
author: Zeya Wang, Baoyu Jing, Yang Ni, Nanqing Dong, Pengtao Xie, Eric P. Xing
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarial training is a useful approach to promote the learning of transferable representations across the source and target domains, which has been widely applied for domain adaptation (DA) tasks based on deep neural networks. Until very recently, existing adversarial domain adaptation (ADA) methods ignore the useful information from the label space, which is an important factor accountable for the complicated data distributions associated with different semantic classes. Especially, the inter-class semantic relationships have been rarely considered and discussed in the current work of transfer learning. In this paper, we propose a novel relationship-aware adversarial domain adaptation (RADA) algorithm, which first utilizes a single multi-class domain discriminator to enforce the learning of inter-class dependency structure during domain-adversarial training and then aligns this structure with the inter-class dependencies that are characterized from training the label predictor on the source domain. Specifically, we impose a regularization term to penalize the structure discrepancy between the inter-class dependencies respectively estimated from domain discriminator and label predictor. Through this alignment, our proposed method makes the ADA aware of class relationships. Empirical studies show that the incorporation of class relationships significantly improves the performance on benchmark datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11931](https://arxiv.org/abs/1905.11931)

##### PDF
[https://arxiv.org/pdf/1905.11931](https://arxiv.org/pdf/1905.11931)

