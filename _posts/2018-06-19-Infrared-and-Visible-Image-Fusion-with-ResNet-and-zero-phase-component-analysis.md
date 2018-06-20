---
layout: post
title: "Infrared and Visible Image Fusion with ResNet and zero-phase component analysis"
date: 2018-06-19 09:15:54
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Hui Li, Xiao-Jun Wu
mathjax: true
---

* content
{:toc}

##### Abstract
In image fusion task, feature extraction and processing are keys for fusion algorithm. Not only traditional feature extraction methods, deep learning-based methods are also applied into image fusion field to extract features. However, most of them use deep features directly which without feature processing. And this will lead the fusion performance degradation in some cases. In this paper, a novel fusion framework which based on deep features and zero-phase component analysis(ZCA) is proposed. Firstly, the residual network(ResNet) is used to extract the deep features from source images. Then ZCA and l_1-norm are utilized to normalize the deep features and obtain initial weight maps. And the final weight maps are obtained by initial weight maps and soft-max operation. Finally, the fused image is reconstructed by weight maps and source images. Compare with the existing fusion methods, experimental results demonstrate that our algorithm achieves better performance in both objective assessment and visual quality. And the code of our fusion algorithm is available at https://github.com/exceptionLi/imagefusion_resnet50

##### Abstract (translated by Google)
在图像融合任务中，特征提取和处理是融合算法的关键。不仅将传统的特征提取方法和基于深度学习的方法应用到图像融合领域中来提取特征，但是，它们大多数都是直接使用深度特征而不进行特征处理。这在某些情况下会导致聚变性能下降。本文提出了一种基于深度特征和零相位分量分析（ZCA）的融合框架。首先，残差网络（ResNet）用于从源图像中提取深度特征。然后利用ZCA和l_1范数来归一化深度特征并获得初始权重图。最终的权重图通过初始权重图和软最大操作获得。最后，融合图像通过权重图和源图像重建。与现有的融合方法相比，实验结果表明我们的算法在客观评估和视觉质量方面均取得了较好的性能。我们的融合算法的代码可以在https://github.com/exceptionLi/imagefusion_resnet50上找到

##### URL
[http://arxiv.org/abs/1806.07119](http://arxiv.org/abs/1806.07119)

##### PDF
[http://arxiv.org/pdf/1806.07119](http://arxiv.org/pdf/1806.07119)

