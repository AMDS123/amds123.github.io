---
layout: post
title: "Learning Effective RGB-D Representations for Scene Recognition"
date: 2018-09-17 15:07:47
categories: arXiv_CV
tags: arXiv_CV CNN RNN Deep_Learning Recognition
author: Xinhang Song, Shuqiang Jiang, Luis Herranz, Chengpeng Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional networks (CNN) can achieve impressive results on RGB scene recognition thanks to large datasets such as Places. In contrast, RGB-D scene recognition is still underdeveloped in comparison, due to two limitations of RGB-D data we address in this paper. The first limitation is the lack of depth data for training deep learning models. Rather than fine tuning or transferring RGB-specific features, we address this limitation by proposing an architecture and a two-step training approach that directly learns effective depth-specific features using weak supervision via patches. The resulting RGB-D model also benefits from more complementary multimodal features. Another limitation is the short range of depth sensors (typically 0.5m to 5.5m), resulting in depth images not capturing distant objects in the scenes that RGB images can. We show that this limitation can be addressed by using RGB-D videos, where more comprehensive depth information is accumulated as the camera travels across the scene. Focusing on this scenario, we introduce the ISIA RGB-D video dataset to evaluate RGB-D scene recognition with videos. Our video recognition architecture combines convolutional and recurrent neural networks (RNNs) that are trained in three steps with increasingly complex data to learn effective features (i.e. patches, frames and sequences). Our approach obtains state-of-the-art performances on RGB-D image (NYUD2 and SUN RGB-D) and video (ISIA RGB-D) scene recognition.

##### Abstract (translated by Google)
由于像Places这样的大型数据集，深度卷积网络（CNN）可以在RGB场景识别上获得令人印象深刻的结果。相比之下，由于我们在本文中提到的RGB-D数据的两个限制，RGB-D场景识别仍然不发达。第一个限制是缺乏深度学习模型的深度数据。我们不是微调或传输特定于RGB的功能，而是通过提出一种架构和两步训练方法来解决这一局限，该方法通过补丁的弱监督直接学习有效的深度特定功能。由此产生的RGB-D模型也受益于更多互补的多模态特征。另一个限制是短距离传感器（通常为0.5米到5.5米），导致深度图像无法捕捉RGB图像可以拍摄的场景中的远处物体。我们展示了这种限制可以通过使用RGB-D视频来解决，其中当相机在场景中传播时累积更全面的深度信息。着眼于这种情况，我们引入了ISIA RGB-D视频数据集来评估带有视频的RGB-D场景识别。我们的视频识别架构结合了卷积和递归神经网络（RNN），这些神经网络通过三个步骤进行训练，使用越来越复杂的数据来学习有效特征（即补丁，帧和序列）。我们的方法在RGB-D图像（NYUD2和SUN RGB-D）和视频（ISIA RGB-D）场景识别方面获得了最先进的性能。

##### URL
[http://arxiv.org/abs/1809.06269](http://arxiv.org/abs/1809.06269)

##### PDF
[http://arxiv.org/pdf/1809.06269](http://arxiv.org/pdf/1809.06269)

