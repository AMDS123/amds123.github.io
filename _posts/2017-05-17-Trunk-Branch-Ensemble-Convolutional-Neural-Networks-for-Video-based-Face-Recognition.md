---
layout: post
title: "Trunk-Branch Ensemble Convolutional Neural Networks for Video-based Face Recognition"
date: 2017-05-17 09:12:19
categories: arXiv_CV
tags: arXiv_CV Face CNN Recognition Face_Recognition
author: Changxing Ding, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Human faces in surveillance videos often suffer from severe image blur, dramatic pose variations, and occlusion. In this paper, we propose a comprehensive framework based on Convolutional Neural Networks (CNN) to overcome challenges in video-based face recognition (VFR). First, to learn blur-robust face representations, we artificially blur training data composed of clear still images to account for a shortfall in real-world video training data. Using training data composed of both still images and artificially blurred data, CNN is encouraged to learn blur-insensitive features automatically. Second, to enhance robustness of CNN features to pose variations and occlusion, we propose a Trunk-Branch Ensemble CNN model (TBE-CNN), which extracts complementary information from holistic face images and patches cropped around facial components. TBE-CNN is an end-to-end model that extracts features efficiently by sharing the low- and middle-level convolutional layers between the trunk and branch networks. Third, to further promote the discriminative power of the representations learnt by TBE-CNN, we propose an improved triplet loss function. Systematic experiments justify the effectiveness of the proposed techniques. Most impressively, TBE-CNN achieves state-of-the-art performance on three popular video face databases: PaSC, COX Face, and YouTube Faces. With the proposed techniques, we also obtain the first place in the BTAS 2016 Video Person Recognition Evaluation.

##### Abstract (translated by Google)
监控视频中的人脸常常遭受严重的图像模糊，姿态变化和遮挡。在本文中，我们提出了一个基于卷积神经网络（CNN）的综合框架来克服基于视频的人脸识别（VFR）中的挑战。首先，为了学习模糊稳健的人脸表示，我们人为地模糊由清晰的静止图像组成的训练数据，以弥补现实视频训练数据中的不足。使用由静止图像和人为模糊数据组成的训练数据，鼓励CNN自动学习模糊不敏感特征。其次，为了增强CNN特征的鲁棒性以改变和遮挡，我们提出了一个Trunk-Branch Ensemble CNN模型（TBE-CNN），它从整体的人脸图像中提取补充信息， TBE-CNN是一个端到端的模型，通过在干线和分支网络之间共享低层和中层卷积层来有效地提取特征。第三，为了进一步提高TBE-CNN所学交涉的判别力，我们提出了一个改进的三元组损失函数。系统的实验验证了所提出的技术的有效性。最令人印象深刻的是，TBE-CNN在三个流行的视频脸谱数据库（PaSC，COX Face和YouTube Faces）上实现了最先进的性能。通过提出的技术，我们也获得了BTAS 2016视频人物识别评估的第一名。

##### URL
[https://arxiv.org/abs/1607.05427](https://arxiv.org/abs/1607.05427)

##### PDF
[https://arxiv.org/pdf/1607.05427](https://arxiv.org/pdf/1607.05427)

