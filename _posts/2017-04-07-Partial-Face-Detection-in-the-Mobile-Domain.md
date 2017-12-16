---
layout: post
title: "Partial Face Detection in the Mobile Domain"
date: 2017-04-07 07:43:11
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Classification Detection Face_Detection
author: Upal Mahbub, Sayantan Sarkar, Rama Chellappa
mathjax: true
---

* content
{:toc}

##### Abstract
Generic face detection algorithms do not perform well in the mobile domain due to significant presence of occluded and partially visible faces. One promising technique to handle the challenge of partial faces is to design face detectors based on facial segments. In this paper two different approaches of facial segment-based face detection are discussed, namely, proposal-based detection and detection by end-to-end regression. Methods that follow the first approach rely on generating face proposals that contain facial segment information. The three detectors following this approach, namely Facial Segment-based Face Detector (FSFD), SegFace and DeepSegFace, discussed in this paper, perform binary classification on each proposal based on features learned from facial segments. The process of proposal generation, however, needs to be handled separately, which can be very time consuming, and is not truly necessary given the nature of the active authentication problem. Hence a novel algorithm, Deep Regression-based User Image Detector (DRUID) is proposed, which shifts from the classification to the regression paradigm, thus obviating the need for proposal generation. DRUID has an unique network architecture with customized loss functions, is trained using a relatively small amount of data by utilizing a novel data augmentation scheme and is fast since it outputs the bounding boxes of a face and its segments in a single pass. Being robust to occlusion by design, the facial segment-based face detection methods, especially DRUID show superior performance over other state-of-the-art face detectors in terms of precision-recall and ROC curve on two mobile face datasets.

##### Abstract (translated by Google)
通用人脸检测算法在移动领域表现不佳，因为存在遮挡和部分可见的人脸。面对局部人脸挑战的一个有前途的技术是设计基于面部片段的人脸检测器。本文讨论了两种不同的基于面部片段的人脸检测方法，即基于提议的检测和端到端回归检测。采用第一种方法的方法依赖于生成包含面部细分信息的面部提议。采用这种方法的三个检测器，即本文讨论的基于面部分割的人脸检测器（FSFD），SegFace和DeepSegFace，根据面部特征学习的特征对每个提议进行二进制分类。然而，提案生成的过程需要分开处理，这可能是非常耗时的，鉴于主动认证问题的性质，并不是真正必要的。因此，提出了一种基于深度回归的用户图像检测器（DRUID）的新算法，该算法从分类转向回归范式，避免了生成方案的需求。 DRUID具有独特的网络结构，具有定制的损失功能，通过利用新颖的数据增强方案使用相对少量的数据进行训练，并且由于其一次输出面和其片段的边界框，所以速度很快。基于面部片段的人脸检测方法，尤其是DRUID对于两个移动人脸数据集的精度 - 召回率和ROC曲线表现出优于其他现有技术的面部检测器的性能。

##### URL
[https://arxiv.org/abs/1704.02117](https://arxiv.org/abs/1704.02117)

##### PDF
[https://arxiv.org/pdf/1704.02117](https://arxiv.org/pdf/1704.02117)

