---
layout: post
title: "Classification Uncertainty of Deep Neural Networks Based on Gradient Information"
date: 2018-05-22 08:07:14
categories: arXiv_AI
tags: arXiv_AI CNN Classification
author: Philipp Oberdiek, Matthias Rottmann, Hanno Gottschalk
mathjax: true
---

* content
{:toc}

##### Abstract
We study the quantification of uncertainty of Convolutional Neural Networks (CNNs) based on gradient metrics. Unlike the classical softmax entropy, such metrics gather information from all layers of the CNN. We show for the (E)MNIST data set that for several such metrics we achieve the same meta classification accuracy -- i.e. the task of classifying correctly predicted labels as correct and incorrectly predicted ones as incorrect without knowing the actual label -- as for entropy thresholding. Meta classification rates for out of sample images can be increased when using entropy together with several gradient based metrics as input quantities for a meta-classifier. This proves that our gradient based metrics do not contain the same information as the entropy. We also apply meta classification to concepts not used during training: EMNIST/Omniglot letters, CIFAR10 and noise. Meta classifiers only trained on the uncertainty metrics of classes available during training usually do not perform equally well for all the unknown concepts letters, CIFAR10 and uniform noise. If we however allow the meta classifier to be trained on uncertainty metrics including some samples of some or all of the categories, meta classification for concepts remote from MNIST digits can be improved considerably.

##### Abstract (translated by Google)
我们研究了基于梯度度量的卷积神经网络（CNN）的不确定性量化。与传统的softmax熵不同，这些度量收集来自CNN所有层的信息。我们针对（E）MNIST数据集展示了对于若干这样的度量我们实现相同的元分类准确性 - 即正确地将预测的标签分类为不正确且不正确地预测的标签作为不正确的而不知道实际标签的任务 - 对于熵阈值。将熵与多个基于梯度的度量一起使用作为元分类器的输入量时，可以增加样本图像外的元分类率。这证明我们的基于梯度的度量不包含与熵相同的信息。我们还将元分类应用于培训期间未使用的概念：EMNIST / Omniglot字母，CIFAR10和噪音。仅在训练期间可用类别的不确定性度量方面训练的元分类器通常对于所有未知概念字母，CIFAR10和均匀噪声表现不佳。然而，如果我们允许对元分类器进行不确定度量度的训练，包括一些或所有类别的一些样本，则远离MNIST数字的概念的元分类可以大大改善。

##### URL
[https://arxiv.org/abs/1805.08440](https://arxiv.org/abs/1805.08440)

##### PDF
[https://arxiv.org/pdf/1805.08440](https://arxiv.org/pdf/1805.08440)

