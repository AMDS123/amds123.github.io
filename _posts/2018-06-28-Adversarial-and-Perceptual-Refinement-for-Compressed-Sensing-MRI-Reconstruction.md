---
layout: post
title: "Adversarial and Perceptual Refinement for Compressed Sensing MRI Reconstruction"
date: 2018-06-28 22:12:39
categories: arXiv_CV
tags: arXiv_CV Adversarial Deep_Learning
author: Maximilian Seitzer, Guang Yang, Jo Schlemper, Ozan Oktay, Tobias W&#xfc;rfl, Vincent Christlein, Tom Wong, Raad Mohiaddin, David Firmin, Jennifer Keegan, Daniel Rueckert, Andreas Maier
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning approaches have shown promising performance for compressed sensing-based Magnetic Resonance Imaging. While deep neural networks trained with mean squared error (MSE) loss functions can achieve high peak signal to noise ratio, the reconstructed images are often blurry and lack sharp details, especially for higher undersampling rates. Recently, adversarial and perceptual loss functions have been shown to achieve more visually appealing results. However, it remains an open question how to (1) optimally combine these loss functions with the MSE loss function and (2) evaluate such a perceptual enhancement. In this work, we propose a hybrid method, in which a visual refinement component is learnt on top of an MSE loss-based reconstruction network. In addition, we introduce a semantic interpretability score, measuring the visibility of the region of interest in both ground truth and reconstructed images, which allows us to objectively quantify the usefulness of the image quality for image post-processing and analysis. Applied on a large cardiac MRI dataset simulated with 8-fold undersampling, we demonstrate significant improvements ($p&lt;0.01$) over the state-of-the-art in both a human observer study and the semantic interpretability score.

##### Abstract (translated by Google)
深度学习方法已经显示出基于压缩感知的磁共振成像的有希望的性能。虽然使用均方误差（MSE）损失函数训练的深度神经网络可以实现较高的峰值信噪比，但重构图像通常模糊不清，并且缺乏清晰的细节，尤其是对于较高的欠采样率。最近，已经证明对抗性和感知性丧失功能可以获得更具视觉吸引力的结果。然而，如何（1）将这些损失函数与MSE损失函数进行最优组合以及（2）评估这种感知增强仍然是一个悬而未决的问题。在这项工作中，我们提出了一种混合方法，其中在MSE损失重建网络上学习视觉细化成分。此外，我们引入了语义可解释性分数，测量了地面实况和重建图像中感兴趣区域的可见性，这使我们能够客观地量化图像质量对图像后处理和分析的有用性。应用于用8倍欠采样模拟的大型心脏MRI数据集，我们证明了在人类观察者研究和语义可解释性得分方面相对于现有技术的显着改进（$ p <0.01 $）。

##### URL
[http://arxiv.org/abs/1806.11216](http://arxiv.org/abs/1806.11216)

##### PDF
[http://arxiv.org/pdf/1806.11216](http://arxiv.org/pdf/1806.11216)

