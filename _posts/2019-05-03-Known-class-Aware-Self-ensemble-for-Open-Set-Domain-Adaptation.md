---
layout: post
title: "Known-class Aware Self-ensemble for Open Set Domain Adaptation"
date: 2019-05-03 08:25:03
categories: arXiv_CV
tags: arXiv_CV Recognition
author: Qing Lian, Wen Li, Lin Chen, Lixin Duan
mathjax: true
---

* content
{:toc}

##### Abstract
Existing domain adaptation methods generally assume different domains have the identical label space, which is quite restrict for real-world applications. In this paper, we focus on a more realistic and challenging case of open set domain adaptation. Particularly, in open set domain adaptation, we allow the classes from the source and target domains to be partially overlapped. In this case, the assumption of conventional distribution alignment does not hold anymore, due to the different label spaces in two domains. To tackle this challenge, we propose a new approach coined as Known-class Aware Self-Ensemble (KASE), which is built upon the recently developed self-ensemble model. In KASE, we first introduce a Known-class Aware Recognition (KAR) module to identify the known and unknown classes from the target domain, which is achieved by encouraging a low cross-entropy for known classes and a high entropy based on the source data from the unknown class. Then, we develop a Known-class Aware Adaptation (KAA) module to better adapt from the source domain to the target by reweighing the adaptation loss based on the likeliness to belong to known classes of unlabeled target samples as predicted by KAR. Extensive experiments on multiple benchmark datasets demonstrate the effectiveness of our approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.01068](http://arxiv.org/abs/1905.01068)

##### PDF
[http://arxiv.org/pdf/1905.01068](http://arxiv.org/pdf/1905.01068)

