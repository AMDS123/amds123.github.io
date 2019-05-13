---
layout: post
title: "Kindling the Darkness: A Practical Low-light Image Enhancer"
date: 2019-05-04 11:05:20
categories: arXiv_CV
tags: arXiv_CV
author: Yonghua Zhang, Jiawan Zhang, Xiaojie Guo
mathjax: true
---

* content
{:toc}

##### Abstract
Images captured under low-light conditions often suffer from (partially) poor visibility. Besides unsatisfactory lightings, multiple types of degradations, such as noise and color distortion due to the limited quality of cameras, hide in the dark. In other words, solely turning up the brightness of dark regions will inevitably amplify hidden artifacts. This work builds a simple yet effective network for \textbf{Kin}dling the \textbf{D}arkness (denoted as KinD), which, inspired by Retinex theory, decomposes images into two components. One component (illumination) is responsible for light adjustment, while the other (reflectance) for degradation removal. In such a way, the original space is decoupled into two smaller subspaces, expecting to be better regularized/learned. It is worth to note that our network is trained with paired images shot under different exposure conditions, instead of using any ground-truth reflectance and illumination information. Extensive experiments are conducted to demonstrate the efficacy of our design and its superiority over state-of-the-art alternatives. Our KinD is robust against severe visual defects, and user-friendly to arbitrarily adjust light levels. In addition, our model spends less than 50ms to process an image in VGA resolution on a 2080Ti GPU. All the above merits make our KinD attractive for practical use.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04161](http://arxiv.org/abs/1905.04161)

##### PDF
[http://arxiv.org/pdf/1905.04161](http://arxiv.org/pdf/1905.04161)

