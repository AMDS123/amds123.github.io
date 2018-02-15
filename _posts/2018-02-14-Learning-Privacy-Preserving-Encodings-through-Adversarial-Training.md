---
layout: post
title: "Learning Privacy Preserving Encodings through Adversarial Training"
date: 2018-02-14 17:04:07
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge Optimization Inference Detection
author: Francesco Pittaluga, Sanjeev J. Koppal, Ayan Chakrabarti
mathjax: true
---

* content
{:toc}

##### Abstract
We present a framework to learn privacy-preserving encodings of images (or other high-dimensional data) to inhibit inference of a chosen private attribute. Rather than encoding a fixed dataset or inhibiting a fixed estimator, we aim to to learn an encoding function such that even after this function is fixed, an estimator with knowledge of the encoding is unable to learn to accurately predict the private attribute, when generalizing beyond a training set. We formulate this as adversarial optimization of an encoding function against a classifier for the private attribute, with both modeled as deep neural networks. We describe an optimization approach which successfully yields an encoder that permanently limits inference of the private attribute, while preserving either a generic notion of information, or the estimation of a different, desired, attribute. We experimentally validate the efficacy of our approach on private tasks of real-world complexity, by learning to prevent detection of scene classes from the Places-365 dataset.

##### Abstract (translated by Google)
我们提出了一个框架来学习图像（或其他高维数据）的隐私保护编码，以禁止推断所选的私有属性。我们的目标不是编码固定数据集或抑制固定估计器，而是致力于学习编码函数，以便即使在修正此函数之后，具有编码知识的估计器也无法学会准确预测私有属性，训练集。我们将此作为针对私有属性的分类器的编码函数的对抗性优化来制定，其中都建模为深度神经网络。我们描述了一种优化方法，该方法成功地产生了永久限制私有属性推断的编码器，同时保留了信息的一般概念，或者估计了不同的，期望的属性。通过学习防止检测Places-365数据集中的场景类，我们通过实验验证了我们方法在真实世界复杂性的私人任务上的功效。

##### URL
[http://arxiv.org/abs/1802.05214](http://arxiv.org/abs/1802.05214)

##### PDF
[http://arxiv.org/pdf/1802.05214](http://arxiv.org/pdf/1802.05214)

