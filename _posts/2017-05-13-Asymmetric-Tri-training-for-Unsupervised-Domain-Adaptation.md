---
layout: post
title: "Asymmetric Tri-training for Unsupervised Domain Adaptation"
date: 2017-05-13 05:44:03
categories: arXiv_CV
tags: arXiv_CV Sentiment Recognition
author: Kuniaki Saito, Yoshitaka Ushiku, Tatsuya Harada
mathjax: true
---

* content
{:toc}

##### Abstract
Deep-layered models trained on a large number of labeled samples boost the accuracy of many tasks. It is important to apply such models to different domains because collecting many labeled samples in various domains is expensive. In unsupervised domain adaptation, one needs to train a classifier that works well on a target domain when provided with labeled source samples and unlabeled target samples. Although many methods aim to match the distributions of source and target samples, simply matching the distribution cannot ensure accuracy on the target domain. To learn discriminative representations for the target domain, we assume that artificially labeling target samples can result in a good representation. Tri-training leverages three classifiers equally to give pseudo-labels to unlabeled samples, but the method does not assume labeling samples generated from a different domain.In this paper, we propose an asymmetric tri-training method for unsupervised domain adaptation, where we assign pseudo-labels to unlabeled samples and train neural networks as if they are true labels. In our work, we use three networks asymmetrically. By asymmetric, we mean that two networks are used to label unlabeled target samples and one network is trained by the samples to obtain target-discriminative representations. We evaluate our method on digit recognition and sentiment analysis datasets. Our proposed method achieves state-of-the-art performance on the benchmark digit recognition datasets of domain adaptation.

##### Abstract (translated by Google)
在大量标记的样本上训练的深层模型提高了许多任务的准确性。将这样的模型应用于不同的领域是很重要的，因为在各个领域收集许多标记的样本是昂贵的。在无监督的领域适应，需要训练一个分类器，如果提供标记的源样本和未标记的目标样本，在目标领域效果很好。尽管许多方法的目标是匹配源样本和目标样本的分布，但是简单地匹配分布并不能确保目标领域的准确性。为了学习目标域的判别式表示，我们假设人工标记目标样本可以得到很好的表示。 Tri-training同样利用三个分类器对未标记的样本赋予伪标签，但是该方法不假设标签样本是从不同的领域生成的。本文提出了一种非监督的非自适应三重训练方法，伪标签到未标记的样本，并训练神经网络，就好像它们是真正的标签。在我们的工作中，我们使用三个不对称的网络。通过不对称，我们的意思是使用两个网络来标记未标记的目标样本，并且一个网络被样本训练以获得目标区分表示。我们评估我们的数字识别和情感分析数据集的方法。我们提出的方法在领域适应的基准数字识别数据集上实现了最先进的性能。

##### URL
[https://arxiv.org/abs/1702.08400](https://arxiv.org/abs/1702.08400)

##### PDF
[https://arxiv.org/pdf/1702.08400](https://arxiv.org/pdf/1702.08400)

