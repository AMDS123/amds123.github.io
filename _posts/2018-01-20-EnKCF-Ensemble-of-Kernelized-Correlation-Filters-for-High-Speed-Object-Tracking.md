---
layout: post
title: "EnKCF: Ensemble of Kernelized Correlation Filters for High-Speed Object Tracking"
date: 2018-01-20 21:22:46
categories: arXiv_CV
tags: arXiv_CV Tracking CNN Object_Tracking Relation
author: Burak Uzkent, YoungWoo Seo
mathjax: true
---

* content
{:toc}

##### Abstract
Computer vision technologies are very attractive for practical applications running on embedded systems. For such an application, it is desirable for the deployed algorithms to run in high-speed and require no offline training. To develop a single-target tracking algorithm with these properties, we propose an ensemble of the kernelized correlation filters (KCF), we call it EnKCF. A committee of KCFs is specifically designed to address the variations in scale and translation of moving objects. To guarantee a high-speed run-time performance, we deploy each of KCFs in turn, instead of applying multiple KCFs to each frame. To minimize any potential drifts between individual KCFs transition, we developed a particle filter. Experimental results showed that the performance of ours is, on average, 70.10% for precision at 20 pixels, 53.00% for success rate for the OTB100 data, and 54.50% and 40.2% for the UAV123 data. Experimental results showed that our method is better than other high-speed trackers over 5% on precision on 20 pixels and 10-20% on AUC on average. Moreover, our implementation ran at 340 fps for the OTB100 and at 416 fps for the UAV123 dataset that is faster than DCF (292 fps) for the OTB100 and KCF (292 fps) for the UAV123. To increase flexibility of the proposed EnKCF running on various platforms, we also explored different levels of deep convolutional features.

##### Abstract (translated by Google)
计算机视觉技术对嵌入式系统上运行的实际应用非常有吸引力。对于这样的应用，部署的算法需要高速运行而不需要离线训练。为了开发具有这些属性的单目标跟踪算法，我们提出了核化相关滤波器（KCF）的集合，我们称之为EnKCF。 KCFs委员会是专门设计来解决移动物体的尺寸和翻译的变化。为了保证高速运行性能，我们依次部署每个KCF，而不是将多个KCF应用到每个框架。为了最大限度地减少单个KCF转换之间的任何潜在的漂移，我们开发了一个粒子滤波器实验结果表明，我们的性能平均为：20像素精度为70.10％，OTB100数据成功率为53.00％，UAV123数据成功率为54.50％和40.2％。实验结果表明，我们的方法比其他高速跟踪器在20个像素精度上的平均精确度高出5％，AUC平均高出10-20％。而且，我们的实现以OTF100的340fps和UAV123数据集的416fps的速度运行，比OTB100的DCF（292fps）和UAV123的KCF（292fps）更快。为了提高在各种平台上运行的EnKCF的灵活性，我们还研究了不同层次的深度卷积特征。

##### URL
[https://arxiv.org/abs/1801.06729](https://arxiv.org/abs/1801.06729)

##### PDF
[https://arxiv.org/pdf/1801.06729](https://arxiv.org/pdf/1801.06729)

