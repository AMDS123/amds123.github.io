---
layout: post
title: "No-reference Image Denoising Quality Assessment"
date: 2018-10-13 19:47:09
categories: arXiv_CV
tags: arXiv_CV
author: Si Lu
mathjax: true
---

* content
{:toc}

##### Abstract
A wide variety of image denoising methods are available now. However, the performance of a denoising algorithm often depends on individual input noisy images as well as its parameter setting. In this paper, we present a no-reference image denoising quality assessment method that can be used to select for an input noisy image the right denoising algorithm with the optimal parameter setting. This is a challenging task as no ground truth is available. This paper presents a data-driven approach to learn to predict image denoising quality. Our method is based on the observation that while individual existing quality metrics and denoising models alone cannot robustly rank denoising results, they often complement each other. We accordingly design denoising quality features based on these existing metrics and models and then use Random Forests Regression to aggregate them into a more powerful unified metric. Our experiments on images with various types and levels of noise show that our no-reference denoising quality assessment method significantly outperforms the state-of-the-art quality metrics. This paper also provides a method that leverages our quality assessment method to automatically tune the parameter settings of a denoising algorithm for an input noisy image to produce an optimal denoising result.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.05919](https://arxiv.org/abs/1810.05919)

##### PDF
[https://arxiv.org/pdf/1810.05919](https://arxiv.org/pdf/1810.05919)

