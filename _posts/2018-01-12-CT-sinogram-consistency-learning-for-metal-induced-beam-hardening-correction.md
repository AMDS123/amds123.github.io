---
layout: post
title: "CT sinogram-consistency learning for metal-induced beam hardening correction"
date: 2018-01-12 07:05:01
categories: arXiv_CV
tags: arXiv_CV Regularization Deep_Learning
author: Hyung Suk Park, Sung Min Lee, Hwa Pyung Kim, Jin Keun Seo
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a sinogram consistency learning method to deal with beam-hardening related artifacts in polychromatic computerized tomography (CT). The presence of highly attenuating materials in the scan field causes an inconsistent sinogram, that does not match the range space of the Radon transform. When the mismatched data are entered into the range space during CT reconstruction, streaking and shading artifacts are generated owing to the inherent nature of the inverse Radon transform. The proposed learning method aims to repair inconsistent sinograms by removing the primary metal-induced beam-hardening factors along the metal trace in the sinogram. Taking account of the fundamental difficulty in obtaining sufficient training data in a medical environment, the learning method is designed to use simulated training data and a patient-type specific learning model is used to simplify the learning process. The feasibility of the proposed method is investigated using a dataset, consisting of real CT scan of pelvises containing hip prostheses. The anatomical areas in training and test data are different, in order to demonstrate that the proposed method extracts the beam hardening features, selectively. The results show that our method successfully corrects sinogram inconsistency by extracting beam-hardening sources by means of deep learning. This paper proposed a deep learning method of sinogram correction for beam hardening reduction in CT for the first time. Conventional methods for beam hardening reduction are based on regularizations, and have the fundamental drawback of being not easily able to use manifold CT images, while a deep learning approach has the potential to do so.

##### Abstract (translated by Google)
本文提出了一种在多色计算机断层摄影（CT）中处理光束硬化相关伪影的正弦学一致性学习方法。在扫描场中高度衰减的材料的存在导致不一致的正弦图，这不符合氡变换的距离空间。在CT重建过程中，当不匹配数据进入距离空间时，由于逆Radon变换的固有特性，会产生斑纹和阴影伪影。所提出的学习方法旨在通过沿正弦图中的金属迹线去除主要金属引起的束硬化因子来修复不一致的正弦图。考虑到在医疗环境中获得足够的训练数据的基本困难，学习方法被设计为使用模拟训练数据，并且使用患者类型特定的学习模型来简化学习过程。所提出的方法的可行性进行了调查使用的数据集，包括髋关节假体骨盆的真正的CT扫描。训练和测试数据中的解剖区域是不同的，以便证明所提出的方法有选择地提取射束硬化特征。结果表明，我们的方法通过深度学习的方式提取光束硬化源来成功校正正弦波的不一致性。本文首次提出了一种用于光束硬化还原的深度学习方法。传统的减少光束硬化的方法基于正则化，并且具有不能容易地使用流形CT图像的根本缺点，而深度学习方法有潜力这样做。

##### URL
[http://arxiv.org/abs/1708.00607](http://arxiv.org/abs/1708.00607)

##### PDF
[http://arxiv.org/pdf/1708.00607](http://arxiv.org/pdf/1708.00607)

