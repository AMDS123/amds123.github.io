---
layout: post
title: "Burst ranking for blind multi-image deblurring"
date: 2018-10-29 13:38:54
categories: arXiv_CV
tags: arXiv_CV CNN
author: Fidel A. Guerrero Pe&#xf1;a, Pedro D. Marrero Fern&#xe1;ndez, Tsang Ing Ren, Jorge J. G. Leandro, Ricardo Nishihara
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new incremental aggregation algorithm for multi-image deblurring with automatic image selection. The primary motivation is that current bursts deblurring methods do not handle well situations in which misalignment or out-of-context frames are present in the burst. These real-life situations result in poor reconstructions or manual selection of the images that will be used to deblur. Automatically selecting best frames within the burst to improve the base reconstruction is challenging because the amount of possible images fusions is equal to the power set cardinal. Here, we approach the multi-image deblurring problem as a two steps process. First, we successfully learn a comparison function to rank a burst of images using a deep convolutional neural network. Then, an incremental Fourier burst accumulation with a reconstruction degradation mechanism is applied fusing only less blurred images that are sufficient to maximize the reconstruction quality. Experiments with the proposed algorithm have shown superior results when compared to other similar approaches, outperforming other methods described in the literature in previously described situations. We validate our findings on several synthetic and real datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.12121](http://arxiv.org/abs/1810.12121)

##### PDF
[http://arxiv.org/pdf/1810.12121](http://arxiv.org/pdf/1810.12121)

