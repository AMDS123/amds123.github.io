---
layout: post
title: "Cell-aware Stacked LSTMs for Modeling Sentences"
date: 2018-09-07 02:17:23
categories: arXiv_CL
tags: arXiv_CL Sentiment Sentiment_Classification Inference RNN Classification Detection
author: Jihun Choi, Taeuk Kim, Sang-goo Lee
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a method of stacking multiple long short-term memory (LSTM) layers for modeling sentences. In contrast to the conventional stacked LSTMs where only hidden states are fed as input to the next layer, our architecture accepts both hidden and memory cell states of the preceding layer and fuses information from the left and the lower context using the soft gating mechanism of LSTMs. Thus the proposed stacked LSTM architecture modulates the amount of information to be delivered not only in horizontal recurrence but also in vertical connections, from which useful features extracted from lower layers are effectively conveyed to upper layers. We dub this architecture Cell-aware Stacked LSTM (CAS-LSTM) and show from experiments that our models achieve state-of-the-art results on benchmark datasets for natural language inference, paraphrase detection, and sentiment classification.

##### Abstract (translated by Google)
我们提出了一种堆叠多个长短期记忆（LSTM）层的方法，用于建模句子。与仅将隐藏状态作为输入馈送到下一层的传统堆叠LSTM相比，我们的架构接受前一层的隐藏和存储单元状态，并使用LSTM的软选通机制融合来自左上下文的信息。 。因此，所提出的堆叠LSTM架构不仅在水平重现中而且在垂直连接中调制要传递的信息量，从下层提取的有用特征被有效地传递到上层。我们将这种架构称为Cell-aware Stacked LSTM（CAS-LSTM），并通过实验证明我们的模型在基准数据集上实现了最先进的结果，用于自然语言推理，释义检测和情感分类。

##### URL
[https://arxiv.org/abs/1809.02279](https://arxiv.org/abs/1809.02279)

##### PDF
[https://arxiv.org/pdf/1809.02279](https://arxiv.org/pdf/1809.02279)

