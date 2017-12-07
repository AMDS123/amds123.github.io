---
layout: post
title: "Distance-based Self-Attention Network for Natural Language Inference"
date: 2017-12-06 05:38:29
categories: arXiv_CL
tags: arXiv_CL Attention Inference RNN
author: Jinbae Im, Sungzoon Cho
mathjax: true
---

* content
{:toc}

##### Abstract
Attention mechanism has been used as an ancillary means to help RNN or CNN. However, the Transformer (Vaswani et al., 2017) recently recorded the state-of-the-art performance in machine translation with a dramatic reduction in training time by solely using attention. Motivated by the Transformer, Directional Self Attention Network (Shen et al., 2017), a fully attention-based sentence encoder, was proposed. It showed good performance with various data by using forward and backward directional information in a sentence. But in their study, not considered at all was the distance between words, an important feature when learning the local dependency to help understand the context of input text. We propose Distance-based Self-Attention Network, which considers the word distance by using a simple distance mask in order to model the local dependency without losing the ability of modeling global dependency which attention has inherent. Our model shows good performance with NLI data, and it records the new state-of-the-art result with SNLI data. Additionally, we show that our model has a strength in long sentences or documents.

##### Abstract (translated by Google)
注意机制已被用作帮助RNN或CNN的辅助手段。然而，Transformer（Vaswani et al。，2017）最近在机器翻译方面表现出了最先进的性能，只需要注意就大大缩短了培训时间。受到变压器，定向自注意网络（Shen et al。，2017）的启发，提出了一种完全注意的句子编码器。用一个句子中的前后向信息来表现出各种数据的良好表现。但在他们的研究中，根本不考虑词语之间的距离，这是学习本地依赖性以帮助理解输入文本的上下文的一个重要特征。我们提出了基于距离的自注意网络，它通过使用简单的距离掩模来考虑单词距离，以便对局部依赖性进行建模，而不会失去建模注意力所固有的全局依赖性的能力。我们的模型在NLI数据下显示出良好的性能，并且记录了SNLI数据的最新的最新结果。另外，我们展示了我们的模型在长句或文档中具有优势。

##### URL
[http://arxiv.org/abs/1712.02047](http://arxiv.org/abs/1712.02047)

##### PDF
[http://arxiv.org/pdf/1712.02047](http://arxiv.org/pdf/1712.02047)

