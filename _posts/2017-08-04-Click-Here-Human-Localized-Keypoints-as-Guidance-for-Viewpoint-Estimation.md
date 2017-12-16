---
layout: post
title: "Click Here: Human-Localized Keypoints as Guidance for Viewpoint Estimation"
date: 2017-08-04 23:01:39
categories: arXiv_CV
tags: arXiv_CV CNN Inference Prediction
author: Ryan Szeto, Jason J. Corso
mathjax: true
---

* content
{:toc}

##### Abstract
We motivate and address a human-in-the-loop variant of the monocular viewpoint estimation task in which the location and class of one semantic object keypoint is available at test time. In order to leverage the keypoint information, we devise a Convolutional Neural Network called Click-Here CNN (CH-CNN) that integrates the keypoint information with activations from the layers that process the image. It transforms the keypoint information into a 2D map that can be used to weigh features from certain parts of the image more heavily. The weighted sum of these spatial features is combined with global image features to provide relevant information to the prediction layers. To train our network, we collect a novel dataset of 3D keypoint annotations on thousands of CAD models, and synthetically render millions of images with 2D keypoint information. On test instances from PASCAL 3D+, our model achieves a mean class accuracy of 90.7%, whereas the state-of-the-art baseline only obtains 85.7% mean class accuracy, justifying our argument for human-in-the-loop inference.

##### Abstract (translated by Google)
我们激励和解决单眼视点估计任务的人在回线变体，其中一个语义对象关键点的位置和类在测试时间是可用的。为了利用关键点信息，我们设计了一个称为Click-Here CNN（CNN）的卷积神经网络，它将关键点信息与处理图像的图层的激活相结合。它将关键点信息转换成二维地图，可用于更加严重地衡量图像某些部分的特征。这些空间特征的加权总和与全局图像特征相结合以向预测层提供相关信息。为了训练我们的网络，我们收集了数千个CAD模型上的3D关键点注释的新颖数据集，并用2D关键点信息综合地渲染了数百万个图像。对于来自PASCAL 3D +的测试实例，我们的模型达到了90.7％的平均类精度，而最先进的基线只获得了85.7％的平均类精度，证明了我们对于人类在环推理的论证。

##### URL
[https://arxiv.org/abs/1703.09859](https://arxiv.org/abs/1703.09859)

##### PDF
[https://arxiv.org/pdf/1703.09859](https://arxiv.org/pdf/1703.09859)

