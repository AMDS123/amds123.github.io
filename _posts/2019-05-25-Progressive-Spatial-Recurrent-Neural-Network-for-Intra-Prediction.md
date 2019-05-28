---
layout: post
title: "Progressive Spatial Recurrent Neural Network for Intra Prediction"
date: 2019-05-25 14:59:34
categories: arXiv_CV
tags: arXiv_CV RNN Prediction
author: Yueyu Hu, Wenhan Yang, Mading Li, Jiaying Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Intra prediction is an important component of modern video codecs, which is able to efficiently squeeze out the spatial redundancy in video frames. With preceding pixels as the context, traditional intra prediction schemes generate linear predictions based on several predefined directions (i.e. modes) for blocks to be encoded. However, these modes are relatively simple and their predictions may fail when facing blocks with complex textures, which leads to additional bits encoding the residue. In this paper, we design a Progressive Spatial Recurrent Neural Network (PS-RNN) that learns to conduct intra prediction. Specifically, our PS-RNN consists of three spatial recurrent units and progressively generates predictions by passing information along from preceding contents to blocks to be encoded. To make our network generate predictions considering both distortion and bit-rate, we propose to use Sum of Absolute Transformed Difference (SATD) as the loss function to train PS-RNN since SATD is able to measure rate-distortion cost of encoding a residue block. Moreover, our method supports variable-block-size for intra prediction, which is more practical in real coding conditions. The proposed intra prediction scheme achieves on average 2.5% bit-rate reduction on variable-block-size settings under the same reconstruction quality compared with HEVC.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.02232](http://arxiv.org/abs/1807.02232)

##### PDF
[http://arxiv.org/pdf/1807.02232](http://arxiv.org/pdf/1807.02232)

