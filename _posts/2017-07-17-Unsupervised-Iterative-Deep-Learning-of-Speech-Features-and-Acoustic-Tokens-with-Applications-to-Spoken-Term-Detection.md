---
layout: post
title: "Unsupervised Iterative Deep Learning of Speech Features and Acoustic Tokens with Applications to Spoken Term Detection"
date: 2017-07-17 10:20:15
categories: arXiv_CL
tags: arXiv_CL GAN Deep_Learning Detection
author: Cheng-Tao Chung, Cheng-Yu Tsai, Chia-Hsiang Liu, Lin-Shan Lee
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we aim to automatically discover high quality frame-level speech features and acoustic tokens directly from unlabeled speech data. A Multi-granular Acoustic Tokenizer (MAT) was proposed for automatic discovery of multiple sets of acoustic tokens from the given corpus. Each acoustic token set is specified by a set of hyperparameters describing the model configuration. These different sets of acoustic tokens carry different characteristics for the given corpus and the language behind, thus can be mutually reinforced. The multiple sets of token labels are then used as the targets of a Multi-target Deep Neural Network (MDNN) trained on frame-level acoustic features. Bottleneck features extracted from the MDNN are then used as the feedback input to the MAT and the MDNN itself in the next iteration. The multi-granular acoustic token sets and the frame-level speech features can be iteratively optimized in the iterative deep learning framework. We call this framework the Multi-granular Acoustic Tokenizing Deep Neural Network (MATDNN). The results were evaluated using the metrics and corpora defined in the Zero Resource Speech Challenge organized at Interspeech 2015, and improved performance was obtained with a set of experiments of query-by-example spoken term detection on the same corpora. Visualization for the discovered tokens against the English phonemes was also shown.

##### Abstract (translated by Google)
在本文中，我们的目标是直接从未标记的语音数据中直接自动发现高质量的帧级语音特征和声学标记。提出了一种多粒度声音标记器（MAT），用于自动发现给定语料库中的多组声学标记。每个声学标记集由描述模型配置的一组超参数指定。这些不同的声学标记集对于给定的语料库和背后的语言具有不同的特征，因此可以相互加强。然后将多组令牌标签用作在帧级声学特征上训练的多目标深度神经网络（MDNN）的目标。然后，将从MDNN提取的瓶颈特征用作MAT和MDNN本身在下一次迭代中的反馈输入。可以在迭代深度学习框架中迭代地优化多粒度听觉令牌集和帧级语音特征。我们称这个框架为多粒度声音令牌深度神经网络（MATDNN）。使用在Interspeech 2015组织的零资源语音挑战中定义的度量和语料对结果进行评估，并且通过在相同语料上的一组实例查询示例口头词语检测来获得改进的性能。还显示了发现的令牌对英文音素的可视化。

##### URL
[https://arxiv.org/abs/1707.05315](https://arxiv.org/abs/1707.05315)

##### PDF
[https://arxiv.org/pdf/1707.05315](https://arxiv.org/pdf/1707.05315)

