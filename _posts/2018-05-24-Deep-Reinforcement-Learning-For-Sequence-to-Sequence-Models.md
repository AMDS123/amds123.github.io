---
layout: post
title: "Deep Reinforcement Learning For Sequence to Sequence Models"
date: 2018-05-24 00:21:34
categories: arXiv_CV
tags: arXiv_CV Image_Caption Attention Summarization Reinforcement_Learning Caption
author: Yaser Keneshloo, Tian Shi, Chandan K. Reddy, Naren Ramakrishnan
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, sequence-to-sequence (seq2seq) models are used in a variety of tasks from machine translation, headline generation, text summarization, speech to text, to image caption generation. The underlying framework of all these models are usually a deep neural network which contains an encoder and decoder. The encoder processes the input data and a decoder receives the output of the encoder and generates the final output. Although simply using an encoder/decoder model would, most of the time, produce better result than traditional methods on the above-mentioned tasks, researchers proposed additional improvements over these sequence to sequence models, like using an attention-based model over the input, pointer-generation models, and self-attention models. However, all these seq2seq models suffer from two common problems: 1) exposure bias and 2) inconsistency between train/test measurement. Recently a completely fresh point of view emerged in solving these two problems in seq2seq models by using methods in Reinforcement Learning (RL). In these new researches, we try to look at the seq2seq problems from the RL point of view and we try to come up with a formulation that could combine the power of RL methods in decision-making and sequence to sequence models in remembering long memories. In this paper, we will summarize some of the most recent frameworks that combines concepts from RL world to the deep neural network area and explain how these two areas could benefit from each other in solving complex seq2seq tasks. In the end, we will provide insights on some of the problems of the current existing models and how we can improve them with better RL models. We also provide the source code for implementing most of the models that will be discussed in this paper on the complex task of abstractive text summarization.

##### Abstract (translated by Google)
近年来，序列到序列（seq2seq）模型被用于从机器翻译，标题生成，文本摘要，语音到文本到图像标题生成等各种任务。所有这些模型的底层框架通常是一个包含编码器和解码器的深度神经网络。编码器处理输入数据，解码器接收编码器的输出并生成最终输出。尽管简单地使用编码器/解码器模型在大多数情况下会比上述任务的传统方法产生更好的结果，但研究人员提出了对这些序列进行附加改进以对序列模型进行改进，例如在输入上使用基于注意力的模型，指针生成模型和自我注意模型。然而，所有这些seq2seq模型都有两个常见问题：1）暴露偏差和2）列车/测试测量之间的不一致性。最近，在使用强化学习（RL）中的方法解决seq2seq模型中的这两个问题时出现了一个全新的观点。在这些新的研究中，我们试图从RL的角度来看待seq2seq问题，我们试图提出一个能够将决策和顺序中的RL方法的强大功能结合起来以记忆长时记忆的序列模型的公式。在本文中，我们将总结一些将RL世界和深度神经网络领域的概念相结合的最新框架，并解释这两个领域如何在解决复杂的seq2seq任务中彼此受益。最后，我们将提供有关当前现有模型的一些问题的见解，以及如何使用更好的RL模型来改进它们。我们还提供了实现本文中讨论的抽象文本摘要这一复杂任务的大多数模型的源代码。

##### URL
[https://arxiv.org/abs/1805.09461](https://arxiv.org/abs/1805.09461)

##### PDF
[https://arxiv.org/pdf/1805.09461](https://arxiv.org/pdf/1805.09461)

