---
layout: post
title: "Multiple Abnormality Detection for Automatic Medical Image Diagnosis Using Bifurcated Convolutional Neural Network"
date: 2018-09-16 07:55:51
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN CNN Classification Detection
author: Mohsen Hajabdollahi, Reza Esfandiarpoor, Elyas Sabeti, Nader Karimi, Kayvan Najarian, S.M. Reza Soroushmehr, Shadrokh Samavi
mathjax: true
---

* content
{:toc}

##### Abstract
Automating classification and segmentation process of abnormal regions in different body organs has a crucial role in most of medical imaging applications such as funduscopy, endoscopy, and dermoscopy. Detecting multiple abnormalities in each type of images is necessary for better and more accurate diagnosis procedure and medical decisions. In recent years portable medical imaging devices such as capsule endoscopy and digital dermatoscope have been introduced and made the diagnosis procedure easier and more efficient. However, these portable devices have constrained power resources and limited computational capability. To address this problem, we propose a bifurcated structure for convolutional neural networks performing both classification and segmentation of multiple abnormalities simultaneously. The proposed network is first trained by each abnormality separately. Then the network is trained using all abnormalities. In order to reduce the computational complexity, the network is redesigned to share some features which are common among all abnormalities. Later, these shared features are used in different settings (directions) to segment and classify the abnormal region of the image. Finally, results of the classification and segmentation directions are fused to obtain the classified segmentation map. Proposed framework is simulated using four frequent gastrointestinal abnormalities as well as three dermoscopic lesions and for evaluation of the proposed framework the results are compared with the corresponding ground truth map. Properties of the bifurcated network like low complexity and resource sharing make it suitable to be implemented as a part of portable medical imaging devices.

##### Abstract (translated by Google)
自动化不同身体器官中异常区域的分类和分割过程在大多数医学成像应用中具有至关重要的作用，例如眼底检查，内窥镜检查和皮肤镜检查。检测每种类型图像中的多种异常对于更好和更准确的诊断程序和医疗决策是必要的。近年来，已经引入了诸如胶囊内窥镜和数字皮肤镜的便携式医学成像设备，并使得诊断过程更容易和更有效。然而，这些便携式设备具有受限的功率资源和有限的计算能力。为了解决这个问题，我们提出了一种用于卷积神经网络的分叉结构，同时对多个异常进行分类和分割。所提出的网络首先分别由每个异常训练。然后使用所有异常来训练网络。为了降低计算复杂度，重新设计网络以共享在所有异常中共同的一些特征。之后，这些共享特征用于不同的设置（方向），以对图像的异常区域进行分段和分类。最后，融合分类和分割方向的结果以获得分类的分割图。使用四种频繁的胃肠道异常以及三种皮肤镜病变模拟所提出的框架，并且为了评估所提出的框架，将结果与相应的地面实况图进行比较。诸如低复杂性和资源共享的分叉网络的属性使其适合于作为便携式医学成像设备的一部分来实现。

##### URL
[http://arxiv.org/abs/1809.05831](http://arxiv.org/abs/1809.05831)

##### PDF
[http://arxiv.org/pdf/1809.05831](http://arxiv.org/pdf/1809.05831)

