---
layout: post
title: "Deep Texture and Structure Aware Filtering Network for Image Smoothing"
date: 2018-05-08 00:51:15
categories: arXiv_CV
tags: arXiv_CV Salient Deep_Learning Prediction
author: Kaiyue Lu, Shaodi You, Nick Barnes
mathjax: true
---

* content
{:toc}

##### Abstract
Image smoothing is a fundamental task in computer vision, that aims to retain salient structures and remove insignificant textures. In this paper, we aim to address the fundamental shortcomings of existing image smoothing methods, which cannot properly distinguish textures and structures with similar low-level appearance. While deep learning approaches have started to explore the preservation of structure through image smoothing, existing work does not yet properly address textures. To this end, we generate a large dataset by blending natural textures with clean structure-only images, and then build a texture prediction network (TPN) that predicts the location and magnitude of textures. We then combine the TPN with a semantic structure prediction network (SPN) so that the final texture and structure aware filtering network (TSAFN) is able to identify the textures to remove ("texture-awareness") and the structures to preserve ("structure-awareness"). The proposed model is easy to understand and implement, and shows excellent performance on real images in the wild as well as our generated dataset.

##### Abstract (translated by Google)
图像平滑是计算机视觉中的一项基础任务，旨在保留显着的结构并消除微不足道的纹理。在本文中，我们旨在解决现有图像平滑方法的基本缺陷，这些方法无法正确区分具有类似低级外观的纹理和结构。尽管深度学习方法已经开始探索通过图像平滑保存结构，但现有的工作还没有正确处理纹理。为此，我们通过将自然纹理与干净的仅有结构的图像混合来生成大型数据集，然后构建预测纹理位置和大小的纹理预测网络（TPN）。然后，我们将TPN与语义结构预测网络（SPN）相结合，以便最终的纹理和结构感知过滤网络（TSAFN）能够识别要移除的纹理（“纹理感知”）和要保留的结构（“结构-意识”）。所提出的模型易于理解和实施，并且在野外以及我们生成的数据集中显示出真实图像的优异性能。

##### URL
[http://arxiv.org/abs/1712.02893](http://arxiv.org/abs/1712.02893)

##### PDF
[http://arxiv.org/pdf/1712.02893](http://arxiv.org/pdf/1712.02893)

