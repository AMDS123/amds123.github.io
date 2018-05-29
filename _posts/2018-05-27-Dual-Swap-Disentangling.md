---
layout: post
title: "Dual Swap Disentangling"
date: 2018-05-27 06:14:21
categories: arXiv_CV
tags: arXiv_CV Weakly_Supervised
author: Zunlei Feng, Xinchao Wang, Chenglong Ke, Anxiang Zeng, Dacheng Tao, Mingli Song
mathjax: true
---

* content
{:toc}

##### Abstract
Learning interpretable disentangled representations is a crucial yet challenging task. In this paper, we propose a weakly semi-supervised method, termed as Dual Swap Disentangling (DSD), for disentangling using both labeled and unlabeled data. Unlike conventional weakly supervised methods that rely on full annotations on the group of samples, we require only limited annotations on paired samples that indicate their shared attribute like the color. Our model takes the form of a dual autoencoder structure. To achieve disentangling using the labeled pairs, we follow a "encoding-swap-decoding" process, where we first swap the parts of their encodings corresponding to the shared attribute and then decode the obtained hybrid codes to reconstruct the original input pairs. For unlabeled pairs, we follow the "encoding-swap-decoding" process twice on designated encoding parts and enforce the final outputs to approximate the input pairs. By isolating parts of the encoding and swapping them back and forth, we impose the dimension-wise modularity and portability of the encodings of the unlabeled samples, which implicitly encourages disentangling under the guidance of labeled pairs. This dual swap mechanism, tailored for semi-supervised setting, turns out to be very effective. Experiments on image datasets from a wide domain show that our model yields state-of-the-art disentangling performances.

##### Abstract (translated by Google)
学习可解释的解题表达是一项至关重要而又具有挑战性的任务。在本文中，我们提出了一种弱半监督方法，称为双交换解缠（DSD），用于使用标记数据和未标记数据进行解缠。与依赖于样本组的完整注释的传统弱监督方法不同，我们只需要配对样本上的有限注释来指示其颜色等共享属性。我们的模型采用双自编码器结构的形式。为了使用带标签的对进行解开，我们遵循“编码交换解码”过程，我们首先交换对应于共享属性的编码部分，然后对获得的混合编码进行解码以重构原始输入对。对于未标记的对，我们在指定的编码部分上执行两次“编码交换解码”过程，并强制最终输出逼近输入对。通过分离部分编码并将它们来回交换，我们强加了未标记样本编码的维数模块性和可移植性，这隐含地鼓励在标记对的指导下解开。这种针对半监督设置的双重交换机制证明是非常有效的。对来自广泛领域的图像数据集进行的实验表明，我们的模型产生了最先进的解构性能。

##### URL
[http://arxiv.org/abs/1805.10583](http://arxiv.org/abs/1805.10583)

##### PDF
[http://arxiv.org/pdf/1805.10583](http://arxiv.org/pdf/1805.10583)

