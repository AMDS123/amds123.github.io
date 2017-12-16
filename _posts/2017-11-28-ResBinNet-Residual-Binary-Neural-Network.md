---
layout: post
title: "ResBinNet: Residual Binary Neural Network"
date: 2017-11-28 00:45:57
categories: arXiv_CV
tags: arXiv_CV CNN Inference
author: Mohammad Ghasemzadeh, Mohammad Samragh, Farinaz Koushanfar
mathjax: true
---

* content
{:toc}

##### Abstract
Recent efforts on training light-weight binary neural networks offer promising execution/memory efficiency. This paper introduces ResBinNet, which is a composition of two interlinked methodologies aiming to address the slow convergence speed and limited accuracy of binary convolutional neural networks. The first method, called residual binarization, learns a multi-level binary representation for the features within a certain neural network layer. The second method, called temperature adjustment, gradually binarizes the weights of a particular layer. The two methods jointly learn a set of soft-binarized parameters that improve the convergence rate and accuracy of binary neural networks. We corroborate the applicability and scalability of ResBinNet by implementing a prototype hardware accelerator. The accelerator is reconfigurable in terms of the numerical precision of the binarized features, offering a trade-off between runtime and inference accuracy.

##### Abstract (translated by Google)
最近在训练轻量级二元神经网络方面的努力提供了有希望的执行/记忆效率。本文介绍了ResBinNet，它是两种相互关联的方法的组合，旨在解决二元卷积神经网络收敛速度慢，精度有限的问题。第一种方法称为残差二值化，学习一个神经网络层中的特征的多级二进制表示。第二种称为温度调节的方法逐渐将特定层的权重二值化。这两种方法共同学习了一组软二值化参数，提高了二值神经网络的收敛速度和准确性。我们通过实施原型硬件加速器来证实ResBinNet的适用性和可扩展性。加速器可根据二值化特征的数值精度进行重新配置，从而在运行时间和推理精度之间进行权衡。

##### URL
[https://arxiv.org/abs/1711.01243](https://arxiv.org/abs/1711.01243)

##### PDF
[https://arxiv.org/pdf/1711.01243](https://arxiv.org/pdf/1711.01243)

