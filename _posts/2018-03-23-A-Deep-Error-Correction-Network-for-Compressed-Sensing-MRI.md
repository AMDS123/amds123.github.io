---
layout: post
title: "A Deep Error Correction Network for Compressed Sensing MRI"
date: 2018-03-23 12:18:25
categories: arXiv_CV
tags: arXiv_CV CNN
author: Liyan Sun, Zhiwen Fan, Yue Huang, Xinghao Ding, John Paisley
mathjax: true
---

* content
{:toc}

##### Abstract
Compressed sensing for magnetic resonance imaging (CS-MRI) exploits image sparsity properties to reconstruct MRI from very few Fourier k-space measurements. The goal is to minimize any structural errors in the reconstruction that could have a negative impact on its diagnostic quality. To this end, we propose a deep error correction network (DECN) for CS-MRI. The DECN model consists of three parts, which we refer to as modules: a guide, or template, module, an error correction module, and a data fidelity module. Existing CS-MRI algorithms can serve as the template module for guiding the reconstruction. Using this template as a guide, the error correction module learns a convolutional neural network (CNN) to map the k-space data in a way that adjusts for the reconstruction error of the template image. Our experimental results show the proposed DECN CS-MRI reconstruction framework can considerably improve upon existing inversion algorithms by supplementing with an error-correcting CNN.

##### Abstract (translated by Google)
用于磁共振成像（CS-MRI）的压缩感测利用图像稀疏性质从极少数傅里叶k空间测量值重建MRI。目标是尽量减少重建中可能对其诊断质量产生负面影响的任何结构性错误。为此，我们为CS-MRI提出了一个深度纠错网络（DECN）。 DECN模型由三部分组成，我们称之为模块：指南，模板，模块，纠错模块和数据保真度模块。现有的CS-MRI算法可以作为指导重建的模板模块。使用该模板作为指导，纠错模块学习卷积神经网络（CNN）以调整模板图像重建误差的方式映射k空间数据。我们的实验结果表明，所提出的DECN CS-MRI重建框架可以通过补充错误校正CNN来显着改善现有的反演算法。

##### URL
[https://arxiv.org/abs/1803.08763](https://arxiv.org/abs/1803.08763)

##### PDF
[https://arxiv.org/pdf/1803.08763](https://arxiv.org/pdf/1803.08763)

