---
layout: post
title: "One-shot Face Recognition by Promoting Underrepresented Classes"
date: 2017-07-18 11:51:13
categories: arXiv_CV
tags: arXiv_CV Face CNN Classification Recognition Face_Recognition
author: Yandong Guo, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
We study in this paper the problem of one-shot face recognition, with the goal to build a large-scale face recognizer capable of recognizing a substantial number of persons. Given that for face recognition one can leverage a large-scale dataset to learn good face representation, our study shows that the poor generalization ability of the one-shot classes is mainly caused by the data imbalance problem, which cannot be effectively addressed by multinomial logistic regression that is widely used as the final classification layer in convolutional neural networks. To solve this problem, we propose a novel supervision signal called underrepresented-classes promotion (UP) loss term, which aligns the norms of the weight vectors of the one-shot classes (a.k.a. underrepresented-classes) to those of the normal classes. In addition to the original cross entropy loss, this new loss term effectively promotes the underrepresented classes in the learned model and leads to a remarkable improvement in face recognition performance. The experimental results on a benchmark dataset of $21,000$ persons show that the new loss term significantly helps improve the recognition coverage rate from $25.65\%$ to $77.48\%$ at the precision of $99\%$ for underrepresented classes, while still keeps an overall top-1 accuracy of $99.8\%$ for normal classes.

##### Abstract (translated by Google)
本文研究了一次性人脸识别问题，目标是建立一个能够识别大量人脸的大型人脸识别器。考虑到人脸识别可以利用大规模的数据集来学习好的人脸表征，本文的研究表明，一次类的泛化能力差主要是由数据不平衡问题引起的，多分类逻辑不能有效解决在卷积神经网络中被广泛用作最后的分类层。为了解决这个问题，我们提出了一种称为代表性不足（UP）损失项的新型监督信号，它将一次课（也称为代表性不足班）的权重向量的规范与正常类的权重向量进行了对齐。除了原有的交叉熵损失之外，这个新的损失项有效地促进了学习模型中代表性不足的类，并导致了人脸识别性能的显着提高。在21,000美元的基准数据集上的实验结果表明，新的损失期限显着地帮助将精确到99美元/％的认可覆盖率从25.65美元％提高到77.48美元美元，但是仍然保持对于普通班级来说，99.8 \％$的总体顶级精度为1。

##### URL
[https://arxiv.org/abs/1707.05574](https://arxiv.org/abs/1707.05574)

##### PDF
[https://arxiv.org/pdf/1707.05574](https://arxiv.org/pdf/1707.05574)

