---
layout: post
title: "Photorealistic Facial Texture Inference Using Deep Neural Networks"
date: 2016-12-02 00:14:12
categories: arXiv_CV
tags: arXiv_CV Face CNN Inference Relation
author: Shunsuke Saito, Lingyu Wei, Liwen Hu, Koki Nagano, Hao Li
mathjax: true
---

* content
{:toc}

##### Abstract
We present a data-driven inference method that can synthesize a photorealistic texture map of a complete 3D face model given a partial 2D view of a person in the wild. After an initial estimation of shape and low-frequency albedo, we compute a high-frequency partial texture map, without the shading component, of the visible face area. To extract the fine appearance details from this incomplete input, we introduce a multi-scale detail analysis technique based on mid-layer feature correlations extracted from a deep convolutional neural network. We demonstrate that fitting a convex combination of feature correlations from a high-resolution face database can yield a semantically plausible facial detail description of the entire face. A complete and photorealistic texture map can then be synthesized by iteratively optimizing for the reconstructed feature correlations. Using these high-resolution textures and a commercial rendering framework, we can produce high-fidelity 3D renderings that are visually comparable to those obtained with state-of-the-art multi-view face capture systems. We demonstrate successful face reconstructions from a wide range of low resolution input images, including those of historical figures. In addition to extensive evaluations, we validate the realism of our results using a crowdsourced user study.

##### Abstract (translated by Google)
我们提出了一个数据驱动的推理方法，可以合成一个完整的3D人脸模型的逼真的纹理图，给出了野外人的局部2D视图。在对形状和低频反照率进行初始估计之后，我们计算可见面部区域的高频部分纹理图，没有阴影部分。为了从这个不完整的输入中提取精细的外观细节，我们引入了一个基于深层卷积神经网络提取的中间层特征相关性的多尺度细节分析技术。我们证明，拟合来自高分辨率人脸数据库的特征相关的凸组合可以产生整个脸部的语义上合理的面部细节描述。然后可以通过迭代地对重建的特征相关性进行优化来合成完整且真实感的纹理图。使用这些高分辨率纹理和商业渲染框架，我们可以生成高保真度的3D渲染效果，这些效果在视觉上与使用最先进的多视图人脸捕捉系统获得的效果相媲美。我们展示来自各种低分辨率输入图像，包括历史人物的成功人脸重建。除了广泛的评估，我们使用众包的用户研究来验证我们的结果的真实性。

##### URL
[https://arxiv.org/abs/1612.00523](https://arxiv.org/abs/1612.00523)

##### PDF
[https://arxiv.org/pdf/1612.00523](https://arxiv.org/pdf/1612.00523)

