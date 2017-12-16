---
layout: post
title: "Face Image Reconstruction from Deep Templates"
date: 2017-03-07 09:01:47
categories: arXiv_CV
tags: arXiv_CV Knowledge Face CNN Recognition Face_Recognition
author: Guangcan Mai, Kai Cao, Pong C. Yuen, Anil K. Jain
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art face recognition systems are based on deep (convolutional) neural networks. Therefore, it is imperative to determine to what extent face templates derived from deep networks can be inverted to obtain the original face image. In this paper, we discuss the vulnerabilities of a face recognition system based on deep templates, extracted by deep networks under image reconstruction attack. We propose a de-convolutional neural network (D-CNN) to reconstruct images of faces from their deep templates. In our experiments, we did not assume any knowledge about the target subject nor the deep network. To train the D-CNN reconstruction models, we augmented existing face datasets with a large collection of images synthesized using a face generator. The proposed reconstruction method was evaluated using type-I (comparing the reconstructed images against the original face images used to generate the deep template) and type-II (comparing the reconstructed images against a different face image of the same subject) attacks. We conducted a three-trial attack for each target face image using three face images reconstructed from three different D-CNNs. Each D-CNN was trained on a different dataset (VGG-Face, CASIA-Webface, or Multi-PIE). The type-I attack achieved a true accept rate (TAR) of 85.48% at a false accept rate (FAR) of 0.1% on the LFW dataset. The corresponding TAR for the type-II attack is 14.71%. Our experimental results demonstrate the need to secure deep templates in face recognition systems.

##### Abstract (translated by Google)
最先进的人脸识别系统基于深度（卷积）神经网络。因此，必须确定从深度网络导出的面部模板在多大程度上可以被倒置以获得原始的面部图像。在本文中，我们讨论了基于深度模板的人脸识别系统的脆弱性，深度网络在图像重构攻击下提取。我们提出了一个去卷积神经网络（D-CNN）来重建从他们的深层模板的面部图像。在我们的实验中，我们并没有任何有关目标主体和深层网络的知识。为了训练D-CNN重建模型，我们使用面部生成器合成大量图像来增强现有人脸数据集。所提出的重建方法使用类型I（比较重建图像与用于生成深度模板的原始人脸图像）和类型II（针对相同主题的不同面部图像比较重建图像）来评估。我们使用三个不同的D-CNN重建的三幅面部图像对每个目标人脸图像进行三次试验攻击。每个D-CNN在不同的数据集（VGG-Face，CASIA-Webface或Multi-PIE）上进行训练。 I型攻击在LFW数据集的假接受率（FAR）为0.1％时达到了85.48％的真实接受率（TAR）。相应的II型攻击TAR为14.71％。我们的实验结果表明需要在人脸识别系统中保证深度模板的安全。

##### URL
[https://arxiv.org/abs/1703.00832](https://arxiv.org/abs/1703.00832)

##### PDF
[https://arxiv.org/pdf/1703.00832](https://arxiv.org/pdf/1703.00832)

