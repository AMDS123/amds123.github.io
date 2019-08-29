---
layout: post
title: "A Coarse-to-Fine Multi-stream Hybrid Deraining Network for Single Image Deraining"
date: 2019-08-28 02:05:36
categories: arXiv_CV
tags: arXiv_CV
author: Yanyan Wei, Zhao Zhang, Haijun Zhang, Richang Hong, Meng Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Single image deraining task is still a very challenging task due to its ill-posed nature in reality. Recently, researchers have tried to fix this issue by training the CNN-based end-to-end models, but they still cannot extract the negative rain streaks from rainy images precisely, which usually leads to an over de-rained or under de-rained result. To handle this issue, this paper proposes a new coarse-to-fine single image deraining framework termed Multi-stream Hybrid Deraining Network (shortly, MH-DerainNet). To obtain the negative rain streaks during training process more accurately, we present a new module named dual path residual dense block, i.e., Residual path and Dense path. The Residual path is used to reuse com-mon features from the previous layers while the Dense path can explore new features. In addition, to concatenate different scaled features, we also apply the idea of multi-stream with shortcuts between cascaded dual path residual dense block based streams. To obtain more distinct derained images, we combine the SSIM loss and perceptual loss to preserve the per-pixel similarity as well as preserving the global structures so that the deraining result is more accurate. Extensive experi-ments on both synthetic and real rainy images demonstrate that our MH-DerainNet can deliver significant improvements over several recent state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.10521](http://arxiv.org/abs/1908.10521)

##### PDF
[http://arxiv.org/pdf/1908.10521](http://arxiv.org/pdf/1908.10521)

