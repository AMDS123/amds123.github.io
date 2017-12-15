---
layout: post
title: "CFGs-2-NLU: Sequence-to-Sequence Learning for Mapping Utterances to Semantics and Pragmatics"
date: 2016-07-22 22:05:20
categories: arXiv_CL
tags: arXiv_CL Knowledge Face RNN Deep_Learning
author: Adam James Summerville, James Ryan, Michael Mateas, Noah Wardrip-Fruin
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a novel approach to natural language understanding that utilizes context-free grammars (CFGs) in conjunction with sequence-to-sequence (seq2seq) deep learning. Specifically, we take a CFG authored to generate dialogue for our target application for NLU, a videogame, and train a long short-term memory (LSTM) recurrent neural network (RNN) to map the surface utterances that it produces to traces of the grammatical expansions that yielded them. Critically, this CFG was authored using a tool we have developed that supports arbitrary annotation of the nonterminal symbols in the grammar. Because we already annotated the symbols in this grammar for the semantic and pragmatic considerations that our game's dialogue manager operates over, we can use the grammatical trace associated with any surface utterance to infer such information. During gameplay, we translate player utterances into grammatical traces (using our RNN), collect the mark-up attributed to the symbols included in that trace, and pass this information to the dialogue manager, which updates the conversation state accordingly. From an offline evaluation task, we demonstrate that our trained RNN translates surface utterances to grammatical traces with great accuracy. To our knowledge, this is the first usage of seq2seq learning for conversational agents (our game's characters) who explicitly reason over semantic and pragmatic considerations.

##### Abstract (translated by Google)
在本文中，我们提出了一种自然语言理解的新方法，它利用上下文无关语法（CFGs）和序列到序列（seq2seq）的深度学习。具体来说，我们采用一个CFG来为我们的NLU（视频游戏）的目标应用程序产生对话，并训练一个长期的短期记忆（LSTM）递归神经网络（RNN），以将它产生的表面话语映射到语法的痕迹扩大，产生了他们。重要的是，这个CFG是使用我们开发的支持任意注释非终结符号的语法工具创作的。因为我们已经注解了这个语法中的符号，以便我们的游戏对话管理器运行的语义和实用考虑，我们可以使用与任何表面发音相关的语法轨迹来推断这些信息。在游戏过程中，我们将玩家话语翻译成语法轨迹（使用我们的RNN），收集归因于包含在轨迹中的符号的标记，并将这些信息传递给对话管理器，对话管理器相应地更新对话状态。从一个离线的评估任务，我们证明了我们训练有素的RNN将表面话语转换成语法轨迹非常准确。据我们所知，这是seq2seq学习的第一个用法，用于会话代理（我们的游戏的角色）明确地推理语义和实用的考虑。

##### URL
[https://arxiv.org/abs/1607.06852](https://arxiv.org/abs/1607.06852)

##### PDF
[https://arxiv.org/pdf/1607.06852](https://arxiv.org/pdf/1607.06852)

