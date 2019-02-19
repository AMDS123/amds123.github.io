---
layout: post
title: "LapEPI-Net: A Laplacian Pyramid EPI structure for Learning-based Dense Light Field Reconstruction"
date: 2019-02-17 08:28:31
categories: arXiv_CV
tags: arXiv_CV
author: Gaochang Wu, Yebin Liu, Lu Fang, Tianyou Chai
mathjax: true
---

* content
{:toc}

##### Abstract
For dense sampled light field (LF) reconstruction problem, existing approaches focus on a depth-free framework to achieve non-Lambertian performance. However, they trap in the trade-off "either aliasing or blurring" problem, i.e., pre-filtering the aliasing components (caused by the angular sparsity of the input LF) always leads to a blurry result. In this paper, we intend to solve this challenge by introducing an elaborately designed epipolar plane image (EPI) structure within a learning-based framework. Specifically, we start by analytically showing that decreasing the spatial scale of an EPI shows higher efficiency in addressing the aliasing problem than simply adopting pre-filtering. Accordingly, we design a Laplacian Pyramid EPI (LapEPI) structure that contains both low spatial scale EPI (for aliasing) and high-frequency residuals (for blurring) to solve the trade-off problem. We then propose a novel network architecture for the LapEPI structure, termed as LapEPI-net. To ensure the non-Lambertian performance, we adopt a transfer-learning strategy by first pre-training the network with natural images then fine-tuning it with unstructured LFs. Extensive experiments demonstrate the high performance and robustness of the proposed approach for tackling the aliasing-or-blurring problem as well as the non-Lambertian reconstruction.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.06221](http://arxiv.org/abs/1902.06221)

##### PDF
[http://arxiv.org/pdf/1902.06221](http://arxiv.org/pdf/1902.06221)

