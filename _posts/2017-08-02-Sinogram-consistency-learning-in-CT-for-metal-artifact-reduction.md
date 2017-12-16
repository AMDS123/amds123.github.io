---
layout: post
title: "Sinogram-consistency learning in CT for metal artifact reduction"
date: 2017-08-02 05:36:25
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Hyung Suk Park, Yong Eun Chung, Sung Min Lee, Hwa Pyung Kim, Jin Keun Seo
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a sinogram consistency learning method to deal with beam-hardening related artifacts in polychromatic computerized tomography (CT). The presence of highly attenuating materials in the scan field causes an inconsistent sinogram, that does not match the range space of the Radon transform. When the mismatched data are entered into the range space during CT reconstruction, streaking and shading artifacts are generated owing to the inherent nature of the inverse Radon transform. The proposed learning method aims to repair inconsistent sinograms by removing the primary metal-induced beam-hardening factors along the metal trace in the sinogram. Taking account of the fundamental difficulty in obtaining sufficient training data in a medical environment, the learning method is designed to use simulated training data. We use a patient-type specific learning model to simplify the learning process. The quality of sinogram repair was established through data inconsistency-evaluation and acceptance checking, which were conducted using a specially designed inconsistency-evaluation function that identifies the degree and structure of mismatch in terms of projection angles. The results show that our method successfully corrects sinogram inconsistency by extracting beam-hardening sources by means of deep learning.

##### Abstract (translated by Google)
本文提出了一种在多色计算机断层摄影（CT）中处理光束硬化相关伪影的正弦学一致性学习方法。在扫描场中高度衰减的材料的存在导致不一致的正弦图，其不符合氡变换的距离空间。在CT重建过程中，当不匹配数据进入距离空间时，由于逆Radon变换的固有特性，会产生斑纹和阴影伪影。所提出的学习方法旨在通过沿正弦图中的金属迹线去除主要金属引起的束硬化因子来修复不一致的正弦图。考虑到在医疗环境中获得充足的训练数据的根本困难，学习方法被设计为使用模拟的训练数据。我们使用患者类型的特定学习模型来简化学习过程。通过数据不一致性评估和验收检查，建立了正弦图修复的质量标准，采用专门设计的不一致性评估函数，根据投影角度确定不匹配的程度和结构。结果表明，我们的方法通过深度学习的方式提取光束硬化源，成功地纠正了正弦波的不一致性。

##### URL
[https://arxiv.org/abs/1708.00607](https://arxiv.org/abs/1708.00607)

##### PDF
[https://arxiv.org/pdf/1708.00607](https://arxiv.org/pdf/1708.00607)

