---
layout: post
title: "Controlling Personality-Based Stylistic Variation with Neural Natural Language Generators"
date: 2018-05-22 02:07:32
categories: arXiv_CL
tags: arXiv_CL
author: Shereen Oraby, Lena Reed, Shubhangi Tandon, T. S. Sharath, Stephanie Lukin, Marilyn Walker
mathjax: true
---

* content
{:toc}

##### Abstract
Natural language generators for task-oriented dialogue must effectively realize system dialogue actions and their associated semantics. In many applications, it is also desirable for generators to control the style of an utterance. To date, work on task-oriented neural generation has primarily focused on semantic fidelity rather than achieving stylistic goals, while work on style has been done in contexts where it is difficult to measure content preservation. Here we present three different sequence-to-sequence models and carefully test how well they disentangle content and style. We use a statistical generator, Personage, to synthesize a new corpus of over 88,000 restaurant domain utterances whose style varies according to models of personality, giving us total control over both the semantic content and the stylistic variation in the training data. We then vary the amount of explicit stylistic supervision given to the three models. We show that our most explicit model can simultaneously achieve high fidelity to both semantic and stylistic goals: this model adds a context vector of 36 stylistic parameters as input to the hidden state of the encoder at each time step, showing the benefits of explicit stylistic supervision, even when the amount of training data is large.

##### Abstract (translated by Google)
用于任务导向对话的自然语言生成器必须有效地实现系统对话操作及其相关语义。在许多应用中，发电机也希望控制话语的风格。迄今为止，面向任务的神经生成工作主要侧重于语义保真度而不是实现文体目标，而风格的工作则是在难以衡量内容保存的情境中完成的。在这里，我们给出三种不同的序列 - 序列模型，并仔细测试他们如何很好地解开内容和风格。我们使用统计生成器Personage来合成一个超过88,000个餐厅领域话语的新语料库，其风格因人格模型而异，使我们能够全面控制训练数据中的语义内容和文体变异。然后我们改变对这三种模型的显式文体监督。我们表明，我们最明确的模型可以同时实现语义和文体目标的高保真度：该模型在每个时间步骤添加36个样式参数的上下文向量作为编码器隐藏状态的输入，显示明确的文体监督的好处即使训练数据量很大。

##### URL
[https://arxiv.org/abs/1805.08352](https://arxiv.org/abs/1805.08352)

##### PDF
[https://arxiv.org/pdf/1805.08352](https://arxiv.org/pdf/1805.08352)

