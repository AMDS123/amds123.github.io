---
layout: post
title: "Deflecting 3D Adversarial Point Clouds Through Outlier-Guided Removal"
date: 2018-12-25 00:38:20
categories: arXiv_CV
tags: arXiv_CV Adversarial Classification
author: Hang Zhou, Kejiang Chen, Weiming Zhang, Han Fang, Wenbo Zhou, Nenghai Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks are vulnerable to adversarial examples, which poses a threat to their application in security sensitive systems. We propose simple random sampling (SRS) and statistical outlier removal (SOR) as defenses for 3D point cloud classification, where both methods remove points by estimating probability of points serving as adversarial points. Compared with ensemble adversarial training which is the state-of-the-art defending method, SOR has several advantages: better defense performance, randomization makes the network more robust to adversarial point clouds, no additional training or fine-tuning required, and few computations are needed by adding the points-removal layer. In particular, our experiments on ModelNet40 show that SOR is very effective as defense in practice. The strength of those defenses lies in their non-differentiable nature and inherent randomness, which makes it difficult for an adversary to circumvent the defenses. Our best defense eliminates 81.4% of strong white-box attacks by C&amp;W and l2 loss based attack methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.11017](http://arxiv.org/abs/1812.11017)

##### PDF
[http://arxiv.org/pdf/1812.11017](http://arxiv.org/pdf/1812.11017)

