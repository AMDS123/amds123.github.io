---
layout: post
title: "In-Place Activated BatchNorm for Memory-Optimized Training of DNNs"
date: 2017-12-07 13:43:45
categories: arXiv_CV
tags: arXiv_CV Segmentation Image_Classification Semantic_Segmentation Classification Deep_Learning
author: Samuel Rota Bul&#xf2;, Lorenzo Porzi, Peter Kontschieder
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we present In-Place Activated Batch Normalization (InPlace-ABN) - a novel approach to drastically reduce the training memory footprint of modern deep neural networks in a computationally efficient way. Our solution substitutes the conventionally used succession of BatchNorm + Activation layers with a single plugin layer, hence avoiding invasive framework surgery while providing straightforward applicability for existing deep learning frameworks. We obtain memory savings of up to 50% by dropping intermediate results and by recovering required information during the backward pass through the inversion of stored forward results, with only minor increase (0.8-2%) in computation time. Also, we demonstrate how frequently used checkpointing approaches can be made computationally as efficient as InPlace-ABN. In our experiments on image classification, we demonstrate on-par results on ImageNet-1k with state-of-the-art approaches. On the memory-demanding task of semantic segmentation, we report results for COCO-Stuff, Cityscapes and Mapillary Vistas, obtaining new state-of-the-art results on the latter without additional training data but in a single-scale and -model scenario. Code can be found at https://github.com/mapillary/inplace_abn.

##### Abstract (translated by Google)
在这项工作中，我们提出了就地激活批量标准化（InPlace-ABN） - 一种新的方法，以计算有效的方式大幅度减少现代深度神经网络的训练记忆足迹。我们的解决方案将常规使用的BatchNorm + Activation图层替换为单个插件层，从而避免了侵入式框架手术，同时为现有的深度学习框架提供了直接的适用性。我们通过丢弃中间结果和在向后通过存储的正向结果反演期间恢复所需的信息而获得高达50％的存储器节省，计算时间仅略微增加（0.8-2％）。此外，我们还演示了频繁使用的检查点方法可以在计算上与InPlace-ABN一样高效。在我们的图像分类实验中，我们用最先进的方法演示了ImageNet-1k上的结果。在对语义分割的内存要求很高的任务中，我们报告COCO-Stuff，Cityscapes和Mapillary Vistas的结果，在没有额外的训练数据的情况下获得最新的最新结果，但是在单一尺度和模型场景下。代码可以在https://github.com/mapillary/inplace_abn找到。

##### URL
[http://arxiv.org/abs/1712.02616](http://arxiv.org/abs/1712.02616)

##### PDF
[http://arxiv.org/pdf/1712.02616](http://arxiv.org/pdf/1712.02616)

