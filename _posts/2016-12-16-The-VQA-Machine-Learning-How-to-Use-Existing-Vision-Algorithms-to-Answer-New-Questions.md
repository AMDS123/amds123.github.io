---
layout: post
title: "The VQA-Machine: Learning How to Use Existing Vision Algorithms to Answer New Questions"
date: 2016-12-16 07:07:25
categories: arXiv_CV
tags: arXiv_CV Segmentation Detection VQA
author: Peng Wang, Qi Wu, Chunhua Shen, Anton van den Hengel
mathjax: true
---

* content
{:toc}

##### Abstract
One of the most intriguing features of the Visual Question Answering (VQA) challenge is the unpredictability of the questions. Extracting the information required to answer them demands a variety of image operations from detection and counting, to segmentation and reconstruction. To train a method to perform even one of these operations accurately from {image,question,answer} tuples would be challenging, but to aim to achieve them all with a limited set of such training data seems ambitious at best. We propose here instead a more general and scalable approach which exploits the fact that very good methods to achieve these operations already exist, and thus do not need to be trained. Our method thus learns how to exploit a set of external off-the-shelf algorithms to achieve its goal, an approach that has something in common with the Neural Turing Machine. The core of our proposed method is a new co-attention model. In addition, the proposed approach generates human-readable reasons for its decision, and can still be trained end-to-end without ground truth reasons being given. We demonstrate the effectiveness on two publicly available datasets, Visual Genome and VQA, and show that it produces the state-of-the-art results in both cases.

##### Abstract (translated by Google)
视觉问答（VQA）挑战中最有趣的特征之一就是问题的不可预测性。提取回答所需的信息需要从检测和计数到分割和重建的各种图像操作。为了训练一种从{图像，问题，答案}元素准确执行这些操作中的一种的方法将是具有挑战性的，但是为了实现这些操作，仅仅通过有限的这样的训练数据来实现这些操作似乎充满了雄心。我们在这里提出一个更普遍和可扩展的方法，利用这个事实，即已经存在很好的方法来实现这些操作，因此不需要训练。因此，我们的方法学习如何利用一套外部的现成算法来实现其目标，这种方法与神经图灵机有一些共同点。我们提出的方法的核心是一个新的共同关注模型。另外，所提出的方法为其决策产生了人为可读的原因，并且仍然可以在没有给出实际理由的情况下端对端地进行训练。我们在两个公开可用的数据集，Visual Genome和VQA上展示了它的有效性，并显示它在这两种情况下都产生了最先进的结果。

##### URL
[https://arxiv.org/abs/1612.05386](https://arxiv.org/abs/1612.05386)

##### PDF
[https://arxiv.org/pdf/1612.05386](https://arxiv.org/pdf/1612.05386)

