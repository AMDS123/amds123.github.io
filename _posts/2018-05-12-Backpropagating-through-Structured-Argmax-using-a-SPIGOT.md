---
layout: post
title: "Backpropagating through Structured Argmax using a SPIGOT"
date: 2018-05-12 05:27:45
categories: arXiv_CL
tags: arXiv_CL Sentiment Attention Sentiment_Classification Reinforcement_Learning Optimization Inference Classification Prediction
author: Hao Peng, Sam Thomson, Noah A. Smith
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce the structured projection of intermediate gradients optimization technique (SPIGOT), a new method for backpropagating through neural networks that include hard-decision structured predictions (e.g., parsing) in intermediate layers. SPIGOT requires no marginal inference, unlike structured attention networks (Kim et al., 2017) and some reinforcement learning-inspired solutions (Yogatama et al., 2017). Like so-called straight-through estimators (Hinton, 2012), SPIGOT defines gradient-like quantities associated with intermediate nondifferentiable operations, allowing backpropagation before and after them; SPIGOT's proxy aims to ensure that, after a parameter update, the intermediate structure will remain well-formed. We experiment on two structured NLP pipelines: syntactic-then-semantic dependency parsing, and semantic parsing followed by sentiment classification. We show that training with SPIGOT leads to a larger improvement on the downstream task than a modularly-trained pipeline, the straight-through estimator, and structured attention, reaching a new state of the art on semantic dependency parsing.

##### Abstract (translated by Google)
我们介绍了中间梯度优化技术（SPIGOT）的结构化投影，SPIGOT是一种通过神经网络反向传播的新方法，包括中间层的硬判决结构预测（例如解析）。 SPIGOT不需要边际推理，这与结构化关注网络（Kim et al。，2017）和一些强化学习灵感解决方案（Yogatama et al。，2017）不同。像所谓的直通式估算器一样（Hinton，2012），SPIGOT定义了与中间不可微操作相关的梯度式量，允许在它们之前和之后的反向传播; SPIGOT的代理旨在确保在参数更新后，中间结构将保持良好状态。我们在两个结构化的NLP管道上进行实验：句法 - 然后 - 语义依赖关系解析，以及语义解析，然后是情感分类。我们表明，使用SPIGOT进行培训会导致对模块化训练管道，直通估计器和结构化注意力的下游任务进行更大改进，从而在语义依赖分析方面达到最新技术水平。

##### URL
[https://arxiv.org/abs/1805.04658](https://arxiv.org/abs/1805.04658)

##### PDF
[https://arxiv.org/pdf/1805.04658](https://arxiv.org/pdf/1805.04658)

