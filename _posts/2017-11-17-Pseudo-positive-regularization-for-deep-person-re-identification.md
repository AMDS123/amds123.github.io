---
layout: post
title: "Pseudo-positive regularization for deep person re-identification"
date: 2017-11-17 11:33:14
categories: arXiv_CV
tags: arXiv_CV Regularization Re-identification Face Person_Re-identification CNN
author: Fuqing Zhu, Xiangwei Kong, Haiyan Fu, Qi Tian
mathjax: true
---

* content
{:toc}

##### Abstract
An intrinsic challenge of person re-identification (re-ID) is the annotation difficulty. This typically means 1) few training samples per identity, and 2) thus the lack of diversity among the training samples. Consequently, we face high risk of over-fitting when training the convolutional neural network (CNN), a state-of-the-art method in person re-ID. To reduce the risk of over-fitting, this paper proposes a Pseudo Positive Regularization (PPR) method to enrich the diversity of the training data. Specifically, unlabeled data from an independent pedestrian database is retrieved using the target training data as query. A small proportion of these retrieved samples are randomly selected as the Pseudo Positive samples and added to the target training set for the supervised CNN training. The addition of Pseudo Positive samples is therefore a data augmentation method to reduce the risk of over-fitting during CNN training. We implement our idea in the identification CNN models (i.e., CaffeNet, VGGNet-16 and ResNet-50). On CUHK03 and Market-1501 datasets, experimental results demonstrate that the proposed method consistently improves the baseline and yields competitive performance to the state-of-the-art person re-ID methods.

##### Abstract (translated by Google)
人重新识别（重新识别）的内在挑战是注释难度。这通常意味着1）每个身份的训练样本少，以及2）因此训练样本之间缺乏多样性。因此，我们在训练卷积神经网络（CNN）时面临过度拟合的高风险，卷积神经网络是一种最先进的个人身份识别方法。为了减少过度拟合的风险，本文提出了一种伪正向正则化（PPR）方法来丰富训练数据的多样性。具体来说，使用目标训练数据作为查询来检索来自独立行人数据库的未标记数据。将这些检索到的样本中的一小部分随机选作伪阳性样本，并添加到目标训练集以进行受监督的CNN训练。伪阳性样本的添加因此是数据增加方法，以减少CNN训练期间过度拟合的风险。我们在识别CNN模型（即CaffeNet，VGGNet-16和ResNet-50）中实现了我们的想法。在CUHK03和Market-1501数据集上，实验结果表明，所提出的方法能够持续改善基线，并为最先进的个人身份识别方法提供有竞争力的表现。

##### URL
[https://arxiv.org/abs/1711.06500](https://arxiv.org/abs/1711.06500)

##### PDF
[https://arxiv.org/pdf/1711.06500](https://arxiv.org/pdf/1711.06500)

