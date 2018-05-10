---
layout: post
title: "Urban Land Cover Classification with Missing Data Modalities Using Deep Convolutional Neural Networks"
date: 2018-05-08 20:44:16
categories: arXiv_CV
tags: arXiv_CV Face CNN Classification
author: Michael Kampffmeyer, Arnt-B&#xf8;rre Salberg, Robert Jenssen
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic urban land cover classification is a fundamental problem in remote sensing, e.g. for environmental monitoring. The problem is highly challenging, as classes generally have high inter-class and low intra-class variance. Techniques to improve urban land cover classification performance in remote sensing include fusion of data from different sensors with different data modalities. However, such techniques require all modalities to be available to the classifier in the decision-making process, i.e. at test time, as well as in training. If a data modality is missing at test time, current state-of-the-art approaches have in general no procedure available for exploiting information from these modalities. This represents a waste of potentially useful information. We propose as a remedy a convolutional neural network (CNN) architecture for urban land cover classification which is able to embed all available training modalities in a so-called hallucination network. The network will in effect replace missing data modalities in the test phase, enabling fusion capabilities even when data modalities are missing in testing. We demonstrate the method using two datasets consisting of optical and digital surface model (DSM) images. We simulate missing modalities by assuming that DSM images are missing during testing. Our method outperforms both standard CNNs trained only on optical images as well as an ensemble of two standard CNNs. We further evaluate the potential of our method to handle situations where only some DSM images are missing during testing. Overall, we show that we can clearly exploit training time information of the missing modality during testing.

##### Abstract (translated by Google)
自动城市土地覆盖分类是遥感中的一个基本问题，例如，进行环境监测。这个问题非常具有挑战性，因为班级一般具有较高的班级间差异和较低的班内差异。提高城市土地覆盖遥感分类性能的技术包括将来自不同传感器的数据与不同数据模式融合。然而，这些技术要求分类器在决策过程中，即在测试时间以及在训练中都可以使用所有的模态。如果数据模式在测试时间丢失，目前最先进的方法通常没有可用于利用这些模式的信息的过程。这代表了浪费潜在有用的信息。我们提出了一种补救方法 - 用于城市土地覆盖分类的卷积神经网络（CNN）体系结构，该体系能够将所有可用的训练模式嵌入到所谓的幻觉网络中。该网络将在测试阶段取代缺失的数据模式，即使在测试中缺少数据模式时也可实现融合功能。我们演示了使用由光学和数字表面模型（DSM）图像组成的两个数据集的方法。我们通过假设测试过程中DSM图像丢失来模拟丢失的模式。我们的方法优于仅在光学图像上训练的标准CNN以及两个标准CNN的整体。我们进一步评估了我们的方法处理测试过程中只有一些DSM图像丢失的情况的潜力。总的来说，我们表明我们可以在测试过程中清楚地利用缺失模式的培训时间信息。

##### URL
[http://arxiv.org/abs/1709.07383](http://arxiv.org/abs/1709.07383)

##### PDF
[http://arxiv.org/pdf/1709.07383](http://arxiv.org/pdf/1709.07383)

