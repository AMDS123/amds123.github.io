---
layout: post
title: "Listwise View Ranking for Image Cropping"
date: 2019-05-14 02:21:59
categories: arXiv_CV
tags: arXiv_CV
author: Weirui Lu, Xiaofen Xing, Bolun Cai, Xiangmin Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Rank-based Learning with deep neural network has been widely used for image cropping. However, the performance of ranking-based methods is often poor and this is mainly due to two reasons: 1) image cropping is a listwise ranking task rather than pairwise comparison; 2) the rescaling caused by pooling layer and the deformation in view generation damage the performance of composition learning. In this paper, we develop a novel model to overcome these problems. To address the first problem, we formulate the image cropping as a listwise ranking problem to find the best view composition. For the second problem, a refined view sampling (called RoIRefine) is proposed to extract refined feature maps for candidate view generation. Given a series of candidate views, the proposed model learns the Top-1 probability distribution of views and picks up the best one. By integrating refined sampling and listwise ranking, the proposed network called LVRN achieves the state-of-the-art performance both in accuracy and speed.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.05352](https://arxiv.org/abs/1905.05352)

##### PDF
[https://arxiv.org/pdf/1905.05352](https://arxiv.org/pdf/1905.05352)

