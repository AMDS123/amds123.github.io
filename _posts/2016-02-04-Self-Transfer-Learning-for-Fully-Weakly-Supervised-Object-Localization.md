---
layout: post
title: "Self-Transfer Learning for Fully Weakly Supervised Object Localization"
date: 2016-02-04 10:41:57
categories: arXiv_CV
tags: arXiv_CV Weakly_Supervised CNN Transfer_Learning Classification Deep_Learning
author: Sangheum Hwang, Hyo-Eun Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances of deep learning have achieved remarkable performances in various challenging computer vision tasks. Especially in object localization, deep convolutional neural networks outperform traditional approaches based on extraction of data/task-driven features instead of hand-crafted features. Although location information of region-of-interests (ROIs) gives good prior for object localization, it requires heavy annotation efforts from human resources. Thus a weakly supervised framework for object localization is introduced. The term "weakly" means that this framework only uses image-level labeled datasets to train a network. With the help of transfer learning which adopts weight parameters of a pre-trained network, the weakly supervised learning framework for object localization performs well because the pre-trained network already has well-trained class-specific features. However, those approaches cannot be used for some applications which do not have pre-trained networks or well-localized large scale images. Medical image analysis is a representative among those applications because it is impossible to obtain such pre-trained networks. In this work, we present a "fully" weakly supervised framework for object localization ("semi"-weakly is the counterpart which uses pre-trained filters for weakly supervised localization) named as self-transfer learning (STL). It jointly optimizes both classification and localization networks simultaneously. By controlling a supervision level of the localization network, STL helps the localization network focus on correct ROIs without any types of priors. We evaluate the proposed STL framework using two medical image datasets, chest X-rays and mammograms, and achieve signiticantly better localization performance compared to previous weakly supervised approaches.

##### Abstract (translated by Google)
深度学习的最新进展在各种具有挑战性的计算机视觉任务中取得了显着的成绩特别是在物体定位方面，深度卷积神经网络优于传统的基于数据/任务驱动特征而不是手工特征的方法。虽然利益区域（ROI）的位置信息给予物体本地化之前很好，但是它需要人力资源的大量注释。因此引入了一个弱监督的对象本地化框架。术语“弱”意味着该框架仅使用图像级标记的数据集来训练网络。借助于采用预训练网络权重参数的转移学习，由于训练好的网络已经具备了训练有素的类别特征，弱监督学习的对象定位学习框架表现良好。然而，这些方法不能用于一些没有预先训练的网络或局部大规模图像的应用。医学图像分析是这些应用中的代表，因为不可能获得这样的预先训练的网络。在这项工作中，我们提出了一个“完全”弱监督的对象定位框架（“半” - 弱是使用预训练过滤器弱监督本地化的对手）命名为自我转让学习（STL）。它同时对分类和本地化网络进行联合优化。通过控制本地化网络的监督水平，STL可以帮助本地化网络集中精力投资正确的投资回报率，而不需要任何类型的先进技术。我们使用两个医学图像数据集，胸部X射线和乳房X线照片来评估所提出的STL框架，并且与之前的弱监督方法相比，实现了明显更好的定位性能。

##### URL
[https://arxiv.org/abs/1602.01625](https://arxiv.org/abs/1602.01625)

##### PDF
[https://arxiv.org/pdf/1602.01625](https://arxiv.org/pdf/1602.01625)

