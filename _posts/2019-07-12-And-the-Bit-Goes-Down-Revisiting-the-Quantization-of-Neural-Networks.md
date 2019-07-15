---
layout: post
title: "And the Bit Goes Down: Revisiting the Quantization of Neural Networks"
date: 2019-07-12 11:52:54
categories: arXiv_CV
tags: arXiv_CV CNN Inference Classification
author: Pierre Stock, Armand Joulin, R&#xe9;mi Gribonval, Benjamin Graham, Herv&#xe9; J&#xe9;gou
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the problem of reducing the memory footprint of ResNet-like convolutional network architectures. We introduce a vector quantization method that aims at preserving the quality of the reconstruction of the network outputs and not its weights. The advantage of our approach is that it minimizes the loss reconstruction error for in-domain inputs and does not require any labelled data. We also use byte-aligned codebooks to produce compressed networks with efficient inference on CPU. We validate our approach by quantizing a high performing ResNet-50 model to a memory size of 5 MB (20x compression factor) while preserving a top-1 accuracy of 76.1% on ImageNet object classification and by compressing a Mask R-CNN with a size budget around 6 MB.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05686](http://arxiv.org/abs/1907.05686)

##### PDF
[http://arxiv.org/pdf/1907.05686](http://arxiv.org/pdf/1907.05686)

