---
layout: post
title: "Transductive Zero-Shot Learning with Visual Structure Constraint"
date: 2019-01-06 16:43:07
categories: arXiv_CV
tags: arXiv_CV
author: Ziyu Wan, Dongdong Chen, Yan Li, Xingguang Yan, Junge Zhang, Yizhou Yu, Jing Liao
mathjax: true
---

* content
{:toc}

##### Abstract
Zero-shot Learning (ZSL) aims to recognize objects of the unseen classes, whose instances may not have been seen during training. It associates seen and unseen classes with the common semantic space and provides the visual features for each data instance. Most existing methods first learn a compatible projection function between the semantic space and the visual space based on the data of source seen classes, then directly apply it to target unseen classes. However, in real scenarios, the data distribution between the source and target domain might not match well, thus causing the well-known domain shift problem. Based on the observation that visual features of test instances can be separated into different clusters, we propose a visual structure constraint on class centers for transductive ZSL, to improve the generality of the projection function (i.e. alleviate the above domain shift problem). Specifically, two different strategies (symmetric Chamfer-distance and bipartite matching) are adopted to align the projected unseen semantic centers and visual cluster centers of test instances. Experiments on three widely used datasets demonstrate that the proposed visual structure constraint can bring substantial performance gain consistently and achieve state-of-the-art results.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.01570](http://arxiv.org/abs/1901.01570)

##### PDF
[http://arxiv.org/pdf/1901.01570](http://arxiv.org/pdf/1901.01570)

