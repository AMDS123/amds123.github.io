---
layout: post
title: "Deep Image Smoothing based on Texture and Structure Guidance"
date: 2017-12-07 23:54:26
categories: arXiv_CV
tags: arXiv_CV Salient Deep_Learning Prediction
author: Kaiyue Lu, Shaodi You, Nick Barnes
mathjax: true
---

* content
{:toc}

##### Abstract
Image smoothing is a fundamental task in computer vision, which aims to retain salient structures and remove insignificant textures. In this paper, we tackle the natural deficiency of existing methods, that they cannot properly distinguish textures and structures with similar low-level appearance. While deep learning approaches have addressed preserving structures, they do not yet properly address textures. To this end, we build a texture prediction network (TPN) that learns from a various of natural textures. We then combine this with a structure prediction network (SPN) so that the final double-guided filtering network (DGFN) is informed where are the textures to remove ("texture-awareness") and where are the structures to preserve ("structure-awareness"). The proposed model is easy to implement and shows excellent performance on real images in the wild as well as our synthetic dataset.

##### Abstract (translated by Google)
图像平滑是计算机视觉中的一项基本任务，其目标是保留显着的结构并消除微不足道的纹理。在本文中，我们解决了现有方法的自然缺陷，即它们无法正确区分具有相似低级外观的纹理和结构。虽然深度学习方法已经解决了保存结构，但是它们还没有正确处理纹理。为此，我们建立了一个从各种自然纹理中学习的纹理预测网络（TPN）。然后，我们将其与结构预测网络（SPN）相结合，以便通知最终的双导滤波网络（DGFN）在哪里去除纹理（“纹理感知”）以及要保存的结构在哪里（“意识”）。所提出的模型易于实现，并且在野外的真实图像以及我们的综合数据集中表现出优异的性能。

##### URL
[http://arxiv.org/abs/1712.02893](http://arxiv.org/abs/1712.02893)

##### PDF
[http://arxiv.org/pdf/1712.02893](http://arxiv.org/pdf/1712.02893)

