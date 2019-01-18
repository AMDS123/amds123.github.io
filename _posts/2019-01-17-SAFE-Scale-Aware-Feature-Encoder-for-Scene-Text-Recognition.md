---
layout: post
title: "SAFE: Scale Aware Feature Encoder for Scene Text Recognition"
date: 2019-01-17 12:58:19
categories: arXiv_CV
tags: arXiv_CV Attention CNN Recognition
author: Wei Liu, Chaofeng Chen, Kwan-Yee K. Wong
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the problem of having characters with different scales in scene text recognition. We propose a novel scale aware feature encoder (SAFE) that is designed specifically for encoding characters with different scales. SAFE is composed of a multi-scale convolutional encoder and a scale attention network. The multi-scale convolutional encoder targets at extracting character features under multiple scales, and the scale attention network is responsible for selecting features from the most relevant scale(s). SAFE has two main advantages over the traditional single-CNN encoder used in current state-of-the-art text recognizers. First, it explicitly tackles the scale problem by extracting scale-invariant features from the characters. This allows the recognizer to put more effort in handling other challenges in scene text recognition, like those caused by view distortion and poor image quality. Second, it can transfer the learning of feature encoding across different character scales. This is particularly important when the training set has a very unbalanced distribution of character scales, as training with such a dataset will make the encoder biased towards extracting features from the predominant scale. To evaluate the effectiveness of SAFE, we design a simple text recognizer named scale-spatial attention network (S-SAN) that employs SAFE as its feature encoder, and carry out experiments on six public benchmarks. Experimental results demonstrate that S-SAN can achieve state-of-the-art (or, in some cases, extremely competitive) performance without any post-processing.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.05770](https://arxiv.org/abs/1901.05770)

##### PDF
[https://arxiv.org/pdf/1901.05770](https://arxiv.org/pdf/1901.05770)

