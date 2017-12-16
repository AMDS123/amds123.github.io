---
layout: post
title: "Fully Convolutional Networks to Detect Clinical Dermoscopic Features"
date: 2017-03-14 00:54:18
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Image_Classification Classification
author: Jeremy Kawahara, Ghassan Hamarneh
mathjax: true
---

* content
{:toc}

##### Abstract
We use a pretrained fully convolutional neural network to detect clinical dermoscopic features from dermoscopy skin lesion images. We reformulate the superpixel classification task as an image segmentation problem, and extend a neural network architecture originally designed for image classification to detect dermoscopic features. Specifically, we interpolate the feature maps from several layers in the network to match the size of the input, concatenate the resized feature maps, and train the network to minimize a smoothed negative F1 score. Over the public validation leaderboard of the 2017 ISIC/ISBI Lesion Dermoscopic Feature Extraction Challenge, our approach achieves 89.3% AUROC, the highest averaged score when compared to the other two entries. Results over the private test leaderboard are still to be announced.

##### Abstract (translated by Google)
我们使用预训练的完全卷积神经网络来从皮肤镜皮肤损伤图像中检测临床皮肤镜特征。我们将超像素分类任务改写为图像分割问题，并扩展了最初设计用于图像分类的神经网络体系结构，以检测皮肤镜的特征。具体而言，我们从网络中的多个层次插入特征映射以匹配输入的大小，连接调整大小的特征映射，并训练网络以最小化平滑的负F1分数。在2017 ISIC / ISBI病灶皮肤镜特征提取挑战赛的公开验证排行榜上，我们的方法达到了89.3％的AUROC，与其他两项相比平均得分最高。私人测试排行榜的结果还有待公布。

##### URL
[https://arxiv.org/abs/1703.04559](https://arxiv.org/abs/1703.04559)

##### PDF
[https://arxiv.org/pdf/1703.04559](https://arxiv.org/pdf/1703.04559)

