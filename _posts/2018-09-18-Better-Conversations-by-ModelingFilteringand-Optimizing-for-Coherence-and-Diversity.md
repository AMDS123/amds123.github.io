---
layout: post
title: "Better Conversations by Modeling,Filtering,and Optimizing for Coherence and Diversity"
date: 2018-09-18 18:08:19
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Xinnuo Xu, Ond&#x159;ej Du&#x161;ek, Ioannis Konstas, Verena Rieser
mathjax: true
---

* content
{:toc}

##### Abstract
We present three enhancements to existing encoder-decoder models for open-domain conversational agents, aimed at effectively modeling coherence and promoting output diversity: (1) We introduce a measure of coherence as the GloVe embedding similarity between the dialogue context and the generated response, (2) we filter our training corpora based on the measure of coherence to obtain topically coherent and lexically diverse context-response pairs, (3) we then train a response generator using a conditional variational autoencoder model that incorporates the measure of coherence as a latent variable and uses a context gate to guarantee topical consistency with the context and promote lexical diversity. Experiments on the OpenSubtitles corpus show a substantial improvement over competitive neural models in terms of BLEU score as well as metrics of coherence and diversity.

##### Abstract (translated by Google)
我们针对开放域会话代理的现有编码器 - 解码器模型提出了三种增强，旨在有效地建模一致性并促进输出多样性：（1）我们引入一种一致性度量作为GloVe嵌入对话上下文与生成的响应之间的相似性， （2）我们根据相干性度量过滤我们的训练语料库，以获得局部相干和词汇多样化的上下文 - 响应对。（3）然后，我们使用条件变量自动编码器模型训练响应生成器，该模型将相干性度量结合为潜在的变量并使用上下文门来保证与上下文的主题一致性并促进词汇多样性。 OpenSubtitles语料库的实验表明，就BLEU评分以及连贯性和多样性的指标而言，竞争神经模型有了实质性的改进。

##### URL
[http://arxiv.org/abs/1809.06873](http://arxiv.org/abs/1809.06873)

##### PDF
[http://arxiv.org/pdf/1809.06873](http://arxiv.org/pdf/1809.06873)

