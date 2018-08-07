---
layout: post
title: "Language Model Supervision for Handwriting Recognition Model Adaptation"
date: 2018-08-04 04:27:05
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning Language_Model Prediction Recognition
author: Chris Tensmeyer, Curtis Wigington, Brian Davis, Seth Stewart, Tony Martinez, William Barrett
mathjax: true
---

* content
{:toc}

##### Abstract
Training state-of-the-art offline handwriting recognition (HWR) models requires large labeled datasets, but unfortunately such datasets are not available in all languages and domains due to the high cost of manual labeling.We address this problem by showing how high resource languages can be leveraged to help train models for low resource languages.We propose a transfer learning methodology where we adapt HWR models trained on a source language to a target language that uses the same writing script.This methodology only requires labeled data in the source language, unlabeled data in the target language, and a language model of the target language. The language model is used in a bootstrapping fashion to refine predictions in the target language for use as ground truth in training the model.Using this approach we demonstrate improved transferability among French, English, and Spanish languages using both historical and modern handwriting datasets. In the best case, transferring with the proposed methodology results in character error rates nearly as good as full supervised training.

##### Abstract (translated by Google)
培训最先进的离线手写识别（HWR）模型需要大型标记数据集，但不幸的是，由于手动标记的高成本，这些数据集并非在所有语言和域中都可用。我们通过显示资源有多高来解决这个问题语言可用于帮助训练低资源语言的模型。我们提出了一种转移学习方法，我们将使用源语言训练的HWR模型应用于使用相同写入脚本的目标语言。此方法仅需要源语言中的标记数据，目标语言中的未标记数据以及目标语言的语言模型。语言模型以自举方式用于改进目标语言中的预测，以用作训练模型的基本事实。使用此方法，我们使用历史和现代手写数据集证明了法语，英语和西班牙语语言之间的可转换性。在最好的情况下，使用所提出的方法进行转换会导致字符错误率几乎与完全监督培训一样好。

##### URL
[https://arxiv.org/abs/1808.01423](https://arxiv.org/abs/1808.01423)

##### PDF
[https://arxiv.org/pdf/1808.01423](https://arxiv.org/pdf/1808.01423)

