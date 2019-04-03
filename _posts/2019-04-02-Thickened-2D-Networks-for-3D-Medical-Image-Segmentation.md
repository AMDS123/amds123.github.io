---
layout: post
title: "Thickened 2D Networks for 3D Medical Image Segmentation"
date: 2019-04-02 00:08:51
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Prediction
author: Qihang Yu, Yingda Xia, Lingxi Xie, Elliot K. Fishman, Alan L. Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
There has been a debate in medical image segmentation on whether to use 2D or 3D networks, where both pipelines have advantages and disadvantages. This paper presents a novel approach which thickens the input of a 2D network, so that the model is expected to enjoy both the stability and efficiency of 2D networks as well as the ability of 3D networks in modeling volumetric contexts. A major information loss happens when a large number of 2D slices are fused at the first convolutional layer, resulting in a relatively weak ability of the network in distinguishing the difference among slices. To alleviate this drawback, we propose an effective framework which (i) postpones slice fusion and (ii) adds highway connections from the pre-fusion layer so that the prediction layer receives slice-sensitive auxiliary cues. Experiments on segmenting a few abdominal targets in particular blood vessels which require strong 3D contexts demonstrate the effectiveness of our approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.01150](http://arxiv.org/abs/1904.01150)

##### PDF
[http://arxiv.org/pdf/1904.01150](http://arxiv.org/pdf/1904.01150)

