---
layout: post
title: "Towards Zero-Shot Frame Semantic Parsing for Domain Scaling"
date: 2017-07-07 21:21:33
categories: arXiv_CL
tags: arXiv_CL Knowledge_Graph Knowledge Deep_Learning
author: Ankur Bapna, Gokhan Tur, Dilek Hakkani-Tur, Larry Heck
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art slot filling models for goal-oriented human/machine conversational language understanding systems rely on deep learning methods. While multi-task training of such models alleviates the need for large in-domain annotated datasets, bootstrapping a semantic parsing model for a new domain using only the semantic frame, such as the back-end API or knowledge graph schema, is still one of the holy grail tasks of language understanding for dialogue systems. This paper proposes a deep learning based approach that can utilize only the slot description in context without the need for any labeled or unlabeled in-domain examples, to quickly bootstrap a new domain. The main idea of this paper is to leverage the encoding of the slot names and descriptions within a multi-task deep learned slot filling model, to implicitly align slots across domains. The proposed approach is promising for solving the domain scaling problem and eliminating the need for any manually annotated data or explicit schema alignment. Furthermore, our experiments on multiple domains show that this approach results in significantly better slot-filling performance when compared to using only in-domain data, especially in the low data regime.

##### Abstract (translated by Google)
用于目标导向的人机对话语言理解系统的最新插槽填充模型依赖于深度学习方法。虽然这种模型的多任务训练减轻了对大型域内注释数据集的需求，但是仅使用语义框架引导新域的语义解析模型，诸如后端API或知识图模式，仍然是语言理解对话系统的圣杯任务。本文提出了一种基于深度学习的方法，可以仅使用上下文中的时隙描述，而不需要任何标记或未标记的域内示例，从而快速引导新域。本文的主要思想是利用多任务深度学习槽填充模型中的槽名称和描述的编码来隐式地跨越域来对齐槽。提出的方法有望解决域扩展问题，并消除任何手动注释数据或显式模式对齐的需要。此外，我们在多个领域的实验表明，与仅使用域内数据相比，这种方法显着改善了时隙填充性能，特别是在低数据情况下。

##### URL
[https://arxiv.org/abs/1707.02363](https://arxiv.org/abs/1707.02363)

##### PDF
[https://arxiv.org/pdf/1707.02363](https://arxiv.org/pdf/1707.02363)

