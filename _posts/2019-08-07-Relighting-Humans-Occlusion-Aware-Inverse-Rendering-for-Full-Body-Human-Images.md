---
layout: post
title: "Relighting Humans: Occlusion-Aware Inverse Rendering for Full-Body Human Images"
date: 2019-08-07 16:35:27
categories: arXiv_CV
tags: arXiv_CV Face CNN Inference
author: Yoshihiro Kanamori, Yuki Endo
mathjax: true
---

* content
{:toc}

##### Abstract
Relighting of human images has various applications in image synthesis. For relighting, we must infer albedo, shape, and illumination from a human portrait. Previous techniques rely on human faces for this inference, based on spherical harmonics (SH) lighting. However, because they often ignore light occlusion, inferred shapes are biased and relit images are unnaturally bright particularly at hollowed regions such as armpits, crotches, or garment wrinkles. This paper introduces the first attempt to infer light occlusion in the SH formulation directly. Based on supervised learning using convolutional neural networks (CNNs), we infer not only an albedo map, illumination but also a light transport map that encodes occlusion as nine SH coefficients per pixel. The main difficulty in this inference is the lack of training datasets compared to unlimited variations of human portraits. Surprisingly, geometric information including occlusion can be inferred plausibly even with a small dataset of synthesized human figures, by carefully preparing the dataset so that the CNNs can exploit the data coherency. Our method accomplishes more realistic relighting than the occlusion-ignored formulation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.02714](http://arxiv.org/abs/1908.02714)

##### PDF
[http://arxiv.org/pdf/1908.02714](http://arxiv.org/pdf/1908.02714)

