---
layout: post
title: "The Promise of Premise: Harnessing Question Premises in Visual Question Answering"
date: 2017-08-17 18:12:18
categories: arXiv_CV
tags: arXiv_CV Detection VQA
author: Aroma Mahendru, Viraj Prabhu, Akrit Mohapatra, Dhruv Batra, Stefan Lee
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we make a simple observation that questions about images often contain premises - objects and relationships implied by the question - and that reasoning about premises can help Visual Question Answering (VQA) models respond more intelligently to irrelevant or previously unseen questions. When presented with a question that is irrelevant to an image, state-of-the-art VQA models will still answer purely based on learned language biases, resulting in non-sensical or even misleading answers. We note that a visual question is irrelevant to an image if at least one of its premises is false (i.e. not depicted in the image). We leverage this observation to construct a dataset for Question Relevance Prediction and Explanation (QRPE) by searching for false premises. We train novel question relevance detection models and show that models that reason about premises consistently outperform models that do not. We also find that forcing standard VQA models to reason about premises during training can lead to improvements on tasks requiring compositional reasoning.

##### Abstract (translated by Google)
在本文中，我们简单地观察一下，关于图像的问题通常包含前提对象和问题所隐含的关系，而关于前提的推理可以帮助视觉问题回答（VQA）模型更加智能地回应无关的或以前看不见的问题。当提出一个与图像无关的问题时，最先进的VQA模型仍然会纯粹基于学习的语言偏差来回答，从而导致无意义甚至误导性的答案。我们注意到，如果一个图像中至少有一个是虚假的，那么这个图像与图像无关（即图像中没有描述）。我们利用这个观察，通过搜索错误的前提来构建一个问题相关性预测和解释（QRPE）的数据集。我们训练新颖的问题相关性检测模型，并显示模型的理由关于前提总是胜过不模型的模型。我们还发现，强迫标准的VQA模型在训练期间对场所进行推理可以导致需要组合推理的任务的改进。

##### URL
[https://arxiv.org/abs/1705.00601](https://arxiv.org/abs/1705.00601)

