---
layout: post
title: "Deep Reinforcement Learning For Sequence to Sequence Models"
date: 2018-07-20 21:02:17
categories: arXiv_CV
tags: arXiv_CV Image_Caption Attention Summarization Reinforcement_Learning Caption Survey
author: Yaser Keneshloo, Tian Shi, Naren Ramakrishnan, Chandan K. Reddy
mathjax: true
---

* content
{:toc}

##### Abstract
In recent times, sequence-to-sequence (seq2seq) models have gained a lot of popularity and provide state-of-the-art performance in a wide variety of tasks such as machine translation, headline generation, text summarization, speech to text conversion, and image caption generation. The underlying framework for all these models is usually a deep neural network comprising an encoder and a decoder. Although simple encoder-decoder models produce competitive results, many researchers have proposed additional improvements over these sequence-to-sequence models, e.g., using an attention-based model over the input, pointer-generation models, and self-attention models. However, such seq2seq models suffer from two common problems: 1) exposure bias and 2) inconsistency between train/test measurement. Recently, a completely novel point of view has emerged in addressing these two problems in seq2seq models, leveraging methods from reinforcement learning (RL). In this survey, we consider seq2seq problems from the RL point of view and provide a formulation combining the power of RL methods in decision-making with sequence-to-sequence models that enable remembering long-term memories. We present some of the most recent frameworks that combine concepts from RL and deep neural networks and explain how these two areas could benefit from each other in solving complex seq2seq tasks. Our work aims to provide insights into some of the problems that inherently arise with current approaches and how we can address them with better RL models. We also provide the source code for implementing most of the RL models discussed in this paper to support the complex task of abstractive text summarization.

##### Abstract (translated by Google)
最近，序列到序列（seq2seq）模型已经获得了很多人的欢迎，并在各种任务中提供了最先进的性能，例如机器翻译，标题生成，文本摘要，语音到文本转换。和图像标题生成。所有这些模型的基础框架通常是包括编码器和解码器的深度神经网络。尽管简单的编码器 - 解码器模型产生竞争结果，但许多研究人员已经提出了对这些序列到序列模型的额外改进，例如，使用基于注意力的模型而不是输入，指针生成模型和自我关注模型。然而，这样的seq2seq模型存在两个常见问题：1）暴露偏差和2）列车/测试测量之间的不一致。最近，在seq2seq模型中，利用强化学习（RL）的方法解决了这两个问题，出现了一种全新的观点。在本次调查中，我们从RL的角度考虑了seq2seq问题，并提供了一种结合RL决策方法的功能的配方，以及能够记忆长期记忆的序列到序列模型。我们介绍了一些最新的框架，这些框架结合了RL和深度神经网络的概念，并解释了这两个领域如何在解决复杂的seq2seq任务中相互受益。我们的工作旨在提供对当前方法中固有产生的一些问题的见解，以及我们如何使用更好的RL模型解决这些问题。我们还提供了实现本文讨论的大多数RL模型的源代码，以支持抽象文本摘要的复杂任务。

##### URL
[https://arxiv.org/abs/1805.09461](https://arxiv.org/abs/1805.09461)

##### PDF
[https://arxiv.org/pdf/1805.09461](https://arxiv.org/pdf/1805.09461)

