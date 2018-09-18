---
layout: post
title: "DocFace+: ID Document to Selfie Matching"
date: 2018-09-15 00:31:44
categories: arXiv_CV
tags: arXiv_CV Face Optimization
author: Yichun Shi, Anil K. Jain
mathjax: true
---

* content
{:toc}

##### Abstract
Numerous activities in our daily life require us to verify who we are by showing our ID documents containing face images, such as passports and driver licenses, to human operators. However, this process is slow, labor intensive and unreliable. As such, an automated system for matching ID document photos to live face images (selfies) in real time and with high accuracy is required. In this paper, we propose DocFace+ to meet this objective. We first show that gradient-based optimization methods converge slowly (due to the underfitting of classifier weights) when many classes have very few samples, a characteristic of existing ID-selfie datasets. To overcome this shortcoming, we propose a method, called dynamic weight imprinting (DWI), to update the classifier weights, which allows faster convergence and more generalizable representations. Next, a pair of sibling networks with partially shared parameters are trained to learn a unified face representation with domain-specific parameters. Cross-validation on an ID-selfie dataset shows that while a publicly available general face matcher (SphereFace) only achieves a True Accept Rate (TAR) of 59.29+-1.55% at a False Accept Rate (FAR) of 0.1% on the problem, DocFace+ improves the TAR to 97.51+-0.40%.

##### Abstract (translated by Google)
我们日常生活中的众多活动要求我们通过向操作人员展示包含面部图像（如护照和驾驶执照）的身份证件来验证我们的身份。但是，这个过程缓慢，劳动强度大且不可靠。这样，需要一种用于实时且高精度地将ID文档照片与实况面部图像（自拍）匹配的自动化系统。在本文中，我们建议DocFace +来实现这一目标。我们首先表明，当许多类具有非常少的样本时，基于梯度的优化方法收敛缓慢（由于分类器权重不足），这是现有ID-selfie数据集的特征。为了克服这个缺点，我们提出了一种称为动态权重印记（DWI）的方法来更新分类器权重，这允许更快的收敛和更通用的表示。接下来，训练具有部分共享参数的一对兄弟网络以学习具有特定于域的参数的统一面部表示。 ID-selfie数据集上的交叉验证显示，虽然公开可用的一般面部匹配器（SphereFace）在该问题的错误接受率（FAR）为0.1％时仅实现59.29 + -1.55％的真实接受率（TAR） ，DocFace +将TAR提高到97.51 + -0.40％。

##### URL
[http://arxiv.org/abs/1809.05620](http://arxiv.org/abs/1809.05620)

##### PDF
[http://arxiv.org/pdf/1809.05620](http://arxiv.org/pdf/1809.05620)

