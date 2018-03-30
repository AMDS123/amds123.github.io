---
layout: post
title: "Context Encoding for Semantic Segmentation"
date: 2018-03-23 17:34:21
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Image_Classification Semantic_Segmentation Classification
author: Hang Zhang, Kristin Dana, Jianping Shi, Zhongyue Zhang, Xiaogang Wang, Ambrish Tyagi, Amit Agrawal
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work has made significant progress in improving spatial resolution for pixelwise labeling with Fully Convolutional Network (FCN) framework by employing Dilated/Atrous convolution, utilizing multi-scale features and refining boundaries. In this paper, we explore the impact of global contextual information in semantic segmentation by introducing the Context Encoding Module, which captures the semantic context of scenes and selectively highlights class-dependent featuremaps. The proposed Context Encoding Module significantly improves semantic segmentation results with only marginal extra computation cost over FCN. Our approach has achieved new state-of-the-art results 51.7% mIoU on PASCAL-Context, 85.9% mIoU on PASCAL VOC 2012. Our single model achieves a final score of 0.5567 on ADE20K test set, which surpass the winning entry of COCO-Place Challenge in 2017. In addition, we also explore how the Context Encoding Module can improve the feature representation of relatively shallow networks for the image classification on CIFAR-10 dataset. Our 14 layer network has achieved an error rate of 3.45%, which is comparable with state-of-the-art approaches with over 10 times more layers. The source code for the complete system are publicly available.

##### Abstract (translated by Google)
最近的工作已在改善基于像素标识的空间分辨率，采用扩张型/ Atrous卷积，利用多尺度特征和精炼边界完全卷积网络（FCN）框架显著的进展。在本文中，我们通过引入上下文编码模块来探索全局上下文信息在语义分割中的影响，该上下文编码模块捕获场景的语义上下文并选择性地突出显示与类相关的特征图。所提出的上下文编码模块显着改善了语义分割结果，并且在FCN上仅有边际额外计算成本。我们的方法在PASCAL-Context上获得了51.7％的最新成果，在PASCAL VOC 2012上获得了85.9％的mIoU。我们的单一模型在ADE20K测试集上获得了0.5567的最终成绩，超过了COCO的获奖作品此外，我们还探讨了上下文编码模块如何改进CIFAR-10数据集上图像分类的相对浅层网络的特征表示。我们的14层网络已经实现了3.45％的错误率，这与具有10倍以上层数的最先进方法相当。完整系统的源代码是公开可用的。

##### URL
[https://arxiv.org/abs/1803.08904](https://arxiv.org/abs/1803.08904)

##### PDF
[https://arxiv.org/pdf/1803.08904](https://arxiv.org/pdf/1803.08904)

