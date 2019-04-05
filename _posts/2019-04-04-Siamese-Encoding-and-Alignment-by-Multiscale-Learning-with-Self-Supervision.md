---
layout: post
title: "Siamese Encoding and Alignment by Multiscale Learning with Self-Supervision"
date: 2019-04-04 16:31:01
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Eric Mitchell, Stefan Keselj, Sergiy Popovych, Davit Buniatyan, H. Sebastian Seung
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a method of aligning a source image to a target image, where the transform is specified by a dense vector field. The two images are encoded as feature hierarchies by siamese convolutional nets. Then a hierarchy of aligner modules computes the transform in a coarse-to-fine recursion. Each module receives as input the transform that was computed by the module at the level above, aligns the source and target encodings at the same level of the hierarchy, and then computes an improved approximation to the transform using a convolutional net. The entire architecture of encoder and aligner nets is trained in a self-supervised manner to minimize the squared error between source and target remaining after alignment. We show that siamese encoding enables more accurate alignment than the image pyramids of SPyNet, a previous deep learning approach to coarse-to-fine alignment. Furthermore, self-supervision applies even without target values for the transform, unlike the strongly supervised SPyNet. We also show that our approach outperforms one-shot approaches to alignment, because the fine pathways in the latter approach may fail to contribute to alignment accuracy when displacements are large. As shown by previous one-shot approaches, good results from self-supervised learning require that the loss function additionally penalize non-smooth transforms. We demonstrate that "masking out" the penalty function near discontinuities leads to correct recovery of non-smooth transforms. Our claims are supported by empirical comparisons using images from serial section electron microscopy of brain tissue.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.02643](http://arxiv.org/abs/1904.02643)

##### PDF
[http://arxiv.org/pdf/1904.02643](http://arxiv.org/pdf/1904.02643)

