---
layout: post
title: "Data Dropout: Optimizing Training Data for Convolutional Neural Networks"
date: 2018-09-01 14:24:36
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification Deep_Learning
author: Tianyang Wang, Jun Huan, Bo Li
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning models learn to fit training data while they are highly expected to generalize well to testing data. Most works aim at finding such models by creatively designing architectures and fine-tuning parameters. To adapt to particular tasks, hand-crafted information such as image prior has also been incorporated into end-to-end learning. However, very little progress has been made on investigating how an individual training sample will influence the generalization ability of a model. In other words, to achieve high generalization accuracy, do we really need all the samples in a training dataset? In this paper, we demonstrate that deep learning models such as convolutional neural networks may not favor all training samples, and generalization accuracy can be further improved by dropping those unfavorable samples. Specifically, the influence of removing a training sample is quantifiable, and we propose a Two-Round Training approach, aiming to achieve higher generalization accuracy. We locate unfavorable samples after the first round of training, and then retrain the model from scratch with the reduced training dataset in the second round. Since our approach is essentially different from fine-tuning or further training, the computational cost should not be a concern. Our extensive experimental results indicate that, with identical settings, the proposed approach can boost performance of the well-known networks on both high-level computer vision problems such as image classification, and low-level vision problems such as image denoising.

##### Abstract (translated by Google)
深度学习模型学习如何适应训练数据，同时期望它们能够很好地概括为测试数据。大多数工作旨在通过创造性地设计架构和微调参数来找到这样的模型。为了适应特定任务，手工制作的信息（如图像优先）也被纳入端到端学习中。然而，在研究个体训练样本如何影响模型的泛化能力方面，进展甚微。换句话说，为了实现高泛化精度，我们真的需要训练数据集中的所有样本吗？在本文中，我们证明了诸如卷积神经网络之类的深度学习模型可能不支持所有训练样本，并且通过丢弃那些不利的样本可以进一步提高泛化精度。具体而言，删除训练样本的影响是可以量化的，我们提出了一种双轮训练方法，旨在实现更高的泛化精度。我们在第一轮训练后找到不利的样本，然后在第二轮中使用减少的训练数据集从头开始重新训练模型。由于我们的方法与微调或进一步培训本质上不同，因此计算成本不应成为问题。我们广泛的实验结果表明，采用相同的设置，所提出的方法可以提高知名网络在高级计算机视觉问题（如图像分类）和低级视觉问题（如图像去噪）方面的性能。

##### URL
[http://arxiv.org/abs/1809.00193](http://arxiv.org/abs/1809.00193)

##### PDF
[http://arxiv.org/pdf/1809.00193](http://arxiv.org/pdf/1809.00193)

