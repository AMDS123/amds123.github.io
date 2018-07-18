---
layout: post
title: "Effective Use of Synthetic Data for Urban Scene Semantic Segmentation"
date: 2018-07-16 22:10:09
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Detection
author: Fatemeh Sadat Saleh, Mohammad Sadegh Aliakbarian, Mathieu Salzmann, Lars Petersson, Jose M. Alvarez
mathjax: true
---

* content
{:toc}

##### Abstract
Training a deep network to perform semantic segmentation requires large amounts of labeled data. To alleviate the manual effort of annotating real images, researchers have investigated the use of synthetic data, which can be labeled automatically. Unfortunately, a network trained on synthetic data performs relatively poorly on real images. While this can be addressed by domain adaptation, existing methods all require having access to real images during training. In this paper, we introduce a drastically different way to handle synthetic images that does not require seeing any real images at training time. Our approach builds on the observation that foreground and background classes are not affected in the same manner by the domain shift, and thus should be treated differently. In particular, the former should be handled in a detection-based manner to better account for the fact that, while their texture in synthetic images is not photo-realistic, their shape looks natural. Our experiments evidence the effectiveness of our approach on Cityscapes and CamVid with models trained on synthetic data only.

##### Abstract (translated by Google)
训练深度网络以执行语义分割需要大量标记数据。为了减轻注释真实图像的手动工作，研究人员研究了合成数据的使用，这些数据可以自动标记。不幸的是，在合成数据上训练的网络在真实图像上表现得相对较差。虽然这可以通过域适应来解决，但是现有方法都需要在训练期间访问真实图像。在本文中，我们介绍了一种截然不同的处理合成图像的方法，这种方法不需要在训练时看到任何真实的图像。我们的方法建立在前景和背景类不受域移动以相同方式影响的观察的基础上，因此应该区别对待。特别是，前者应该以基于检测的方式处理，以更好地解释这样的事实：虽然它们在合成图像中的纹理不是照片般逼真的，但它们的形状看起来很自然。我们的实验证明了我们的方法对Cityscapes和CamVid的有效性，仅对合成数据进行了训练。

##### URL
[http://arxiv.org/abs/1807.06132](http://arxiv.org/abs/1807.06132)

##### PDF
[http://arxiv.org/pdf/1807.06132](http://arxiv.org/pdf/1807.06132)

