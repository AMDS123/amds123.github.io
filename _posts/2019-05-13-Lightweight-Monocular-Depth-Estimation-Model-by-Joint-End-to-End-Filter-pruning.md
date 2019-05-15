---
layout: post
title: "Lightweight Monocular Depth Estimation Model by Joint End-to-End Filter pruning"
date: 2019-05-13 18:01:01
categories: arXiv_CV
tags: arXiv_CV CNN Relation
author: Sara Elkerdawy, Hong Zhang, Nilanjan Ray
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) have emerged as the state-of-the-art in multiple vision tasks including depth estimation. However, memory and computing power requirements remain as challenges to be tackled in these models. Monocular depth estimation has significant use in robotics and virtual reality that requires deployment on low-end devices. Training a small model from scratch results in a significant drop in accuracy and it does not benefit from pre-trained large models. Motivated by the literature of model pruning, we propose a lightweight monocular depth model obtained from a large trained model. This is achieved by removing the least important features with a novel joint end-to-end filter pruning. We propose to learn a binary mask for each filter to decide whether to drop the filter or not. These masks are trained jointly to exploit relations between filters at different layers as well as redundancy within the same layer. We show that we can achieve around 5x compression rate with small drop in accuracy on the KITTI driving dataset. We also show that masking can improve accuracy over the baseline with fewer parameters, even without enforcing compression loss.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.05212](https://arxiv.org/abs/1905.05212)

##### PDF
[https://arxiv.org/pdf/1905.05212](https://arxiv.org/pdf/1905.05212)

