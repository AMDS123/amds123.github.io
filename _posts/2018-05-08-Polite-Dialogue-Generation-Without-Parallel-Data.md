---
layout: post
title: "Polite Dialogue Generation Without Parallel Data"
date: 2018-05-08 16:56:15
categories: arXiv_AI
tags: arXiv_AI Attention Reinforcement_Learning Embedding Language_Model
author: Tong Niu, Mohit Bansal
mathjax: true
---

* content
{:toc}

##### Abstract
Stylistic dialogue response generation, with valuable applications in personality-based conversational agents, is a challenging task because the response needs to be fluent, contextually-relevant, as well as paralinguistically accurate. Moreover, parallel datasets for regular-to-stylistic pairs are usually unavailable. We present three weakly-supervised models that can generate diverse polite (or rude) dialogue responses without parallel data. Our late fusion model (Fusion) merges the decoder of an encoder-attention-decoder dialogue model with a language model trained on stand-alone polite utterances. Our label-fine-tuning (LFT) model prepends to each source sequence a politeness-score scaled label (predicted by our state-of-the-art politeness classifier) during training, and at test time is able to generate polite, neutral, and rude responses by simply scaling the label embedding by the corresponding score. Our reinforcement learning model (Polite-RL) encourages politeness generation by assigning rewards proportional to the politeness classifier score of the sampled response. We also present two retrieval-based polite dialogue model baselines. Human evaluation validates that while the Fusion and the retrieval-based models achieve politeness with poorer context-relevance, the LFT and Polite-RL models can produce significantly more polite responses without sacrificing dialogue quality.

##### Abstract (translated by Google)
文体对话反应的产生，在基于个性的会话代理中具有有价值的应用，是一项具有挑战性的任务，因为反应需要流利，上下文相关以及并行语言准确。此外，常规到文体对的平行数据集通常不可用。我们提出了三个弱监督模型，可以产生不同的礼貌（或粗鲁）对话反应，没有平行数据。我们后期的融合模型（Fusion）将编码器 - 注意 - 解码器对话模型的解码器与在独立礼貌话语上训练的语言模型合并。我们的标签微调（LFT）模型在训练过程中将每个源序列预先设置一个礼貌评分标度（由我们先进的礼貌分类器预测），并且在测试时间能够产生礼貌，中立，并通过简单地按照相应分数缩放标签嵌入来粗鲁回应。我们的强化学习模型（Polite-RL）鼓励通过分配与采样响应的礼貌分类器分数成正比的奖励来产生礼貌。我们还提出了两个基于检索的礼貌对话模型基线。人类评估证实，虽然融合和基于检索的模型达到了较差的上下文相关性，但LFT和Polite-RL模型可以在不牺牲对话质量的情况下产生显着更有礼貌的反应。

##### URL
[https://arxiv.org/abs/1805.03162](https://arxiv.org/abs/1805.03162)

##### PDF
[https://arxiv.org/pdf/1805.03162](https://arxiv.org/pdf/1805.03162)

