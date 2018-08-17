---
layout: post
title: "Metric Learning for Novelty and Anomaly Detection"
date: 2018-08-16 13:53:14
categories: arXiv_CV
tags: arXiv_CV Prediction Detection Recognition
author: Marc Masana, Idoia Ruiz, Joan Serrat, Joost van de Weijer, Antonio M. Lopez
mathjax: true
---

* content
{:toc}

##### Abstract
When neural networks process images which do not resemble the distribution seen during training, so called out-of-distribution images, they often make wrong predictions, and do so too confidently. The capability to detect out-of-distribution images is therefore crucial for many real-world applications. We divide out-of-distribution detection between novelty detection ---images of classes which are not in the training set but are related to those---, and anomaly detection ---images with classes which are unrelated to the training set. By related we mean they contain the same type of objects, like digits in MNIST and SVHN. Most existing work has focused on anomaly detection, and has addressed this problem considering networks trained with the cross-entropy loss. Differently from them, we propose to use metric learning which does not have the drawback of the softmax layer (inherent to cross-entropy methods), which forces the network to divide its prediction power over the learned classes. We perform extensive experiments and evaluate both novelty and anomaly detection, even in a relevant application such as traffic sign recognition, obtaining comparable or better results than previous works.

##### Abstract (translated by Google)
当神经网络处理的图像与训练期间看到的分布不相似时，所谓的分布式图像，通常会做出错误的预测，并且过于自信。因此，检测分发外图像的能力对于许多实际应用是至关重要的。我们将新颖性检测 - 不在训练集中但与之相关的类的图像 - 和异常检测 - 与具有与训练集无关的类的图像分开。相关的我们的意思是它们包含相同类型的对象，如MNIST和SVHN中的数字。大多数现有工作都集中在异常检测上，并且考虑到用交叉熵损失训练的网络解决了这个问题。与它们不同，我们建议使用不具有softmax层（交叉熵方法固有）的缺点的度量学习，这迫使网络将其预测能力划分为学习类。我们进行大量实验并评估新颖性和异常检测，即使在交通标志识别等相关应用中，也能获得与之前作品相当或更好的结果。

##### URL
[http://arxiv.org/abs/1808.05492](http://arxiv.org/abs/1808.05492)

##### PDF
[http://arxiv.org/pdf/1808.05492](http://arxiv.org/pdf/1808.05492)

