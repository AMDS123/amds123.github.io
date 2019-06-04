---
layout: post
title: "Learning to Transfer: Unsupervised Meta Domain Translation"
date: 2019-06-01 08:24:26
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face Optimization
author: Jianxin Lin, Yijun Wang, Yingce Xia, Tianyu He, Zhibo Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised domain translation has recently achieved impressive performance with rapidly developed generative adversarial network (GAN) and availability of sufficient training data. However, existing domain translation frameworks form in a disposable way where the learning experiences are ignored. In this work, we take this research direction toward unsupervised meta domain translation problem. We propose a meta translation model called MT-GAN to find parameter initialization of a conditional GAN, which can quickly adapt for a new domain translation task with limited training samples. In the meta-training procedure, MT-GAN is explicitly fine-tuned with a primary translation task and a synthesized dual translation task. Then we design a meta-optimization objective to require the fine-tuned MT-GAN to produce good generalization performance. We demonstrate effectiveness of our model on ten diverse two-domain translation tasks and multiple face identity translation tasks. We show that our proposed approach significantly outperforms the existing domain translation methods when using no more than $10$ training samples in each image domain.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00181](http://arxiv.org/abs/1906.00181)

##### PDF
[http://arxiv.org/pdf/1906.00181](http://arxiv.org/pdf/1906.00181)

