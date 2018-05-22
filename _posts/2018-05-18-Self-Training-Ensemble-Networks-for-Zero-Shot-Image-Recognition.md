---
layout: post
title: "Self-Training Ensemble Networks for Zero-Shot Image Recognition"
date: 2018-05-18 23:24:12
categories: arXiv_AI
tags: arXiv_AI Knowledge Embedding Image_Classification Classification Recognition
author: Meng Ye, Yuhong Guo
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the advancement of supervised image recognition algorithms, their de- pendence on the availability of labeled data and the rapid expansion of image categories raise the significant challenge of zero-shot learning. Zero-shot learn- ing (ZSL) aims to transfer knowledge from labeled classes into unlabeled classes to reduce human labeling effort. In this paper, we propose a novel self-training ensemble network model to address zero-shot image recognition. The ensemble network is built by learning multiple image classification functions with a shared feature extraction network but different label embedding representations, each of which facilitates information transfer to different subsets of unlabeled classes. A self-training framework is then deployed to iteratively label the most confident images in each unlabeled class with predicted pseudo-labels and update the ensem- ble network with the training data augmented by the pseudo-labels. The proposed model performs training on both labeled and unlabeled data. It can naturally bridge the domain shift problem in visual appearances and be extended to the generalized zero-shot learning scenario. We conduct experiments on multiple standard ZSL datasets and the empirical results demonstrate the efficacy of the proposed model.

##### Abstract (translated by Google)
尽管监督图像识别算法的进步，但它们依赖于标签数据的可用性以及图像类别的快速扩展，增加了零点学习的重大挑战。零点学习（ZSL）旨在将来自标记类的知识转化为未标记类，以减少人类标记工作量。在本文中，我们提出了一种新的自我训练集成网络模型来解决零点图像识别问题。该集合网络是通过学习多个图像分类函数与共享特征提取网络，但不同的标签嵌入表示来构建的，每个图像分类函数有助于信息传输到不标注类别的不同子集。然后部署一个自我训练框架，用预测的伪标签对每个无标签类别中最自信的图像进行迭代标注，并用伪标签增强的训练数据更新整个网络。所提出的模型对标记数据和未标记数据进行训练。它可以自然地弥合视觉外观中的域转移问题，并且可以扩展到广义零点学习场景。我们在多个标准ZSL数据集上进行实验，实证结果证明了所提出模型的有效性。

##### URL
[https://arxiv.org/abs/1805.07473](https://arxiv.org/abs/1805.07473)

##### PDF
[https://arxiv.org/pdf/1805.07473](https://arxiv.org/pdf/1805.07473)

