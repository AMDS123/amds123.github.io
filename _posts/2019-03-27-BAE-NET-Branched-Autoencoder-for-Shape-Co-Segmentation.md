---
layout: post
title: "BAE-NET: Branched Autoencoder for Shape Co-Segmentation"
date: 2019-03-27 02:33:20
categories: arXiv_CV
tags: arXiv_CV Segmentation Weakly_Supervised CNN Represenation_Learning
author: Zhiqin Chen, Kangxue Yin, Matthew Fisher, Siddhartha Chaudhuri, Hao Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
We treat shape co-segmentation as a representation learning problem and introduce BAE-NET, a branched autoencoder network, for the task. The unsupervised BAE-NET is trained with all shapes in an input collection using a shape reconstruction loss, without ground-truth segmentations. Specifically, the network takes an input shape and encodes it using a convolutional neural network, whereas the decoder concatenates the resulting feature code with a point coordinate and outputs a value indicating whether the point is inside/outside the shape. Importantly, the decoder is branched: each branch learns a compact representation for one commonly recurring part of the shape collection, e.g., airplane wings. By complementing the shape reconstruction loss with a label loss, BAE-NET is easily tuned for one-shot learning. We show unsupervised, weakly supervised, and one-shot learning results by BAE-NET, demonstrating that using only a couple of exemplars, our network can generally outperform state-of-the-art supervised methods trained on hundreds of segmented shapes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.11228](http://arxiv.org/abs/1903.11228)

##### PDF
[http://arxiv.org/pdf/1903.11228](http://arxiv.org/pdf/1903.11228)

