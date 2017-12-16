---
layout: post
title: "Self-Supervised Siamese Learning on Stereo Image Pairs for Depth Estimation in Robotic Surgery"
date: 2017-05-17 11:10:49
categories: arXiv_CV
tags: arXiv_CV GAN CNN Deep_Learning Prediction
author: Menglong Ye, Edward Johns, Ankur Handa, Lin Zhang, Philip Pratt, Guang-Zhong Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Robotic surgery has become a powerful tool for performing minimally invasive procedures, providing advantages in dexterity, precision, and 3D vision, over traditional surgery. One popular robotic system is the da Vinci surgical platform, which allows preoperative information to be incorporated into live procedures using Augmented Reality (AR). Scene depth estimation is a prerequisite for AR, as accurate registration requires 3D correspondences between preoperative and intraoperative organ models. In the past decade, there has been much progress on depth estimation for surgical scenes, such as using monocular or binocular laparoscopes [1,2]. More recently, advances in deep learning have enabled depth estimation via Convolutional Neural Networks (CNNs) [3], but training requires a large image dataset with ground truth depths. Inspired by [4], we propose a deep learning framework for surgical scene depth estimation using self-supervision for scalable data acquisition. Our framework consists of an autoencoder for depth prediction, and a differentiable spatial transformer for training the autoencoder on stereo image pairs without ground truth depths. Validation was conducted on stereo videos collected in robotic partial nephrectomy.

##### Abstract (translated by Google)
机器人手术已成为执行微创手术的有力工具，与传统手术相比，在灵活性，精确性和三维视觉方面具有优势。一个流行的机器人系统是达芬奇手术平台，它允许使用增强现实（AR）将术前信息并入现场手术。场景深度估计是AR的先决条件，因为准确的配准需要术前和术中器官模型之间的3D对应。在过去十年中，手术场景的深度估计已经取得了很大的进展，如单眼或双目腹腔镜[1,2]。最近，深度学习的进展使得通过卷积神经网络（CNN）进行深度估计成为可能[3]，但是训练需要一个大的具有地深深度的图像数据集。受到文献[4]的启发，我们提出了一个深度学习框架，利用自我监测的可伸缩数据采集手术场景深度估计。我们的框架包括一个用于深度预测的自编码器，以及一个用于在没有地面真实深度的情况下在立体图像对上训练自编码器的可微分空间变换器。在机器人部分肾切除术中采集的立体视频进行验证。

##### URL
[https://arxiv.org/abs/1705.08260](https://arxiv.org/abs/1705.08260)

##### PDF
[https://arxiv.org/pdf/1705.08260](https://arxiv.org/pdf/1705.08260)

