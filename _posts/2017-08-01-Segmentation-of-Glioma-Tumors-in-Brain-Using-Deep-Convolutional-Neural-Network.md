---
layout: post
title: "Segmentation of Glioma Tumors in Brain Using Deep Convolutional Neural Network"
date: 2017-08-01 15:06:07
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Detection
author: Saddam Hussain, Syed Muhammad Anwar, Muhammad Majid
mathjax: true
---

* content
{:toc}

##### Abstract
Detection of brain tumor using a segmentation based approach is critical in cases, where survival of a subject depends on an accurate and timely clinical diagnosis. Gliomas are the most commonly found tumors having irregular shape and ambiguous boundaries, making them one of the hardest tumors to detect. The automation of brain tumor segmentation remains a challenging problem mainly due to significant variations in its structure. An automated brain tumor segmentation algorithm using deep convolutional neural network (DCNN) is presented in this paper. A patch based approach along with an inception module is used for training the deep network by extracting two co-centric patches of different sizes from the input images. Recent developments in deep neural networks such as drop-out, batch normalization, non-linear activation and inception module are used to build a new ILinear nexus architecture. The module overcomes the over-fitting problem arising due to scarcity of data using drop-out regularizer. Images are normalized and bias field corrected in the pre-processing step and then extracted patches are passed through a DCNN, which assigns an output label to the central pixel of each patch. Morphological operators are used for post-processing to remove small false positives around the edges. A two-phase weighted training method is introduced and evaluated using BRATS 2013 and BRATS 2015 datasets, where it improves the performance parameters of state-of-the-art techniques under similar settings.

##### Abstract (translated by Google)
使用基于分割的方法检测脑肿瘤对于那些需要准确及时的临床诊断依赖于患者生存的病例至关重要。神经胶质瘤是最常见的肿瘤形状不规则和模糊的边界，使其成为最难检测的肿瘤之一。脑肿瘤分割的自动化仍然是一个具有挑战性的问题，主要是由于其结构的显着变化。提出了一种基于深度卷积神经网络（DCNN）的脑肿瘤自动分割算法。基于补丁的方法与初始模块一起用于通过从输入图像中提取两个不同尺寸的共中心的补丁来训练深度网络。最近深度神经网络的发展，如退出，批量标准化，非线性激活和启动模块被用来建立一个新的ILinear连接体系结构。该模块克服了由于数据不足而引起的过度拟合问题，使用了drop-out regularizer。在预处理步骤中对图像进行归一化和偏置场校正，然后将提取的贴片通过DCNN，该DCNN将输出标签分配给每个贴片的中心像素。形态学算子用于后期处理，以消除边缘周围的小误报。使用BRATS 2013和BRATS 2015数据集引入和评估了两阶段加权训练方法，在相似设置下，它改进了最新技术的性能参数。

##### URL
[https://arxiv.org/abs/1708.00377](https://arxiv.org/abs/1708.00377)

##### PDF
[https://arxiv.org/pdf/1708.00377](https://arxiv.org/pdf/1708.00377)

