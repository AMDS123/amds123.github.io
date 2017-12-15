---
layout: post
title: "Sparse Coding for Alpha Matting"
date: 2016-04-11 11:48:18
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Quantitative
author: Jubin Johnson, Ehsan Shahrian Varnousfaderani, Hisham Cholakkal, Deepu Rajan
mathjax: true
---

* content
{:toc}

##### Abstract
Existing color sampling based alpha matting methods use the compositing equation to estimate alpha at a pixel from pairs of foreground (F) and background (B) samples. The quality of the matte depends on the selected (F,B) pairs. In this paper, the matting problem is reinterpreted as a sparse coding of pixel features, wherein the sum of the codes gives the estimate of the alpha matte from a set of unpaired F and B samples. A non-parametric probabilistic segmentation provides a certainty measure on the pixel belonging to foreground or background, based on which a dictionary is formed for use in sparse coding. By removing the restriction to conform to (F,B) pairs, this method allows for better alpha estimation from multiple F and B samples. The same framework is extended to videos, where the requirement of temporal coherence is handled effectively. Here, the dictionary is formed by samples from multiple frames. A multi-frame graph model, as opposed to a single image as for image matting, is proposed that can be solved efficiently in closed form. Quantitative and qualitative evaluations on a benchmark dataset are provided to show that the proposed method outperforms current state-of-the-art in image and video matting.

##### Abstract (translated by Google)
基于现有的基于颜色采样的阿尔法消光方法使用合成方程来估计来自前景（F）和背景（B）样本对的像素处的阿尔法。遮罩的质量取决于所选的（F，B）对。在本文中，消光问题被重新解释为像素特征的稀疏编码，其中代码之和给出了来自一组不成对的F和B样本的alpha遮罩的估计。非参数概率分割提供了属于前景或背景的像素的确定性度量，基于该度量形成字典以用于稀疏编码。通过消除符合（F，B）对的限制，该方法允许从多个F和B样本更好的α估计。同样的框架被扩展到视频，其中时间相干性的要求被有效地处理。这里，字典是由来自多个帧的样本形成的。提出了一个多帧图模型，而不是单一的图像作为图像抠像，可以有效解决封闭的形式。提供基准数据集的定量和定性评估，以表明所提出的方法胜过当前的图像和视频抠图技术。

##### URL
[https://arxiv.org/abs/1604.02898](https://arxiv.org/abs/1604.02898)

##### PDF
[https://arxiv.org/pdf/1604.02898](https://arxiv.org/pdf/1604.02898)

