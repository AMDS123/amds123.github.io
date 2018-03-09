---
layout: post
title: "Rethinking Feature Distribution for Loss Functions in Image Classification"
date: 2018-03-08 07:28:55
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial Image_Classification Classification Recognition
author: Weitao Wan, Yuanyi Zhong, Tianpeng Li, Jiansheng Chen
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a large-margin Gaussian Mixture (L-GM) loss for deep neural networks in classification tasks. Different from the softmax cross-entropy loss, our proposal is established on the assumption that the deep features of the training set follow a Gaussian Mixture distribution. By involving a classification margin and a likelihood regularization, the L-GM loss facilitates both a high classification performance and an accurate modeling of the training feature distribution. As such, the L-GM loss is superior to the softmax loss and its major variants in the sense that besides classification, it can be readily used to distinguish abnormal inputs, such as the adversarial examples, based on their features' likelihood to the training feature distribution. Extensive experiments on various recognition benchmarks like MNIST, CIFAR, ImageNet and LFW, as well as on adversarial examples demonstrate the effectiveness of our proposal.

##### Abstract (translated by Google)
我们在分类任务中提出了深度神经网络的高边缘高斯混合（L-GM）损失。与softmax交叉熵损失不同，我们的建议是在假设训练集的深度特征遵循高斯混合分布的假设下建立的。通过涉及分类边界和似然正则化，L-GM损失既有利于高分类性能，又有利于训练特征分布的准确建模。因此，L-GM损失优于softmax损失及其主要变体，因为除了分类之外，它可以很容易地根据其特征对训练的可能性区分诸如对抗性例子之类的异常输入功能分配。对MNIST，CIFAR，ImageNet和LFW等各种识别基准以及对抗性实例进行的大量实验证明了我们提议的有效性。

##### URL
[http://arxiv.org/abs/1803.02988](http://arxiv.org/abs/1803.02988)

##### PDF
[http://arxiv.org/pdf/1803.02988](http://arxiv.org/pdf/1803.02988)

