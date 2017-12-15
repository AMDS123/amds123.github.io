---
layout: post
title: "Recurrent and Contextual Models for Visual Question Answering"
date: 2017-03-23 15:57:23
categories: arXiv_SD
tags: arXiv_SD Attention Text_Generation RNN VQA
author: Abhijit Sharang, Eric Lau
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a series of recurrent and contextual neural network models for multiple choice visual question answering on the Visual7W dataset. Motivated by divergent trends in model complexities in the literature, we explore the balance between model expressiveness and simplicity by studying incrementally more complex architectures. We start with LSTM-encoding of input questions and answers; build on this with context generation by LSTM-encodings of neural image and question representations and attention over images; and evaluate the diversity and predictive power of our models and the ensemble thereof. All models are evaluated against a simple baseline inspired by the current state-of-the-art, consisting of involving simple concatenation of bag-of-words and CNN representations for the text and images, respectively. Generally, we observe marked variation in image-reasoning performance between our models not obvious from their overall performance, as well as evidence of dataset bias. Our standalone models achieve accuracies up to $64.6\%$, while the ensemble of all models achieves the best accuracy of $66.67\%$, within $0.5\%$ of the current state-of-the-art for Visual7W.

##### Abstract (translated by Google)
我们针对Visual7W数据集中的多选题视觉问题提出了一系列复发和上下文的神经网络模型。受到文献中模型复杂性趋势的影响，我们通过逐步研究更复杂的体系结构来探索模型表达性与简单性之间的平衡。我们从输入问题和答案的LSTM编码开始;在上下文生成的基础上，通过LSTM编码神经图像和问题表示以及对图像的关注;并评估我们的模型及其集合的多样性和预测能力。所有模型都是基于当前最新技术的简单基线进行评估的，其中包括文本和图像的简单拼接以及文本和图像的CNN表示。一般来说，我们观察到我们的模型之间的图像推理性能的显着变化从其整体性能不明显，以及数据集偏差的证据。我们的独立模型可达到$ 64.6 \％$的准确度，而所有模型的合奏达到$ 66.67 \％$的最佳精度，在目前Visual7W的最新技术水平的$ 0.5 \％$以内。

##### URL
[https://arxiv.org/abs/1703.08120](https://arxiv.org/abs/1703.08120)

##### PDF
[https://arxiv.org/pdf/1703.08120](https://arxiv.org/pdf/1703.08120)

