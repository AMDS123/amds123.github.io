---
layout: post
title: "Tips and Tricks for Visual Question Answering: Learnings from the 2017 Challenge"
date: 2017-08-09 04:19:42
categories: arXiv_CV
tags: arXiv_CV QA Attention Embedding VQA
author: Damien Teney, Peter Anderson, Xiaodong He, Anton van den Hengel
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a state-of-the-art model for visual question answering (VQA), which won the first place in the 2017 VQA Challenge. VQA is a task of significant importance for research in artificial intelligence, given its multimodal nature, clear evaluation protocol, and potential real-world applications. The performance of deep neural networks for VQA is very dependent on choices of architectures and hyperparameters. To help further research in the area, we describe in detail our high-performing, though relatively simple model. Through a massive exploration of architectures and hyperparameters representing more than 3,000 GPU-hours, we identified tips and tricks that lead to its success, namely: sigmoid outputs, soft training targets, image features from bottom-up attention, gated tanh activations, output embeddings initialized using GloVe and Google Images, large mini-batches, and smart shuffling of training data. We provide a detailed analysis of their impact on performance to assist others in making an appropriate selection.

##### Abstract (translated by Google)
本文提出了视觉问答（VQA）的最新模型，该模型在2017年VQA挑战赛中获得第一名。 VQA是人工智能研究中具有重要意义的任务，因为它具有多模式性质，明确的评估协议和潜在的实际应用。深度神经网络对于VQA的性能非常依赖于架构和超参数的选择。为了帮助进一步研究该领域，我们详细描述了我们的高性能，虽然相对简单的模型。通过大量的体系结构和超过3,000 GPU时间的超参数的探索，我们发现了一些可以使它成功的技巧和诀窍，即：S形输出，软训练目标，来自自下而上注意力的图像特征，门控激励，输出嵌入使用GloVe和Google Images进行初始化，大型小批量，以及训练数据的智能混洗。我们详细分析了他们对绩效的影响，以帮助他人做出适当的选择。

##### URL
[https://arxiv.org/abs/1708.02711](https://arxiv.org/abs/1708.02711)

##### PDF
[https://arxiv.org/pdf/1708.02711](https://arxiv.org/pdf/1708.02711)

