---
layout: post
title: "From Big to Small: Multi-Scale Local Planar Guidance for Monocular Depth Estimation"
date: 2019-07-24 09:31:24
categories: arXiv_CV
tags: arXiv_CV CNN Prediction
author: Jin Han Lee, Myung-Kyu Han, Dong Wook Ko, Il Hong Suh
mathjax: true
---

* content
{:toc}

##### Abstract
Estimating accurate depth from a single image is challenging, because it is an ill-posed problem as infinitely many 3D scenes can be projected to the same 2D scene. However, recent works based on deep convolutional neural networks show great progress achieving plausible result. The networks are generally composed of two parts: an encoder for dense feature extraction and a decoder for predicting the desired depth. In the encoder-decoder schemes, repeated strided convolution and spatial pooling layers lower the spatial resolution of transitional outputs, and several techniques such as skip connections or multi-layer deconvolutional networks are adopted to effectively recover back to the original resolution. 
 In this paper, for a more effective guidance of densely encoded features to desired depth prediction, we propose a network architecture that utilizes novel local planar guidance layers located at multiple stages in decoding phase. We show that the proposed method outperforms the state-of-the-art works with significant margin evaluating on challenging benchmarks. We also provide results from an ablation study to validate the effectiveness of the proposed core factors.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.10326](http://arxiv.org/abs/1907.10326)

##### PDF
[http://arxiv.org/pdf/1907.10326](http://arxiv.org/pdf/1907.10326)

