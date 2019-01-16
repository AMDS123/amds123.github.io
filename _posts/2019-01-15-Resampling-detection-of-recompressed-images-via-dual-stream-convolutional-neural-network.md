---
layout: post
title: "Resampling detection of recompressed images via dual-stream convolutional neural network"
date: 2019-01-15 02:15:26
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Deep_Learning Detection
author: Antao Zhou, Gang Cao, Xianglin Huang, Gege Song, Lifang Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Resampling detection plays an important role in identifying image tampering, such as image splicing. Currently, the resampling detection is still difficult in recompressed images, which are yielded by applying resampling and post-JPEG compression to primary JPEG images. Although low quality primary compression benefits the detection, it remains rather challenging due to the widespread use of middle/high quality compression in imaging devices. In this paper, we propose a novel deep learning approach to learn resampling features directly from the recompressed images. To this end, a noise extraction layer based on low-order high pass filters is deployed to yield the image noise residual domain, which is more beneficial to extract manipulation trail features. A dual-stream convolutional neural network (CNN) is presented to capture the resampling trails along different directions, where the horizontal and vertical streams are interleaved and concatenated. Lastly, the learned features are fed into Sigmoid/Softmax layer, which is used as a binary/multiple classifier for achieving the blind detection or parameter estimation of resampling operations, respectively. Extensive experimental results demonstrate that our proposed method could detect resampling effectively in recompressed images and outperform the state-of-the-art detectors.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.04637](https://arxiv.org/abs/1901.04637)

##### PDF
[https://arxiv.org/pdf/1901.04637](https://arxiv.org/pdf/1901.04637)

