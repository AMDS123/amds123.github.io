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


##### URL
[https://arxiv.org/abs/1711.00066](https://arxiv.org/abs/1711.00066)

##### PDF
[https://arxiv.org/pdf/1711.00066](https://arxiv.org/pdf/1711.00066)

