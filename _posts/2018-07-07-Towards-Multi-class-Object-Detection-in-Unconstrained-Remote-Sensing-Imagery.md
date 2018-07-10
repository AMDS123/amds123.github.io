---
layout: post
title: "Towards Multi-class Object Detection in Unconstrained Remote Sensing Imagery"
date: 2018-07-07 17:48:57
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Seyed Majid Azimi, Eleonora Vig, Reza Bahmanyar, Marco K&#xf6;rner, Peter Reinartz
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic multi-class object detection in remote sensing images in unconstrained scenarios is of high interest for several applications including traffic monitoring and disaster management. %a crucial and needed tool. The huge variation in object scale, orientation, category, and complex backgrounds, as well as the different camera sensors pose great challenges for current algorithms. In this work, we propose a new method consisting of a novel joint image cascade and feature pyramid network with multi-size convolution kernels to extract multi-scale strong and weak semantic features. These features are fed into rotation-based region proposal and region of interest networks to produce object detections. Finally, rotational non-maximum suppression is applied to remove redundant detections. During training, we minimize joint horizontal and oriented bounding box loss functions, as well as a novel loss that enforces oriented boxes to be rectangular. Our method achieves 68.16\% mAP on horizontal and 72.45\% mAP on oriented bounding box detection tasks on the challenging new DOTA dataset, outperforming all published methods by a large margin ($+6$\% and $+12$\% absolute improvement, respectively). % whereas the best results in the leader-board are 54.13\% and 60.46\%. Furthermore, it generalizes to two other datasets, NWPU VHR-10 and UCAS-AOD, and achieves competitive results with the baselines even when trained on DOTA. Our method can be deployed in multi-class object detection applications, regardless of the image and object scales and orientations, making it a great choice for unconstrained aerial and satellite imagery.

##### Abstract (translated by Google)
无约束情景下的遥感图像中的自动多类物体检测对于包括交通监控和灾害管理在内的多种应用具有高度的兴趣。 ％是一个至关重要的工具。物体尺度，方向，类别和复杂背景的巨大变化以及不同的相机传感器对当前的算法提出了巨大的挑战。在这项工作中，我们提出了一种新的方法，包括一个新的联合图像级联和功能金字塔网络与多尺寸卷积核，以提取多尺度的强弱语义特征。这些特征被馈送到基于旋转的区域提议和感兴趣区域网络以产生对象检测。最后，应用旋转非最大抑制来移除冗余检测。在训练期间，我们最小化关节水平和定向边界框丢失函数，以及强制定向框为矩形的新颖损失。在具有挑战性的新DOTA数据集上，我们的方法在水平方向上实现了68.16％的mAP，在定向边界框检测任务上实现了72.45％的mAP，大大超过了所有已发布的方法（$ + 6 $ \％和$ + $ $ \％绝对值分别改进）。 ％，而排行榜的最佳结果是54.13 \％和60.46 \％。此外，它推广到另外两个数据集，NWPU VHR-10和UCAS-AOD，即使在DOTA上接受过培训，也可以通过基线获得有竞争力的结果。我们的方法可以部署在多类物体检测应用中，无论图像和物体的尺度和方向如何，使其成为无约束天线和卫星图像的绝佳选择。

##### URL
[http://arxiv.org/abs/1807.02700](http://arxiv.org/abs/1807.02700)

##### PDF
[http://arxiv.org/pdf/1807.02700](http://arxiv.org/pdf/1807.02700)

