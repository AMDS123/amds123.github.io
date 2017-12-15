---
layout: post
title: "Hierarchical Recurrent Attention Network for Response Generation"
date: 2017-01-25 03:04:31
categories: arXiv_SD
tags: arXiv_SD QA Attention
author: Chen Xing, Wei Wu, Yu Wu, Ming Zhou, Yalou Huang, Wei-Ying Ma
mathjax: true
---

* content
{:toc}

##### Abstract
We study multi-turn response generation in chatbots where a response is generated according to a conversation context. Existing work has modeled the hierarchy of the context, but does not pay enough attention to the fact that words and utterances in the context are differentially important. As a result, they may lose important information in context and generate irrelevant responses. We propose a hierarchical recurrent attention network (HRAN) to model both aspects in a unified framework. In HRAN, a hierarchical attention mechanism attends to important parts within and among utterances with word level attention and utterance level attention respectively. With the word level attention, hidden vectors of a word level encoder are synthesized as utterance vectors and fed to an utterance level encoder to construct hidden representations of the context. The hidden vectors of the context are then processed by the utterance level attention and formed as context vectors for decoding the response. Empirical studies on both automatic evaluation and human judgment show that HRAN can significantly outperform state-of-the-art models for multi-turn response generation.

##### Abstract (translated by Google)
我们研究了根据对话上下文产生响应的chatbots中的多回应响应生成。现有的工作模仿了语境的层次结构，但对于语境中的话语和话语具有差异性的重要性并没有引起足够的重视。因此，他们可能会丢失重要的信息并产生不相关的反应。我们提出了一个分层的经常性关注网络（HRAN）在一个统一的框架中对两个方面进行建模。在HRAN中，分层注意机制分别以话语层面的注意力和话语层面的注意力参与话语内部和话语之间的重要部分。利用字级关注，将字级编码器的隐藏向量合成为话语向量，并馈送到话语级编码器以构建上下文的隐藏表示。上下文的隐藏向量然后由话语级关注来处理，并形成为用于解码响应的上下文向量。自动评估和人为判断的实证研究表明，HRAN可以显着地胜过最先进的多回转反应模型。

##### URL
[https://arxiv.org/abs/1701.07149](https://arxiv.org/abs/1701.07149)

##### PDF
[https://arxiv.org/pdf/1701.07149](https://arxiv.org/pdf/1701.07149)

