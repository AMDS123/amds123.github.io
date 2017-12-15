---
layout: post
title: "Maximum-Margin Structured Learning with Deep Networks for 3D Human Pose Estimation"
date: 2015-08-27 03:21:15
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Embedding CNN
author: Sijin Li, Weichen Zhang, Antoni B. Chan
mathjax: true
---

* content
{:toc}

##### Abstract
This paper focuses on structured-output learning using deep neural networks for 3D human pose estimation from monocular images. Our network takes an image and 3D pose as inputs and outputs a score value, which is high when the image-pose pair matches and low otherwise. The network structure consists of a convolutional neural network for image feature extraction, followed by two sub-networks for transforming the image features and pose into a joint embedding. The score function is then the dot-product between the image and pose embeddings. The image-pose embedding and score function are jointly trained using a maximum-margin cost function. Our proposed framework can be interpreted as a special form of structured support vector machines where the joint feature space is discriminatively learned using deep neural networks. We test our framework on the Human3.6m dataset and obtain state-of-the-art results compared to other recent methods. Finally, we present visualizations of the image-pose embedding space, demonstrating the network has learned a high-level embedding of body-orientation and pose-configuration.

##### Abstract (translated by Google)
本文重点研究利用深度神经网络进行结构化输出学习，用于单眼图像的三维人体姿态估计。我们的网络将图像和3D姿势作为输入并输出分数值，当图像 - 姿势匹配匹配时，分数值高，否则低。网络结构包括一个用于图像特征提取的卷积神经网络，其次是两个子网络，用于变换图像特征并构成联合嵌入。得分函数是图像与姿势嵌入之间的点积。图像姿势嵌入和分数函数是使用最大裕度成本函数联合训练的。我们提出的框架可以被解释为结构化支持向量机的一种特殊形式，其中联合特征空间是使用深度神经网络来区分地学习的。我们在Human3.6m数据集上测试我们的框架，并获得与其他最近的方法相比最先进的结果。最后，我们给出了图像姿态嵌入空间的可视化，展示了网络已经学习了一个高层次的身体姿态和姿态配置的嵌入。

##### URL
[https://arxiv.org/abs/1508.06708](https://arxiv.org/abs/1508.06708)

##### PDF
[https://arxiv.org/pdf/1508.06708](https://arxiv.org/pdf/1508.06708)

