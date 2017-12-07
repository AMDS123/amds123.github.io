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
为RGBD显着性检测设计了不同的低级显着性提示，如颜色或深度对比度特征，背景和颜色紧致度先验等。然而，这些显着线索如何相互作用，以及如何有效地结合这些低级显着性线索来生成主显着图仍然是一个具有挑战性的问题。在本文中，我们设计了一种新的卷积神经网络（CNN），将不同的低级显着性提示融合为分层特征，自动检测RGBD图像中的显着物体。与现有的直接将原始图像像素提供给CNN的作品相比，该方法利用了传统显着性检测的知识，采用了各种有意义的，设计良好的显着特征向量作为输入。由于减少了学习的模糊性，这可以指导CNN训练更有效地检测显着对象。然后，我们将拉普拉斯传播框架与学习的CNN相结合，通过利用输入图像的内在结构来提取空间一致的显着图。对三个数据集进行广泛的定量和定性实验评估表明，所提出的方法始终优于最先进的方法。

##### URL
[https://arxiv.org/abs/1607.03333](https://arxiv.org/abs/1607.03333)

##### PDF
[https://arxiv.org/pdf/1607.03333](https://arxiv.org/pdf/1607.03333)

