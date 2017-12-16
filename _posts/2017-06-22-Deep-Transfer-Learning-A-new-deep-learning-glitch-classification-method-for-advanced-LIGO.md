---
layout: post
title: "Deep Transfer Learning: A new deep learning glitch classification method for advanced LIGO"
date: 2017-06-22 18:11:13
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge CNN Transfer_Learning Classification Deep_Learning Detection Recognition
author: Daniel George, Hongyu Shen, E. A. Huerta
mathjax: true
---

* content
{:toc}

##### Abstract
The exquisite sensitivity of the advanced LIGO detectors has enabled the detection of multiple gravitational wave signals. The sophisticated design of these detectors mitigates the effect of most types of noise. However, advanced LIGO data streams are contaminated by numerous artifacts known as glitches: non-Gaussian noise transients with complex morphologies. Given their high rate of occurrence, glitches can lead to false coincident detections, obscure and even mimic gravitational wave signals. Therefore, successfully characterizing and removing glitches from advanced LIGO data is of utmost importance. Here, we present the first application of Deep Transfer Learning for glitch classification, showing that knowledge from deep learning algorithms trained for real-world object recognition can be transferred for classifying glitches in time-series based on their spectrogram images. Using the Gravity Spy dataset, containing hand-labeled, multi-duration spectrograms obtained from real LIGO data, we demonstrate that this method enables optimal use of very deep convolutional neural networks for classification given small training datasets, significantly reduces the time for training the networks, and achieves state-of-the-art accuracy above 98.8%, with perfect precision-recall on 8 out of 22 classes. Furthermore, new types of glitches can be classified accurately given few labeled examples with this technique. Once trained via transfer learning, we show that the convolutional neural networks can be truncated and used as excellent feature extractors for unsupervised clustering methods to identify new classes based on their morphology, without any labeled examples. Therefore, this provides a new framework for dynamic glitch classification for gravitational wave detectors, which are expected to encounter new types of noise as they undergo gradual improvements to attain design sensitivity.

##### Abstract (translated by Google)
先进的LIGO探测器的精巧的灵敏度使得能够检测多个引力波信号。这些探测器的复杂设计减轻了大多数噪音的影响。然而，先进的LIGO数据流被许多被称为毛刺的伪像所污染：具有复杂形态的非高斯噪声瞬变。由于其发生率很高，故障可能导致错误的重合检测，模糊甚至模仿引力波信号。因此，成功地表征和消除先进的LIGO数据中的故障是至关重要的。在这里，我们介绍深度转移学习的第一个应用程序，用于故障分类，显示从深度学习算法训练的真实世界物体识别的知识可以转移到时间序列毛刺分类基于他们的光谱图像。使用重力间谍数据集，包含从实际LIGO数据中获得的手标记的多持续时间谱图，我们证明，该方法使得能够在给定小的训练数据集的情况下优化使用非常深的卷积神经网络进行分类，显着减少训练网络的时间，达到了98.8％以上的最高精度，22个班级中有8个达到了完美的精确度。此外，使用这种技术，只需少量标记的例子就可以准确地分类新的毛刺类型。一旦通过传递学习进行训练，我们展示卷积神经网络可以被截断并用作非监督聚类方法的优秀特征提取器，以基于其形态识别新类别，而没有任何标记示例。因此，这为引力波探测器的动态干扰分类提供了一个新的框架，随着它们逐渐改进以获得设计灵敏度，预计会遇到新的噪声类型。

##### URL
[https://arxiv.org/abs/1706.07446](https://arxiv.org/abs/1706.07446)

##### PDF
[https://arxiv.org/pdf/1706.07446](https://arxiv.org/pdf/1706.07446)

