---
layout: post
title: "Image Inpainting for Irregular Holes Using Partial Convolutions"
date: 2018-12-15 22:22:34
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Quantitative
author: Guilin Liu, Fitsum A. Reda, Kevin J. Shih, Ting-Chun Wang, Andrew Tao, Bryan Catanzaro
mathjax: true
---

* content
{:toc}

##### Abstract
Existing deep learning based image inpainting methods use a standard convolutional network over the corrupted image, using convolutional filter responses conditioned on both valid pixels as well as the substitute values in the masked holes (typically the mean value). This often leads to artifacts such as color discrepancy and blurriness. Post-processing is usually used to reduce such artifacts, but are expensive and may fail. We propose the use of partial convolutions, where the convolution is masked and renormalized to be conditioned on only valid pixels. We further include a mechanism to automatically generate an updated mask for the next layer as part of the forward pass. Our model outperforms other methods for irregular masks. We show qualitative and quantitative comparisons with other methods to validate our approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.07723](http://arxiv.org/abs/1804.07723)

##### PDF
[http://arxiv.org/pdf/1804.07723](http://arxiv.org/pdf/1804.07723)

