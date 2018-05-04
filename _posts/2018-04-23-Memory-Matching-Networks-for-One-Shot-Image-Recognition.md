---
layout: post
title: "Memory Matching Networks for One-Shot Image Recognition"
date: 2018-04-23 08:31:26
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Inference Recognition
author: Qi Cai, Yingwei Pan, Ting Yao, Chenggang Yan, Tao Mei
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce the new ideas of augmenting Convolutional Neural Networks (CNNs) with Memory and learning to learn the network parameters for the unlabelled images on the fly in one-shot learning. Specifically, we present Memory Matching Networks (MM-Net) --- a novel deep architecture that explores the training procedure, following the philosophy that training and test conditions must match. Technically, MM-Net writes the features of a set of labelled images (support set) into memory and reads from memory when performing inference to holistically leverage the knowledge in the set. Meanwhile, a Contextual Learner employs the memory slots in a sequential manner to predict the parameters of CNNs for unlabelled images. The whole architecture is trained by once showing only a few examples per class and switching the learning from minibatch to minibatch, which is tailored for one-shot learning when presented with a few examples of new categories at test time. Unlike the conventional one-shot learning approaches, our MM-Net could output one unified model irrespective of the number of shots and categories. Extensive experiments are conducted on two public datasets, i.e., Omniglot and \emph{mini}ImageNet, and superior results are reported when compared to state-of-the-art approaches. More remarkably, our MM-Net improves one-shot accuracy on Omniglot from 98.95% to 99.28% and from 49.21% to 53.37% on \emph{mini}ImageNet.

##### Abstract (translated by Google)
在本文中，我们介绍了利用记忆增强卷积神经网络（CNN）和学习在一次学习中动态学习未标记图像的网络参数的新思想。具体而言，我们提出了记忆匹配网络（MM-Net）---一种探索训练过程的新型深层架构，遵循训练和测试条件必须匹配的原则。从技术上讲，MM-Net将一组标记图像（支持集）的特征写入内存，并在执行推理时从内存中读取，从而全面利用集合中的知识。同时，上下文学习者以顺序方式使用存储器时隙来预测未标记图像的CNN的参数。整个架构通过一次仅显示每个类的几个示例并将学习从小批次切换到小批次来进行培训，当在测试时间提供几个新类别的示例时，该小批次适用于单次学习。与传统的一次学习方法不同，我们的MM-Net可以输出一个统一的模型，而不考虑镜头和类别的数量。对两个公共数据集进行了广泛的实验，即Omniglot和\ emph {mini} ImageNet，并且与最先进的方法进行比较时报告了优异的结果。更为显着的是，我们的MM-Net将Omniglot的一次性准确度从\ emph {mini} ImageNet上的98.95％提高到99.28％，从49.21％提高到53.37％。

##### URL
[https://arxiv.org/abs/1804.08281](https://arxiv.org/abs/1804.08281)

##### PDF
[https://arxiv.org/pdf/1804.08281](https://arxiv.org/pdf/1804.08281)

