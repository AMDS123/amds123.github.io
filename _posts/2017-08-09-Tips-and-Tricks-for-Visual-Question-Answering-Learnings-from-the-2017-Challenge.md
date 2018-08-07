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
本文介绍了一种最先进的视觉问答模型（VQA），该模型在2017年VQA挑战赛中获得第一名。考虑到VQA的多模态特性，明确的评估协议以及潜在的实际应用，VQA对于人工智能研究具有重要意义。用于VQA的深度神经网络的性能非常依赖于体系结构和超参数的选择。为了帮助该领域的进一步研究，我们详细描述了我们的高性能，但相对简单的模型。通过对代表超过3,000小时GPU的架构和超参数的大量探索，我们确定了导致其成功的技巧和窍门，即：sigmoid输出，软训练目标，自下而上关注的图像特征，门控tanh激活，输出嵌入使用GloVe和Google Images初始化，大型小批量和训练数据的智能改组。我们会详细分析其对绩效的影响，以帮助其他人做出适当的选择。

##### URL
[https://arxiv.org/abs/1708.02711](https://arxiv.org/abs/1708.02711)

##### PDF
[https://arxiv.org/pdf/1708.02711](https://arxiv.org/pdf/1708.02711)

