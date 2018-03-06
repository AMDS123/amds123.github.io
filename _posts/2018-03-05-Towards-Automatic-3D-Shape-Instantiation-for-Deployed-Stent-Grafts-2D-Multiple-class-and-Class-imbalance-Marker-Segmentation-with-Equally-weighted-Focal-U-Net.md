---
layout: post
title: "Towards Automatic 3D Shape Instantiation for Deployed Stent Grafts: 2D Multiple-class and Class-imbalance Marker Segmentation with Equally-weighted Focal U-Net"
date: 2018-03-05 12:32:24
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Xiao-Yun Zhou Celia Riga, Su-Lin Lee, Guang-Zhong Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Robot-assisted Fenestrated Endovascular Aortic Repair (FEVAR) is currently navigated by 2D fluoroscopy which is insufficiently informative. Previously, a semi-automatic 3D shape instantiation method was developed to instantiate the 3D shape of a main, deployed, and fenestrated stent graft from a single fluoroscopy projection in real-time, which is applied in 3D FEVAR navigation and robotic path planning. This semi-automatic method was based on the Robust Perspective-5-Point (RP5P) method, graft gap interpolation and semi-automatic multiple-class marker center determination. In this paper, automatic 3D shape instantiation could be achieved by automatic multiple-class marker segmentation and hence automatic marker center determination. Firstly, the markers were designed into five different shapes. Then, Equally-weighted Focal U-Net was proposed to segment the customized markers into multiple classes. The proposed network utilized U-Net as the network structure, equally-weighted loss function for initial marker segmentation, and then equally-weighted focal loss function for multiple-class marker segmentation. This network outperformed traditional Weighted U-Net on the class-imbalance segmentation with reducing one hyperparameter - the weight. An overall mean Intersection over Union (mIoU) of $0.6943$ was achieved on $78$ testing images, where $81.01\%$ markers were segmented with a center position error $&lt;1.6mm$. Comparable accuracy of 3D shape instantiation was also achieved. The training/testing images, trained models and TensorFlow codes will be available online.

##### Abstract (translated by Google)
机器人辅助有孔血管内主动脉修复术（FEVAR）目前由二维荧光透视导航，但信息不充分。以前，开发了一种半自动3D形状实例化方法，用于实时从单个荧光透视投影实例化主要，部署和开窗的支架移植物的3D形状，该方法应用于3D FEVAR导航和机器人路径规划。该半自动方法基于鲁棒性透视五点（RP5P）方法，移植间隙插值和半自动多级标记中心确定。在本文中，可以通过自动多级标记分割来实现自动3D形状实例化，并因此实现自动标记中心确定。首先，标记被设计成五种不同的形状。然后，提出等权重焦点U-Net将自定义标记分割成多个类。所提出的网络利用U-Net作为网络结构，对初始标记分割使用等权重损失函数，然后对多级标记分割进行等权重聚焦损失函数。这个网络在类别不平衡分割方面优于传统的加权U-Net，减少了一个超参数 - 权重。在78美元的测试图像上获得了0.6943美元的整体平均交汇点（mIoU），其中81.01美元的标记被中心位置误差$ <1.6mm $分割。还实现了3D形状实例化的相当准确性。培训/测试图像，训练有素的模型和TensorFlow代码将在网上提供。

##### URL
[http://arxiv.org/abs/1711.01506](http://arxiv.org/abs/1711.01506)

##### PDF
[http://arxiv.org/pdf/1711.01506](http://arxiv.org/pdf/1711.01506)

