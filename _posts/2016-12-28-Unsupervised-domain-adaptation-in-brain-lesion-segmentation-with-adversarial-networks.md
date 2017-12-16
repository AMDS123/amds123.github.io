---
layout: post
title: "Unsupervised domain adaptation in brain lesion segmentation with adversarial networks"
date: 2016-12-28 14:23:34
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation
author: Konstantinos Kamnitsas, Christian Baumgartner, Christian Ledig, Virginia F.J. Newcombe, Joanna P. Simpson, Andrew D. Kane, David K. Menon, Aditya Nori, Antonio Criminisi, Daniel Rueckert, Ben Glocker
mathjax: true
---

* content
{:toc}

##### Abstract
Significant advances have been made towards building accurate automatic segmentation systems for a variety of biomedical applications using machine learning. However, the performance of these systems often degrades when they are applied on new data that differ from the training data, for example, due to variations in imaging protocols. Manually annotating new data for each test domain is not a feasible solution. In this work we investigate unsupervised domain adaptation using adversarial neural networks to train a segmentation method which is more invariant to differences in the input data, and which does not require any annotations on the test domain. Specifically, we learn domain-invariant features by learning to counter an adversarial network, which attempts to classify the domain of the input data by observing the activations of the segmentation network. Furthermore, we propose a multi-connected domain discriminator for improved adversarial training. Our system is evaluated using two MR databases of subjects with traumatic brain injuries, acquired using different scanners and imaging protocols. Using our unsupervised approach, we obtain segmentation accuracies which are close to the upper bound of supervised domain adaptation.

##### Abstract (translated by Google)
使用机器学习为各种生物医学应用构建精确的自动分割系统已经取得重大进展。然而，当这些系统应用于与训练数据不同的新数据时，这些系统的性能常常降低，例如由于成像协议的变化。手动注释每个测试域的新数据不是一个可行的解决方案。在这项工作中，我们调查无监督的领域适应使用敌对神经网络来训练分割方法，这是不变的输入数据的差异，并不需要在测试域上的任何注释。具体而言，我们通过学习对抗敌对网络来学习领域不变特征，试图通过观察分割网络的激活来分类输入数据的领域。此外，我们提出了一个多连接领域鉴别器改善对手训练。我们的系统是使用两个磁共振数据库的创伤性脑损伤，使用不同的扫描仪和成像协议获得的数据库进行评估。使用我们的无监督方法，我们获得接近监督域适应的上限的分割准确度。

##### URL
[https://arxiv.org/abs/1612.08894](https://arxiv.org/abs/1612.08894)

##### PDF
[https://arxiv.org/pdf/1612.08894](https://arxiv.org/pdf/1612.08894)

