---
layout: post
title: "Unsupervised Learning of Video Representations using LSTMs"
date: 2016-01-04 00:42:07
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN RNN Classification Recognition
author: Nitish Srivastava, Elman Mansimov, Ruslan Salakhutdinov
mathjax: true
---

* content
{:toc}

##### Abstract
We use multilayer Long Short Term Memory (LSTM) networks to learn representations of video sequences. Our model uses an encoder LSTM to map an input sequence into a fixed length representation. This representation is decoded using single or multiple decoder LSTMs to perform different tasks, such as reconstructing the input sequence, or predicting the future sequence. We experiment with two kinds of input sequences - patches of image pixels and high-level representations ("percepts") of video frames extracted using a pretrained convolutional net. We explore different design choices such as whether the decoder LSTMs should condition on the generated output. We analyze the outputs of the model qualitatively to see how well the model can extrapolate the learned video representation into the future and into the past. We try to visualize and interpret the learned features. We stress test the model by running it on longer time scales and on out-of-domain data. We further evaluate the representations by finetuning them for a supervised learning problem - human action recognition on the UCF-101 and HMDB-51 datasets. We show that the representations help improve classification accuracy, especially when there are only a few training examples. Even models pretrained on unrelated datasets (300 hours of YouTube videos) can help action recognition performance.

##### Abstract (translated by Google)
我们使用多层长短期记忆（LSTM）网络来学习视频序列的表示。我们的模型使用编码器LSTM将输入序列映射为固定长度的表示。使用单个或多个解码器LSTM来解码该表示以执行不同的任务，诸如重建输入序列或预测未来序列。我们试验了两种输入序列 - 使用预训练卷积网提取的视频帧的图像像素块和高级表示（“感知”）。我们研究不同的设计选择，例如解码器LSTM是否应该对生成的输出进行调节。我们定性地分析模型的输出，看看模型能够将学习的视频表示推断到未来和过去。我们尝试想象和解释学习的功能。我们强调通过在更长的时间范围内运行并在域外数据上测试模型。我们进一步评估表示，通过微调它们的监督学习问题 - 在UCF-101和HMDB-51数据集上的人类行为识别。我们表明，表示有助于提高分类的准确性，特别是当只有少数训练的例子。即使模型pretrained在不相关的数据集（YouTube视频300小时）可以帮助行为识别性能。

##### URL
[https://arxiv.org/abs/1502.04681](https://arxiv.org/abs/1502.04681)

##### PDF
[https://arxiv.org/pdf/1502.04681](https://arxiv.org/pdf/1502.04681)

