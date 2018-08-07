---
layout: post
title: "Fraternal Dropout"
date: 2018-03-28 15:50:58
categories: arXiv_CV
tags: arXiv_CV Image_Caption Regularization Caption Inference RNN Language_Model Prediction
author: Konrad Zolna, Devansh Arpit, Dendi Suhubdy, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks (RNNs) are important class of architectures among neural networks useful for language modeling and sequential prediction. However, optimizing RNNs is known to be harder compared to feed-forward neural networks. A number of techniques have been proposed in literature to address this problem. In this paper we propose a simple technique called fraternal dropout that takes advantage of dropout to achieve this goal. Specifically, we propose to train two identical copies of an RNN (that share parameters) with different dropout masks while minimizing the difference between their (pre-softmax) predictions. In this way our regularization encourages the representations of RNNs to be invariant to dropout mask, thus being robust. We show that our regularization term is upper bounded by the expectation-linear dropout objective which has been shown to address the gap due to the difference between the train and inference phases of dropout. We evaluate our model and achieve state-of-the-art results in sequence modeling tasks on two benchmark datasets - Penn Treebank and Wikitext-2. We also show that our approach leads to performance improvement by a significant margin in image captioning (Microsoft COCO) and semi-supervised (CIFAR-10) tasks.

##### Abstract (translated by Google)
递归神经网络（RNN）是用于语言建模和顺序预测的神经网络中的重要架构类。然而，与前馈神经网络相比，已知优化RNN更难。在文献中已经提出了许多技术来解决这个问题。在本文中，我们提出了一种称为兄弟辍学的简单技术，利用辍学来实现这一目标。具体而言，我们建议使用不同的丢失掩码训练两个相同的RNN（共享参数）副本，同时最小化它们（pre-softmax）预测之间的差异。通过这种方式，我们的正则化鼓励RNN的表示对于丢失掩码是不变的，因此是稳健的。我们证明了我们的正则化项是由期望 - 线性辍学目标所界定的，该目标已被证明可以解决由于辍学的列车和推理阶段之间的差异导致的差距。我们评估我们的模型，并在两个基准数据集--Penn Treebank和Wikitext-2上的序列建模任务中获得最先进的结果。我们还表明，我们的方法可以在图像字幕（Microsoft COCO）和半监督（CIFAR-10）任务中显着提高性能。

##### URL
[https://arxiv.org/abs/1711.00066](https://arxiv.org/abs/1711.00066)

##### PDF
[https://arxiv.org/pdf/1711.00066](https://arxiv.org/pdf/1711.00066)

