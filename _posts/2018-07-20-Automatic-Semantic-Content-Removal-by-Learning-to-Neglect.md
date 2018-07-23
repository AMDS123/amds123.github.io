---
layout: post
title: "Automatic Semantic Content Removal by Learning to Neglect"
date: 2018-07-20 02:17:33
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation GAN
author: Siyang Qin, Jiahui Wei, Roberto Manduchi
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a new system for automatic image content removal and inpainting. Unlike traditional inpainting algorithms, which require advance knowledge of the region to be filled in, our system automatically detects the area to be removed and infilled. Region segmentation and inpainting are performed jointly in a single pass. In this way, potential segmentation errors are more naturally alleviated by the inpainting module. The system is implemented as an encoder-decoder architecture, with two decoder branches, one tasked with segmentation of the foreground region, the other with inpainting. The encoder and the two decoder branches are linked via neglect nodes, which guide the inpainting process in selecting which areas need reconstruction. The whole model is trained using a conditional GAN strategy. Comparative experiments show that our algorithm outperforms state-of-the-art inpainting techniques (which, unlike our system, do not segment the input image and thus must be aided by an external segmentation module.)

##### Abstract (translated by Google)
我们引入了一种新的自动图像内容删除和修复系统。与传统的修复算法不同，传统的修复算法需要提前了解要填充的区域，我们的系统会自动检测要移除和填充的区域。区域分割和修复在单次通过中共同执行。通过这种方式，修复模块可以更自然地减轻潜在的分割错误。该系统被实现为编码器 - 解码器架构，具有两个解码器分支，一个用于分割前景区域，另一个用于修复。编码器和两个解码器分支通过忽略节点链接，指导修复过程选择哪些区域需要重建。使用条件GAN策略训练整个模型。对比实验表明，我们的算法优于最先进的修复技术（与我们的系统不同，它不对输入图像进行分割，因此必须由外部分割模块辅助。）

##### URL
[http://arxiv.org/abs/1807.07696](http://arxiv.org/abs/1807.07696)

##### PDF
[http://arxiv.org/pdf/1807.07696](http://arxiv.org/pdf/1807.07696)

