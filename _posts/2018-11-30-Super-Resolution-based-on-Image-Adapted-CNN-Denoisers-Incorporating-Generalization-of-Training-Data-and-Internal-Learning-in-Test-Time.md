---
layout: post
title: "Super-Resolution based on Image-Adapted CNN Denoisers: Incorporating Generalization of Training Data and Internal Learning in Test Time"
date: 2018-11-30 16:15:19
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Optimization Deep_Learning
author: Tom Tirer, Raja Giryes
mathjax: true
---

* content
{:toc}

##### Abstract
While deep neural networks exhibit state-of-the-art results in the task of image super-resolution (SR) with a fixed known acquisition process (e.g., a bicubic downscaling kernel), they experience a huge performance loss when the real observation model mismatches the one used in training. Recently, two different techniques suggested to mitigate this deficiency, i.e., enjoy the advantages of deep learning without being restricted by the prior training. The first one follows the plug-and-play (P&amp;P) approach that solves general inverse problems (e.g., SR) by plugging Gaussian denoisers into model-based optimization schemes. The second builds on internal recurrence of information inside a single image, and trains a super-resolver network at test time on examples synthesized from the low-resolution image. Our work incorporates the two strategies, enjoying the impressive generalization capabilities of deep learning, captured by the first, and further improving it through internal learning at test time. First, we apply a recent P&amp;P strategy to SR. Then, we show how it may become image-adaptive in test time. This technique outperforms the above two strategies on popular datasets and gives better results than other state-of-the-art methods on real images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.12866](http://arxiv.org/abs/1811.12866)

##### PDF
[http://arxiv.org/pdf/1811.12866](http://arxiv.org/pdf/1811.12866)

