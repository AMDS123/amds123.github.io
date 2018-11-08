---
layout: post
title: "Demystifying Neural Network Filter Pruning"
date: 2018-10-29 23:49:18
categories: arXiv_CV
tags: arXiv_CV CNN
author: Zhuwei Qin, Fuxun Yu, ChenChen Liu, Xiang Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Based on filter magnitude ranking (e.g. L1 norm), conventional filter pruning methods for Convolutional Neural Networks (CNNs) have been proved with great effectiveness in computation load reduction. Although effective, these methods are rarely analyzed in a perspective of filter functionality. In this work, we explore the filter pruning and the retraining through qualitative filter functionality interpretation. We find that the filter magnitude based method fails to eliminate the filters with repetitive functionality. And the retraining phase is actually used to reconstruct the remained filters for functionality compensation for the wrongly-pruned critical filters. With a proposed functionality-oriented pruning method, we further testify that, by precisely addressing the filter functionality redundancy, a CNN can be pruned without considerable accuracy drop, and the retraining phase is unnecessary.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.02639](http://arxiv.org/abs/1811.02639)

##### PDF
[http://arxiv.org/pdf/1811.02639](http://arxiv.org/pdf/1811.02639)

