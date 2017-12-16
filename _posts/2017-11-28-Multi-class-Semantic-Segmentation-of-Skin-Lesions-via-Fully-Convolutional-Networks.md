---
layout: post
title: "Multi-class Semantic Segmentation of Skin Lesions via Fully Convolutional Networks"
date: 2017-11-28 18:24:15
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Transfer_Learning Semantic_Segmentation Classification Deep_Learning Detection
author: Manu Goyal, Moi Hoon Yap
mathjax: true
---

* content
{:toc}

##### Abstract
Early detection of skin cancer, particularly melanoma, is crucial to enable advanced treatment. Due to the rapid growth of skin cancers, there is a growing need of computerized analysis for skin lesions. These processes including detection, classification, and segmentation. There are three main types of skin lesions in common that are benign nevi, melanoma, and seborrhoeic keratoses which have huge intra-class variations in terms of color, size, place and appearance for each class and high inter-class visual similarities in dermoscopic images. The majority of current research is focusing on melanoma segmentation, but it is also very important to segment the seborrhoeic keratoses and benign nevi lesions as these regions potentially indicate the pre-cancer stage. We propose a multiclass semantic segmentation for these three classes from publicly available ISBI-2017 challenge dataset which consists of 2750 dermoscopic images. We propose an end-to-end solution using fully convolutional networks (FCNs) for multi-class semantic segmentation, which will automatically segment the melanoma, keratoses and benign lesions. To overcome the issue of data deficiency, we propose a transfer learning approach which uses both partial transfer learning and full transfer learning to train FCNs for multi-class semantic segmentation of skin lesions. The results are presented in Dice Similarity Coefficient (Dice) to compare the performance of the deep learning segmentation methods on the dataset with 5-fold cross-validation. The results showed that the two-tier level transfer learning FCN-8s achieved the overall best result with Dice score of 0.785 in a benign category, 0.653 in melanoma segmentation, and 0.557 in seborrhoeic keratoses.

##### Abstract (translated by Google)
早期发现皮肤癌，特别是黑色素瘤，对于进行晚期治疗至关重要。由于皮肤癌的快速增长，皮肤病变的计算机化分析的需求日益增加。这些过程包括检测，分类和分割。常见的皮肤病变主要有三种，即良性痣，黑色素瘤和脂溢性角化病，每种类别在颜色，大小，位置和外观方面存在巨大的类内差异，皮肤镜像中的类间视觉相似性高。目前大部分的研究集中在黑色素瘤分割，但分割脂溢性角化病和良性痣病变也是非常重要的，因为这些区域可能表明癌前期阶段。我们提出了从公开可用的ISBI-2017挑战数据集（包含2750个dermoscopic图像）的这三个类的多类语义分割。我们提出了一个使用全卷积网络（FCNs）进行多类语义分割的端到端解决方案，可以自动分割黑色素瘤，角化病和良性病变。为了克服数据缺乏的问题，我们提出了一种转移学习的方法，它使用部分转移学习和全转移学习来训练FCN用于皮肤病变的多级语义分割。结果以Dice Similarity Coefficient（Dice）表示，以比较数据集上的深度学习分割方法的性能和5倍交叉验证。结果显示，双层转移学习FCN-8s获得总体最佳结果，良性组骰子评分为0.785，黑素瘤分割评分为0.653，脂溢性角化病评分为0.557。

##### URL
[https://arxiv.org/abs/1711.10449](https://arxiv.org/abs/1711.10449)

##### PDF
[https://arxiv.org/pdf/1711.10449](https://arxiv.org/pdf/1711.10449)

