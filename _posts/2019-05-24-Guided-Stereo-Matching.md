---
layout: post
title: "Guided Stereo Matching"
date: 2019-05-24 09:32:34
categories: arXiv_CV
tags: arXiv_CV Sparse Deep_Learning
author: Matteo Poggi, Davide Pallotti, Fabio Tosi, Stefano Mattoccia
mathjax: true
---

* content
{:toc}

##### Abstract
Stereo is a prominent technique to infer dense depth maps from images, and deep learning further pushed forward the state-of-the-art, making end-to-end architectures unrivaled when enough data is available for training. However, deep networks suffer from significant drops in accuracy when dealing with new environments. Therefore, in this paper, we introduce Guided Stereo Matching, a novel paradigm leveraging a small amount of sparse, yet reliable depth measurements retrieved from an external source enabling to ameliorate this weakness. The additional sparse cues required by our method can be obtained with any strategy (e.g., a LiDAR) and used to enhance features linked to corresponding disparity hypotheses. Our formulation is general and fully differentiable, thus enabling to exploit the additional sparse inputs in pre-trained deep stereo networks as well as for training a new instance from scratch. Extensive experiments on three standard datasets and two state-of-the-art deep architectures show that even with a small set of sparse input cues, i) the proposed paradigm enables significant improvements to pre-trained networks. Moreover, ii) training from scratch notably increases accuracy and robustness to domain shifts. Finally, iii) it is suited and effective even with traditional stereo algorithms such as SGM.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10107](http://arxiv.org/abs/1905.10107)

##### PDF
[http://arxiv.org/pdf/1905.10107](http://arxiv.org/pdf/1905.10107)

