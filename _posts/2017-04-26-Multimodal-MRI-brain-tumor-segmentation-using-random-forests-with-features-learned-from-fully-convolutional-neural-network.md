---
layout: post
title: "Multimodal MRI brain tumor segmentation using random forests with features learned from fully convolutional neural network"
date: 2017-04-26 14:22:02
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Prediction
author: Mohammadreza Soltaninejad, Lei Zhang, Tryphon Lambrou, Nigel Allinson, Xujiong Ye
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel learning based method for automated segmenta-tion of brain tumor in multimodal MRI images. The machine learned features from fully convolutional neural network (FCN) and hand-designed texton fea-tures are used to classify the MRI image voxels. The score map with pixel-wise predictions is used as a feature map which is learned from multimodal MRI train-ing dataset using the FCN. The learned features are then applied to random for-ests to classify each MRI image voxel into normal brain tissues and different parts of tumor. The method was evaluated on BRATS 2013 challenge dataset. The results show that the application of the random forest classifier to multimodal MRI images using machine-learned features based on FCN and hand-designed features based on textons provides promising segmentations. The Dice overlap measure for automatic brain tumor segmentation against ground truth is 0.88, 080 and 0.73 for complete tumor, core and enhancing tumor, respectively.

##### Abstract (translated by Google)
在本文中，我们提出了一种基于学习的多模态MRI图像自动分割脑肿瘤的方法。该机器学习完全卷积神经网络（FCN）的特征，手工设计的纹理特征用于对MRI图像体素进行分类。以像素方式预测的评分图被用作使用FCN从多模式MRI训练数据集学习的特征图。然后将学习到的特征应用于随机前沿，以将每个MRI图像体素分类为正常脑组织和肿瘤的不同部分。该方法在BRATS 2013挑战数据集上进行评估。结果表明，基于FCN的机器学习特征和基于文本的手工设计特征，将随机森林分类器应用于多模态MRI图像提供了有前景的分割。对于自动脑肿瘤分割的Dice重叠测量，对于完全肿瘤，核心和增强肿瘤分别为0.88,080和0.73。

##### URL
[https://arxiv.org/abs/1704.08134](https://arxiv.org/abs/1704.08134)

##### PDF
[https://arxiv.org/pdf/1704.08134](https://arxiv.org/pdf/1704.08134)

