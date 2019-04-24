---
layout: post
title: "Adaptive Transform Domain Image Super-resolution Via Orthogonally Regularized Deep Networks"
date: 2019-04-22 22:29:52
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN Inference Deep_Learning
author: Tiantong Guo, Hojjat S. Mousavi, Vishal Monga
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning methods, in particular, trained Convolutional Neural Networks (CNN) have recently been shown to produce compelling results for single image Super-Resolution (SR). Invariably, a CNN is learned to map the Low Resolution (LR) image to its corresponding High Resolution (HR) version in the spatial domain. We propose a novel network structure for learning the SR mapping function in an image transform domain, specifically the Discrete Cosine Transform (DCT). As the first contribution, we show that DCT can be integrated into the network structure as a Convolutional DCT (CDCT) layer. With the CDCT layer, we construct the DCT Deep SR (DCT-DSR) network. We further extend the DCT-DSR to allow the CDCT layer to become trainable (i.e., optimizable). Because this layer represents an image transform, we enforce pairwise orthogonality constraints and newly formulated complexity order constraints on the individual basis functions/filters. This Orthogonally Regularized Deep SR network (ORDSR) simplifies the SR task by taking advantage of image transform domain while adapting the design of transform basis to the training image set. Experimental results show ORDSR achieves state-of-the-art SR image quality with fewer parameters than most of the deep CNN methods. A particular success of ORDSR is in overcoming the artifacts introduced by bicubic interpolation. A key burden of deep SR has been identified as the requirement of generous training LR and HR image pairs; ORSDR exhibits a much more graceful degradation as training size is reduced with significant benefits in the regime of limited training. Analysis of memory and computation requirements confirms that ORDSR can allow for a more efficient network with faster inference.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.10082](http://arxiv.org/abs/1904.10082)

##### PDF
[http://arxiv.org/pdf/1904.10082](http://arxiv.org/pdf/1904.10082)

