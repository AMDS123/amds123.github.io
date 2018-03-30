---
layout: post
title: "Learning to Look around Objects for Top-View Representations of Outdoor Scenes"
date: 2018-03-28 22:33:17
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation
author: Samuel Schulter, Menghua Zhai, Nathan Jacobs, Manmohan Chandraker
mathjax: true
---

* content
{:toc}

##### Abstract
Given a single RGB image of a complex outdoor road scene in the perspective view, we address the novel problem of estimating an occlusion-reasoned semantic scene layout in the top-view. This challenging problem not only requires an accurate understanding of both the 3D geometry and the semantics of the visible scene, but also of occluded areas. We propose a convolutional neural network that learns to predict occluded portions of the scene layout by looking around foreground objects like cars or pedestrians. But instead of hallucinating RGB values, we show that directly predicting the semantics and depths in the occluded areas enables a better transformation into the top-view. We further show that this initial top-view representation can be significantly enhanced by learning priors and rules about typical road layouts from simulated or, if available, map data. Crucially, training our model does not require costly or subjective human annotations for occluded areas or the top-view, but rather uses readily available annotations for standard semantic segmentation. We extensively evaluate and analyze our approach on the KITTI and Cityscapes data sets.

##### Abstract (translated by Google)
在透视图中给定一个复杂户外道路场景的单个RGB图像，我们解决了在顶视图中估计遮蔽理由的语义场景布局的新问题。这个具有挑战性的问题不仅需要准确理解3D几何和可见场景的语义，而且还需要了解遮挡区域的语义。我们提出了一个卷积神经网络，通过环顾诸如汽车或行人的前景物体来学习预测场景布局的遮挡部分。但我们不是幻觉RGB值，而是直接预测遮挡区域中的语义和深度，以便更好地转换为顶视图。我们进一步表明，通过从模拟或地图数据（如果有的话）学习关于典型道路布局的先验和规则，可以显着增强此初始顶视图表示。至关重要的是，训练我们的模型并不需要成本高昂的或主观的人为注解来遮挡区域或顶视图，而是使用现成的标注进行标准语义分割。我们广泛评估和分析我们在KITTI和Cityscapes数据集上的方法。

##### URL
[http://arxiv.org/abs/1803.10870](http://arxiv.org/abs/1803.10870)

##### PDF
[http://arxiv.org/pdf/1803.10870](http://arxiv.org/pdf/1803.10870)

