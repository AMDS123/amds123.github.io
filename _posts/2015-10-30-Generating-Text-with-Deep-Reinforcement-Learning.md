---
layout: post
title: "Generating Text with Deep Reinforcement Learning"
date: 2015-10-30 19:02:53
categories: arXiv_CL
tags: arXiv_CL Attention Reinforcement_Learning RNN
author: Hongyu Guo
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a novel schema for sequence to sequence learning with a Deep Q-Network (DQN), which decodes the output sequence iteratively. The aim here is to enable the decoder to first tackle easier portions of the sequences, and then turn to cope with difficult parts. Specifically, in each iteration, an encoder-decoder Long Short-Term Memory (LSTM) network is employed to, from the input sequence, automatically create features to represent the internal states of and formulate a list of potential actions for the DQN. Take rephrasing a natural sentence as an example. This list can contain ranked potential words. Next, the DQN learns to make decision on which action (e.g., word) will be selected from the list to modify the current decoded sequence. The newly modified output sequence is subsequently used as the input to the DQN for the next decoding iteration. In each iteration, we also bias the reinforcement learning's attention to explore sequence portions which are previously difficult to be decoded. For evaluation, the proposed strategy was trained to decode ten thousands natural sentences. Our experiments indicate that, when compared to a left-to-right greedy beam search LSTM decoder, the proposed method performed competitively well when decoding sentences from the training set, but significantly outperformed the baseline when decoding unseen sentences, in terms of BLEU score obtained.

##### Abstract (translated by Google)
我们引入了一个新的序列模式，用深度Q网络（DQN）对序列进行学习，迭代地对输出序列进行解码。这里的目的是使解码器能够首先解决序列中较为容易的部分，然后转而应付困难的部分。具体而言，在每次迭代中，采用编码器 - 解码器长期短期存储器（LSTM）网络从输入序列自动创建表示DQN的内部状态的特征并且制定潜在动作的列表。以一句自然的句子作为例子。该列表可以包含排名潜在词。接下来，DQN学习如何决定从列表中选择哪个动作（例如单词）来修改当前解码的序列。随后将新修改的输出序列用作DQN的输入以用于下一次解码迭代。在每次迭代中，我们也将强化学习的注意力偏向于探索之前难以解码的序列部分。为了评估，提出的策略被训练来解码一万个自然语句。我们的实验表明，当与从左到右的贪婪束搜索LSTM解码器相比时，所提出的方法在从训练集解码句子时表现出竞争良好，但是在解读看不见的句子时，在获得的BLEU得分方面显着优于基线。

##### URL
[https://arxiv.org/abs/1510.09202](https://arxiv.org/abs/1510.09202)

##### PDF
[https://arxiv.org/pdf/1510.09202](https://arxiv.org/pdf/1510.09202)

