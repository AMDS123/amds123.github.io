---
layout: post
title: "P2SGrad: Refined Gradients for Optimizing Deep Face Models"
date: 2019-05-07 11:38:29
categories: arXiv_CV
tags: arXiv_CV Face Classification Recognition Face_Recognition
author: Xiao Zhang, Rui Zhao, Junjie Yan, Mengya Gao, Yu Qiao, Xiaogang Wang, Hongsheng Li
mathjax: true
---

* content
{:toc}

##### Abstract
Cosine-based softmax losses significantly improve the performance of deep face recognition networks. However, these losses always include sensitive hyper-parameters which can make training process unstable, and it is very tricky to set suitable hyper parameters for a specific dataset. This paper addresses this challenge by directly designing the gradients for adaptively training deep neural networks. We first investigate and unify previous cosine softmax losses by analyzing their gradients. This unified view inspires us to propose a novel gradient called P2SGrad (Probability-to-Similarity Gradient), which leverages a cosine similarity instead of classification probability to directly update the testing metrics for updating neural network parameters. P2SGrad is adaptive and hyper-parameter free, which makes the training process more efficient and faster. We evaluate our P2SGrad on three face recognition benchmarks, LFW, MegaFace, and IJB-C. The results show that P2SGrad is stable in training, robust to noise, and achieves state-of-the-art performance on all the three benchmarks.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.02479](https://arxiv.org/abs/1905.02479)

##### PDF
[https://arxiv.org/pdf/1905.02479](https://arxiv.org/pdf/1905.02479)

