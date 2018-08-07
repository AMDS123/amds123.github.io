---
layout: post
title: "A Multi-task Framework for Skin Lesion Detection and Segmentation"
date: 2018-08-05 19:13:15
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Detection
author: Sulaiman Vesal, Shreyas Malakarjun Patil, Nishant Ravikumar, Andreas Maier
mathjax: true
---

* content
{:toc}

##### Abstract
Early detection and segmentation of skin lesions is crucial for timely diagnosis and treatment, necessary to improve the survival rate of patients. However, manual delineation is time consuming and subject to intra- and inter-observer variations among dermatologists. This underlines the need for an accurate and automatic approach to skin lesion segmentation. To tackle this issue, we propose a multi-task convolutional neural network (CNN) based, joint detection and segmentation framework, designed to initially localize the lesion and subsequently, segment it. A `Faster region-based convolutional neural network' (Faster-RCNN) which comprises a region proposal network (RPN), is used to generate bounding boxes/region proposals, for lesion localization in each image. The proposed regions are subsequently refined using a softmax classifier and a bounding-box regressor. The refined bounding boxes are finally cropped and segmented using `SkinNet', a modified version of U-Net. We trained and evaluated the performance of our network, using the ISBI 2017 challenge and the PH2 datasets, and compared it with the state-of-the-art, using the official test data released as part of the challenge for the former. Our approach outperformed others in terms of Dice coefficients ($>0.93$), Jaccard index ($>0.88$), accuracy ($>0.96$) and sensitivity ($>0.95$), across five-fold cross validation experiments.

##### Abstract (translated by Google)
皮肤病变的早期检测和分割对于及时诊断和治疗至关重要，这是提高患者生存率所必需的。然而，手动描绘是耗时的并且受到皮肤科医生之间的观察者内和观察者之间的变化的影响。这强调了对皮肤病变分割的准确和自动方法的需求。为了解决这个问题，我们提出了一种基于多任务卷积神经网络（CNN）的联合检测和分割框架，旨在初步定位病变并随后对其进行分割。包括区域提议网络（RPN）的“更快的基于区域的卷积神经网络”（Faster-RCNN）用于生成边界框/区域提议，用于每个图像中的病变定位。随后使用softmax分类器和边界框回归器来细化所提出的区域。精制的边界框最终使用“SkinNet”（U-Net的修改版本）进行裁剪和分段。我们使用ISBI 2017挑战和PH2数据集对我们网络的性能进行了培训和评估，并将其与最新技术进行了比较，使用作为前者挑战的一部分发布的官方测试数据。在五重交叉验证实验中，我们的方法在骰子系数（$> 0.93 $），Jaccard指数（$> 0.88 $），准确度（$> 0.96 $）和敏感度（$> 0.95 $）方面优于其他方法。

##### URL
[https://arxiv.org/abs/1808.01676](https://arxiv.org/abs/1808.01676)

##### PDF
[https://arxiv.org/pdf/1808.01676](https://arxiv.org/pdf/1808.01676)

