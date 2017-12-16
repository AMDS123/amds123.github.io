---
layout: post
title: "Nazr-CNN: Fine-Grained Classification of UAV Imagery for Damage Assessment"
date: 2017-08-22 08:27:52
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face CNN Transfer_Learning Classification Deep_Learning Detection
author: N. Attari, F. Ofli, M. Awad, J. Lucas, S. Chawla
mathjax: true
---

* content
{:toc}

##### Abstract
We propose Nazr-CNN1, a deep learning pipeline for object detection and fine-grained classification in images acquired from Unmanned Aerial Vehicles (UAVs) for damage assessment and monitoring. Nazr-CNN consists of two components. The function of the first component is to localize objects (e.g. houses or infrastructure) in an image by carrying out a pixel-level classification. In the second component, a hidden layer of a Convolutional Neural Network (CNN) is used to encode Fisher Vectors (FV) of the segments generated from the first component in order to help discriminate between different levels of damage. To showcase our approach we use data from UAVs that were deployed to assess the level of damage in the aftermath of a devastating cyclone that hit the island of Vanuatu in 2015. The collected images were labeled by a crowdsourcing effort and the labeling categories consisted of fine-grained levels of damage to built structures. Since our data set is relatively small, a pre- trained network for pixel-level classification and FV encoding was used. Nazr-CNN attains promising results both for object detection and damage assessment suggesting that the integrated pipeline is robust in the face of small data sets and labeling errors by annotators. While the focus of Nazr-CNN is on assessment of UAV images in a post-disaster scenario, our solution is general and can be applied in many diverse settings. We show one such case of transfer learning to assess the level of damage in aerial images collected after a typhoon in Philippines.

##### Abstract (translated by Google)
我们提出Nazr-CNN1，一种深度学习管道，用于从无人机（UAV）获取的图像中的目标检测和细粒度分类，用于损害评估和监测。 Nazr CNN由两部分组成。第一部分的功能是通过执行像素级分类来定位图像中的对象（例如房屋或基础设施）。在第二个组件中，使用卷积神经网络（CNN）的隐藏层编码从第一个组件产生的段的Fisher矢量（FV），以帮助区分不同级别的损害。为了展示我们的方法，我们使用部署的无人机数据来评估2015年瓦努阿图岛遭受破坏性气旋后的破坏程度。所收集的图像被标记为众包，标签类别包括罚款对建筑结构造成的损害程度。由于我们的数据集相对较小，所以使用了一个预先训练好的像素级分类和FV编码网络。 Nazr-CNN在目标检测和损伤评估方面都取得了令人鼓舞的成果，表明整合的管道在面对小数据集和注释者的标签错误时是稳健的。虽然Nazr CNN的重点是在灾后情景下对无人机图像进行评估，但我们的解决方案是一般的，可以应用于许多不同的环境。我们展示了一个这样的转移学习案例来评估菲律宾台风后收集的航拍图像的损坏程度。

##### URL
[https://arxiv.org/abs/1611.06474](https://arxiv.org/abs/1611.06474)

##### PDF
[https://arxiv.org/pdf/1611.06474](https://arxiv.org/pdf/1611.06474)

