---
layout: post
title: "Learning Transferable Adversarial Examples via Ghost Networks"
date: 2018-12-09 02:11:03
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Yingwei Li, Song Bai, Yuyin Zhou, Cihang Xie, Zhishuai Zhang, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
The recent development of adversarial attack has proven that ensemble-based methods can perform black-box attack better than the traditional, non-ensemble ones. However, those methods generally suffer from high complexity. They require a family of diverse models, and ensembling them afterward, both of which are computationally expensive. 
 In this paper, we propose Ghost Networks to efficiently learn transferable adversarial examples. The key principle of ghost networks is to perturb an existing model, which potentially generates a huge set of diverse models. Those models are subsequently fused by longitudinal ensemble. Both steps almost require no extra time and space consumption. 
 Extensive experimental results suggest that the number of networks is essential for improving the transferability of adversarial examples, but it is less necessary to independently train different networks and then ensemble them in an intensive aggregation way. Instead, our work can be a computationally cheap plug-in, which can be easily applied to improve adversarial approaches both in single-model attack and multi-model attack, compatible with both residual and non-residual networks. In particular, by re-producing the NIPS 2017 adversarial competition, our work outperforms the No.1 attack submission by a large margin, which demonstrates its effectiveness and efficiency.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.03413](http://arxiv.org/abs/1812.03413)

##### PDF
[http://arxiv.org/pdf/1812.03413](http://arxiv.org/pdf/1812.03413)

