---
layout: post
title: "Visualizing and Improving Scattering Networks"
date: 2017-09-05 12:41:05
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification Recognition
author: Fergal Cotter, Nick Kingsbury
mathjax: true
---

* content
{:toc}

##### Abstract
Scattering Transforms (or ScatterNets) introduced by Mallat are a promising start into creating a well-defined feature extractor to use for pattern recognition and image classification tasks. They are of particular interest due to their architectural similarity to Convolutional Neural Networks (CNNs), while requiring no parameter learning and still performing very well (particularly in constrained classification tasks). In this paper we visualize what the deeper layers of a ScatterNet are sensitive to using a 'DeScatterNet'. We show that the higher orders of ScatterNets are sensitive to complex, edge-like patterns (checker-boards and rippled edges). These complex patterns may be useful for texture classification, but are quite dissimilar from the patterns visualized in second and third layers of Convolutional Neural Networks (CNNs) - the current state of the art Image Classifiers. We propose that this may be the source of the current gaps in performance between ScatterNets and CNNs (83% vs 93% on CIFAR-10 for ScatterNet+SVM vs ResNet). We then use these visualization tools to propose possible enhancements to the ScatterNet design, which show they have the power to extract features more closely resembling CNNs, while still being well-defined and having the invariance properties fundamental to ScatterNets.

##### Abstract (translated by Google)
由Mallat引入的散射变换（或ScatterNets）是创建定义良好的特征提取器以用于模式识别和图像分类任务的有前途的开始。由于其与卷积神经网络（CNN）的结构相似性，它们是特别感兴趣的，同时不需要参数学习，并且仍然表现良好（特别是在约束分类任务中）。在本文中，我们可以看到ScatterNet的深层对于使用“DeScatterNet”是敏感的。我们表明，ScatterNets的高阶对复杂的边缘状图案（棋盘和波纹边缘）敏感。这些复杂的模式可能对纹理分类有用，但与卷积神经网络（CNN）的第二层和第三层中可视化的模式（当前最先进的图像分类器）的模式完全不同。我们认为这可能是目前ScatterNet和CNN之间性能差距的来源（ScatterNet + SVM vs ResNet在CIFAR-10上为83％vs 93％）。然后，我们使用这些可视化工具来提出对ScatterNet设计的可能的增强，这表明它们有能力提取更类似于CNN的特征，同时仍然是定义明确的并且具有ScatterNets的基本不变性质。

##### URL
[https://arxiv.org/abs/1709.01355](https://arxiv.org/abs/1709.01355)

##### PDF
[https://arxiv.org/pdf/1709.01355](https://arxiv.org/pdf/1709.01355)

