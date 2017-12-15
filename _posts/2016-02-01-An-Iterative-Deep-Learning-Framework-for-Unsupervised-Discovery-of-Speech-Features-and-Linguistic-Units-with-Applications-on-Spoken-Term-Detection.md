---
layout: post
title: "An Iterative Deep Learning Framework for Unsupervised Discovery of Speech Features and Linguistic Units with Applications on Spoken Term Detection"
date: 2016-02-01 08:37:56
categories: arXiv_SD
tags: arXiv_SD GAN Deep_Learning Detection
author: Cheng-Tao Chung, Cheng-Yu Tsai, Hsiang-Hung Lu, Chia-Hsiang Liu, Hung-yi Lee, Lin-shan Lee
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we aim to discover high quality speech features and linguistic units directly from unlabeled speech data in a zero resource scenario. The results are evaluated using the metrics and corpora proposed in the Zero Resource Speech Challenge organized at Interspeech 2015. A Multi-layered Acoustic Tokenizer (MAT) was proposed for automatic discovery of multiple sets of acoustic tokens from the given corpus. Each acoustic token set is specified by a set of hyperparameters that describe the model configuration. These sets of acoustic tokens carry different characteristics fof the given corpus and the language behind, thus can be mutually reinforced. The multiple sets of token labels are then used as the targets of a Multi-target Deep Neural Network (MDNN) trained on low-level acoustic features. Bottleneck features extracted from the MDNN are then used as the feedback input to the MAT and the MDNN itself in the next iteration. We call this iterative deep learning framework the Multi-layered Acoustic Tokenizing Deep Neural Network (MAT-DNN), which generates both high quality speech features for the Track 1 of the Challenge and acoustic tokens for the Track 2 of the Challenge. In addition, we performed extra experiments on the same corpora on the application of query-by-example spoken term detection. The experimental results showed the iterative deep learning framework of MAT-DNN improved the detection performance due to better underlying speech features and acoustic tokens.

##### Abstract (translated by Google)
在这项工作中，我们的目标是在零资源情况下直接从无标签语音数据中发现高质量的语音特征和语言单元。利用2015年Interspeech组织的零资源演讲挑战中提出的度量和语料对结果进行评估。提出了一种多层声学标记器（MAT），用于自动发现来自给定语料库的多组声学标记。每个声学标记集由一组描述模型配置的超参数指定。这些声学标记集具有给定语料库和后面语言的不同特征，因此可以相互加强。然后将多组令牌标签用作在低级声学特征上训练的多目标深度神经网络（MDNN）的目标。然后，将从MDNN提取的瓶颈特征用作MAT和MDNN本身在下一次迭代中的反馈输入。我们把这个迭代的深度学习框架称为MAT-DNN多层声学令牌化深度神经网络（MAT-DNN），它为挑战的第一轨道生成高质量的语音特征，为挑战的第二轨道生成声音的记号。另外，我们在相同的语料库上进行了额外的实验，以应用通过例子查询口头词语检测。实验结果表明，由于更好的底层语音特征和声音令牌，MAT-DNN的迭代深度学习框架改善了检测性能。

##### URL
[https://arxiv.org/abs/1602.00426](https://arxiv.org/abs/1602.00426)

##### PDF
[https://arxiv.org/pdf/1602.00426](https://arxiv.org/pdf/1602.00426)

