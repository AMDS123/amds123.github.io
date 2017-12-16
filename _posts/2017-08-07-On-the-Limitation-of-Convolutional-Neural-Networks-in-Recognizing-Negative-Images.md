---
layout: post
title: "On the Limitation of Convolutional Neural Networks in Recognizing Negative Images"
date: 2017-08-07 20:53:28
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN Classification
author: Hossein Hosseini, Baicen Xiao, Mayoore Jaiswal, Radha Poovendran
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNNs) have achieved state-of-the-art performance on a variety of computer vision tasks, particularly visual classification problems, where new algorithms reported to achieve or even surpass the human performance. In this paper, we examine whether CNNs are capable of learning the semantics of training data. To this end, we evaluate CNNs on negative images, since they share the same structure and semantics as regular images and humans can classify them correctly. Our experimental results indicate that when training on regular images and testing on negative images, the model accuracy is significantly lower than when it is tested on regular images. This leads us to the conjecture that current training methods do not effectively train models to generalize the concepts. We then introduce the notion of semantic adversarial examples - transformed inputs that semantically represent the same objects, but the model does not classify them correctly - and present negative images as one class of such inputs.

##### Abstract (translated by Google)
卷积神经网络（CNN）已经在各种计算机视觉任务上取得了最先进的性能，特别是视觉分类问题，在这些问题中新算法被报告达到甚至超过人类的表现。在本文中，我们研究CNN是否有能力学习训练数据的语义。为此，我们对负图像进行CNN评估，因为它们与普通图像具有相同的结构和语义，人类可以对它们进行正确的分类。我们的实验结果表明，当对常规图像进行训练和对负像进行测试时，模型的精确度要比对常规图像进行测试时要低得多。这导致我们猜想，目前的训练方法不能有效地训练模型来概括概念。然后，我们介绍语义对抗例子的概念 - 语义上表示相同对象的变换输入，但模型不能正确分类它们，并将负面图像作为一类输入。

##### URL
[https://arxiv.org/abs/1703.06857](https://arxiv.org/abs/1703.06857)

##### PDF
[https://arxiv.org/pdf/1703.06857](https://arxiv.org/pdf/1703.06857)

