---
layout: post
title: "A Spatial Mapping Algorithm with Applications in Deep Learning-Based Structure Classification"
date: 2018-02-07 17:18:33
categories: arXiv_CV
tags: arXiv_CV CNN Classification Deep_Learning Recognition
author: Thomas Corcoran, Rafael Zamora-Resendiz, Xinlian Liu, Silvia Crivelli
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Network (CNN)-based machine learning systems have made breakthroughs in feature extraction and image recognition tasks in two dimensions (2D). Although there is significant ongoing work to apply CNN technology to domains involving complex 3D data, the success of such efforts has been constrained, in part, by limitations in data representation techniques. Most current approaches rely upon low-resolution 3D models, strategic limitation of scope in the 3D space, or the application of lossy projection techniques to allow for the use of 2D CNNs. To address this issue, we present a mapping algorithm that converts 3D structures to 2D and 1D data grids by mapping a traversal of a 3D space-filling curve to the traversal of corresponding 2D and 1D curves. We explore the performance of 2D and 1D CNNs trained on data encoded with our method versus comparable volumetric CNNs operating upon raw 3D data from a popular benchmarking dataset. Our experiments demonstrate that both 2D and 1D representations of 3D data generated via our method preserve a significant proportion of the 3D data's features in forms learnable by CNNs. Furthermore, we demonstrate that our method of encoding 3D data into lower-dimensional representations allows for decreased CNN training time cost, increased original 3D model rendering resolutions, and supports increased numbers of data channels when compared to purely volumetric approaches. This demonstration is accomplished in the context of a structural biology classification task wherein we train 3D, 2D, and 1D CNNs on examples of two homologous branches within the Ras protein family. The essential contribution of this paper is the introduction of a dimensionality-reduction method that may ease the application of powerful deep learning tools to domains characterized by complex structural data.

##### Abstract (translated by Google)
基于卷积神经网络（CNN）的机器学习系统在二维（2D）特征提取和图像识别任务方面取得突破性进展。尽管将CNN技术应用于涉及复杂三维数据的领域的工作仍在进行中，但这种努力的成功部分受到数据表示技术的限制。大多数当前的方法依赖于低分辨率3D模型，3D空间中的范围的策略性限制，或者使用有损投影技术来允许使用2D CNN。为了解决这个问题，我们提出了一种映射算法，通过将3D空间填充曲线的遍历映射到对应的2D和1D曲线的遍历，将3D结构转换为2D和1D数据网格。我们研究了用我们的方法编码的数据训练的二维和一维CNNs的性能，以及从一个流行的基准测试数据集的原始三维数据上运行的可比较的体积CNN的性能。我们的实验证明，通过我们的方法生成的3D数据的2D和1D表示在CNN可以学习的形式中保留了3D数据的大部分特征。此外，我们证明，我们将3D数据编码为低维表示的方法允许减少CNN训练时间成本，增加原始3D模型渲染分辨率，并且与纯体积方法相比，支持增加的数据通道数量。这个演示是在结构生物学分类任务的背景下完成的，其中我们在Ras蛋白家族中的两个同源分支的例子上训练3D，2D和1D CNN。本文的重要贡献是引入了一种降维方法，可以减轻强大的深度学习工具在以复杂结构数据为特征的领域的应用。

##### URL
[https://arxiv.org/abs/1802.02532](https://arxiv.org/abs/1802.02532)

##### PDF
[https://arxiv.org/pdf/1802.02532](https://arxiv.org/pdf/1802.02532)

