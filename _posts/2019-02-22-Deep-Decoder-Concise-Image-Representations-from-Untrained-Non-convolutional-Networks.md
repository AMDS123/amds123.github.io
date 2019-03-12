---
layout: post
title: "Deep Decoder: Concise Image Representations from Untrained Non-convolutional Networks"
date: 2019-02-22 22:13:19
categories: arXiv_CV
tags: arXiv_CV Image_Caption CNN
author: Reinhard Heckel, Paul Hand
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks, in particular convolutional neural networks, have become highly effective tools for compressing images and solving inverse problems including denoising, inpainting, and reconstruction from few and noisy measurements. This success can be attributed in part to their ability to represent and generate natural images well. Contrary to classical tools such as wavelets, image-generating deep neural networks have a large number of parameters---typically a multiple of their output dimension---and need to be trained on large datasets. In this paper, we propose an untrained simple image model, called the deep decoder, which is a deep neural network that can generate natural images from very few weight parameters. The deep decoder has a simple architecture with no convolutions and fewer weight parameters than the output dimensionality. This underparameterization enables the deep decoder to compress images into a concise set of network weights, which we show is on par with wavelet-based thresholding. Further, underparameterization provides a barrier to overfitting, allowing the deep decoder to have state-of-the-art performance for denoising. The deep decoder is simple in the sense that each layer has an identical structure that consists of only one upsampling unit, pixel-wise linear combination of channels, ReLU activation, and channelwise normalization. This simplicity makes the network amenable to theoretical analysis, and it sheds light on the aspects of neural networks that enable them to form effective signal representations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.03982](http://arxiv.org/abs/1810.03982)

##### PDF
[http://arxiv.org/pdf/1810.03982](http://arxiv.org/pdf/1810.03982)

