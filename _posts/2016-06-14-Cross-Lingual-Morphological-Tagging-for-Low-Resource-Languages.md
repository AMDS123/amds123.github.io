---
layout: post
title: "Cross-Lingual Morphological Tagging for Low-Resource Languages"
date: 2016-06-14 09:43:36
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Jan Buys, Jan A. Botha
mathjax: true
---

* content
{:toc}

##### Abstract
Morphologically rich languages often lack the annotated linguistic resources required to develop accurate natural language processing tools. We propose models suitable for training morphological taggers with rich tagsets for low-resource languages without using direct supervision. Our approach extends existing approaches of projecting part-of-speech tags across languages, using bitext to infer constraints on the possible tags for a given word type or token. We propose a tagging model using Wsabie, a discriminative embedding-based model with rank-based learning. In our evaluation on 11 languages, on average this model performs on par with a baseline weakly-supervised HMM, while being more scalable. Multilingual experiments show that the method performs best when projecting between related language pairs. Despite the inherently lossy projection, we show that the morphological tags predicted by our models improve the downstream performance of a parser by +0.6 LAS on average.

##### Abstract (translated by Google)
形态丰富的语言往往缺乏开发准确的自然语言处理工具所需的注释语言资源。我们提出了适合训练具有丰富的标记集的形态标记器的模型，用于低资源语言而不使用直接监督。我们的方法扩展了跨语言投射词性标签的现有方法，使用bitext来推断对于给定词类型或标记的可能标签的约束。我们提出了一个标签模型使用Wsabie，基于排名的学习歧视嵌入为基础的模型。在我们对11种语言的评估中，平均而言，这个模型与基线弱监督HMM相当，而且更具可扩展性。多语言实验表明，在相关语言对之间进行投影时，该方法效果最好。尽管内在有损的投影，我们表明，我们的模型预测的形态标签平均提高了解析器的下游性能+ 0.6 LAS。

##### URL
[https://arxiv.org/abs/1606.04279](https://arxiv.org/abs/1606.04279)

##### PDF
[https://arxiv.org/pdf/1606.04279](https://arxiv.org/pdf/1606.04279)

