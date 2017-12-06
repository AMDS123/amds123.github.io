---
layout: post
title: "Fraternal Dropout"
date: 2017-11-16 16:40:34
categories: arXiv_CV
tags: arXiv_CV Image_Caption Regularization Caption RNN
author: Konrad Zolna, Devansh Arpit, Dendi Suhubdy, Yoshua Bengio
---

* content
{:toc}

##### Abstract
Recurrent neural networks (RNNs) are important class of architectures among neural networks useful for language modeling and sequential prediction. However, optimizing RNNs is known to be harder compared to feed-forward neural networks. A number of techniques have been proposed in literature to address this problem. In this paper we propose a simple technique called fraternal dropout that takes advantage of dropout to achieve this goal. Specifically, we propose to train two identical copies of an RNN (that share parameters) with different dropout masks while minimizing the difference between their (pre-softmax) predictions. In this way our regularization encourages the representations of RNNs to be invariant to dropout mask, thus being robust. We show that our regularization term is upper bounded by the expectation-linear dropout objective which has been shown to address the gap due to the difference between the train and inference phases of dropout. We evaluate our model and achieve state-of-the-art results in sequence modeling tasks on two benchmark datasets - Penn Treebank and Wikitext-2. We also show that our approach leads to performance improvement by a significant margin in image captioning (Microsoft COCO) and semi-supervised (CIFAR-10) tasks.

##### Abstract (translated by Google)
递归神经网络（RNN）是用于语言建模和顺序预测的神经网络中重要的一类架构。然而，与前馈神经网络相比，优化RNN是困难的。文献中提出了许多技术来解决这个问题。在本文中，我们提出了一个简单的技术，称为兄弟辍学，利用退学来实现这一目标。具体来说，我们建议训练两个相同的副本RNN（共享参数）与不同的失落面具，同时最小化他们（pre-softmax）预测之间的差异。通过这种方式，我们的正则化鼓励RNN的表示对于丢失掩码是不变的，因此是鲁棒的。我们证明了我们的正则化项是由期望 - 线性退出目标所限定的，这个目标已经被证明是为了解决由于退出的列车和推理阶段之间的差异而导致的差距。我们评估我们的模型，并在两个基准数据集Penn Treebank和Wikitext-2上实现序列建模任务中的最新结果。我们还表明，我们的方法导致图像字幕（Microsoft COCO）和半监督（CIFAR-10）任务的性能提高很大。

##### URL
[https://arxiv.org/abs/1711.00066](https://arxiv.org/abs/1711.00066)

