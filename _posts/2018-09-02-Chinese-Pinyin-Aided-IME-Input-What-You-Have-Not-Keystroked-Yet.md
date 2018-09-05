---
layout: post
title: "Chinese Pinyin Aided IME, Input What You Have Not Keystroked Yet"
date: 2018-09-02 12:01:27
categories: arXiv_AI
tags: arXiv_AI Attention
author: Yafang Huang, Hai Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Chinese pinyin input method engine (IME) converts pinyin into character so that Chinese characters can be conveniently inputted into computer through common keyboard. IMEs work relying on its core component, pinyin-to-character conversion (P2C). Usually Chinese IMEs simply predict a list of character sequences for user choice only according to user pinyin input at each turn. However, Chinese inputting is a multi-turn online procedure, which can be supposed to be exploited for further user experience promoting. This paper thus for the first time introduces a sequence-to-sequence model with gated-attention mechanism for the core task in IMEs. The proposed neural P2C model is learned by encoding previous input utterance as extra context to enable our IME capable of predicting character sequence with incomplete pinyin input. Our model is evaluated in different benchmark datasets showing great user experience improvement compared to traditional models, which demonstrates the first engineering practice of building Chinese aided IME.

##### Abstract (translated by Google)
中文拼音输入法引擎（IME）将拼音转换为字符，使汉字可以通过普通键盘方便地输入计算机。 IME的工作依赖于其核心组件，拼音到字符的转换（P2C）。通常，中国IME仅根据每个转弯处的用户拼音输入来预测用户选择的字符序列列表。然而，中文输入是一个多转在线程序，可以被用来进一步提升用户体验。因此，本文首次介绍了一种具有门控注意机制的序列到序列模型，用于IME中的核心任务。通过将先前的输入话语编码为额外的上下文来学习所提出的神经P2C模型，以使我们的IME能够预测具有不完整拼音输入的字符序列。我们的模型在不同的基准数据集中进行评估，与传统模型相比，显示了良好的用户体验改进，这表明了构建中文辅助IME的第一个工程实践。

##### URL
[http://arxiv.org/abs/1809.00329](http://arxiv.org/abs/1809.00329)

##### PDF
[http://arxiv.org/pdf/1809.00329](http://arxiv.org/pdf/1809.00329)

