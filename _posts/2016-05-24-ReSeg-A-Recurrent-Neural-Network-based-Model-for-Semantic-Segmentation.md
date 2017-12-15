---
layout: post
title: "ReSeg: A Recurrent Neural Network-based Model for Semantic Segmentation"
date: 2016-05-24 15:55:41
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Image_Classification Semantic_Segmentation RNN Classification Prediction
author: Francesco Visin, Marco Ciccone, Adriana Romero, Kyle Kastner, Kyunghyun Cho, Yoshua Bengio, Matteo Matteucci, Aaron Courville
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a structured prediction architecture, which exploits the local generic features extracted by Convolutional Neural Networks and the capacity of Recurrent Neural Networks (RNN) to retrieve distant dependencies. The proposed architecture, called ReSeg, is based on the recently introduced ReNet model for image classification. We modify and extend it to perform the more challenging task of semantic segmentation. Each ReNet layer is composed of four RNN that sweep the image horizontally and vertically in both directions, encoding patches or activations, and providing relevant global information. Moreover, ReNet layers are stacked on top of pre-trained convolutional layers, benefiting from generic local features. Upsampling layers follow ReNet layers to recover the original image resolution in the final predictions. The proposed ReSeg architecture is efficient, flexible and suitable for a variety of semantic segmentation tasks. We evaluate ReSeg on several widely-used semantic segmentation datasets: Weizmann Horse, Oxford Flower, and CamVid; achieving state-of-the-art performance. Results show that ReSeg can act as a suitable architecture for semantic segmentation tasks, and may have further applications in other structured prediction problems. The source code and model hyperparameters are available on this https URL

##### Abstract (translated by Google)
我们提出了一种结构化的预测体系结构，它利用卷积神经网络提取的局部特征和递归神经网络（RNN）的能力来检索远处的依赖关系。所提出的架构称为ReSeg，是基于最近引入的用于图像分类的ReNet模型。我们修改和扩展它以执行更具挑战性的语义分割任务。每个ReNet层由四个RNN组成，它们在两个方向上水平和垂直扫描图像，编码补丁或激活，并提供相关的全局信息。此外，ReNet层堆叠在预先训练的卷积层之上，受益于通用的局部特征。在最终的预测中，上采样层遵循ReNet层以恢复原始图像分辨率。所提出的ReSeg架构高效，灵活，适用于各种语义分割任务。我们在几个广泛使用的语义分割数据集上评估ReSeg：Weizmann Horse，Oxford Flower和CamVid;实现最先进的性能。结果表明，ReSeg可以作为一个合适的语义分割任务体系结构，并可能在其他结构化预测问题中有更多的应用。源代码和模型超参数在此https URL上可用

##### URL
[https://arxiv.org/abs/1511.07053](https://arxiv.org/abs/1511.07053)

##### PDF
[https://arxiv.org/pdf/1511.07053](https://arxiv.org/pdf/1511.07053)

