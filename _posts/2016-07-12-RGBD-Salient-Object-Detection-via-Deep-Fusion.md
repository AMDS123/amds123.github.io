---
layout: post
title: "RGBD Salient Object Detection via Deep Fusion"
date: 2016-07-12 12:32:56
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Knowledge CNN Quantitative Detection
author: Liangqiong Qu, Shengfeng He, Jiawei Zhang, Jiandong Tian, Yandong Tang, Qingxiong Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Numerous efforts have been made to design different low level saliency cues for the RGBD saliency detection, such as color or depth contrast features, background and color compactness priors. However, how these saliency cues interact with each other and how to incorporate these low level saliency cues effectively to generate a master saliency map remain a challenging problem. In this paper, we design a new convolutional neural network (CNN) to fuse different low level saliency cues into hierarchical features for automatically detecting salient objects in RGBD images. In contrast to the existing works that directly feed raw image pixels to the CNN, the proposed method takes advantage of the knowledge in traditional saliency detection by adopting various meaningful and well-designed saliency feature vectors as input. This can guide the training of CNN towards detecting salient object more effectively due to the reduced learning ambiguity. We then integrate a Laplacian propagation framework with the learned CNN to extract a spatially consistent saliency map by exploiting the intrinsic structure of the input image. Extensive quantitative and qualitative experimental evaluations on three datasets demonstrate that the proposed method consistently outperforms state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1607.03333](https://arxiv.org/abs/1607.03333)

##### PDF
[https://arxiv.org/pdf/1607.03333](https://arxiv.org/pdf/1607.03333)

