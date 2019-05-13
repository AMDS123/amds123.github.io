---
layout: post
title: "Two-layer Near-lossless HDR Coding with Backward Compatibility to JPEG"
date: 2019-05-09 09:12:41
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Hiroyuki Kobayashi, Osamu Watanabe, Hitoshi Kiya
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an efficient two-layer near-lossless coding method using an extended histogram packing technique with backward compatibility to the legacy JPEG standard. The JPEG XT, which is the international standard to compress HDR images, adopts a two-layer coding method for backward compatibility to the legacy JPEG standard. However, there are two problems with this two-layer coding method. One is that it does not exhibit better near-lossless performance than other methods for HDR image compression with single-layer structure. The other problem is that the determining the appropriate values of the coding parameters may be required for each input image to achieve good compression performance of near-lossless compression with the two-layer coding method of the JPEG XT. To solve these problems, we focus on a histogram-packing technique that takes into account the histogram sparseness of HDR images. We used zero-skip quantization, which is an extension of the histogram-packing technique proposed for lossless coding, for implementing the proposed near-lossless coding method. The experimental results indicate that the proposed method exhibits not only a better near-lossless compression performance than that of the two-layer coding method of the JPEG XT, but also there are no issue regarding the combination of parameter values without losing backward compatibility to the JPEG standard.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04129](http://arxiv.org/abs/1905.04129)

##### PDF
[http://arxiv.org/pdf/1905.04129](http://arxiv.org/pdf/1905.04129)

