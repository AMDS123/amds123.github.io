---
layout: post
title: "Adaptive feature recombination and recalibration for semantic segmentation: application to brain tumor segmentation in MRI"
date: 2018-06-06 17:37:15
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Classification
author: S&#xe9;rgio Pereira, Victor Alves, Carlos A. Silva
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) have been successfully used for brain tumor segmentation, specifically, fully convolutional networks (FCNs). FCNs can segment a set of voxels at once, having a direct spatial correspondence between units in feature maps (FMs) at a given location and the corresponding classified voxels. In convolutional layers, FMs are merged to create new FMs, so, channel combination is crucial. However, not all FMs have the same relevance for a given class. Recently, in classification problems, Squeeze-and-Excitation (SE) blocks have been proposed to re-calibrate FMs as a whole, and suppress the less informative ones. However, this is not optimal in FCN due to the spatial correspondence between units and voxels. In this article, we propose feature recombination through linear expansion and compression to create more complex features for semantic segmentation. Additionally, we propose a segmentation SE (SegSE) block for feature recalibration that collects contextual information, while maintaining the spatial meaning. Finally, we evaluate the proposed methods in brain tumor segmentation, using publicly available data.

##### Abstract (translated by Google)
卷积神经网络（CNN）已成功用于脑肿瘤分割，特别是完全卷积网络（FCNs）。 FCN可以一次分割一组体素，在给定位置的特征映射（FM）中的单位与相应的分类体素之间具有直接的空间对应关系。在卷积层中，FM被合并以创建新的FM，因此，通道组合是至关重要的。但是，并不是所有的FM对于给定的类都具有相同的相关性。最近，在分类问题中，已提出挤压与激励（SE）块来重新校准整体FM，并抑制较少信息的FM。然而，由于单位和体素之间的空间对应关系，这在FCN中并不是最佳的。在本文中，我们通过线性扩展和压缩来提出特征重组，以便为​​语义分割创建更复杂的特征。此外，我们还提出了一个分割SE（SegSE）块，用于特征重新校准，收集上下文信息，同时保持空间含义。最后，我们使用公开可用的数据评估所提出的脑肿瘤分割方法。

##### URL
[http://arxiv.org/abs/1806.02318](http://arxiv.org/abs/1806.02318)

##### PDF
[http://arxiv.org/pdf/1806.02318](http://arxiv.org/pdf/1806.02318)

