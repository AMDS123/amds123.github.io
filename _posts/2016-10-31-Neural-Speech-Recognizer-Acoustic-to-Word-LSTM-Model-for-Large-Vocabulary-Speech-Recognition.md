---
layout: post
title: "Neural Speech Recognizer: Acoustic-to-Word LSTM Model for Large Vocabulary Speech Recognition"
date: 2016-10-31 15:36:42
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition RNN Language_Model Recognition
author: Hagen Soltau, Hank Liao, Hasim Sak
mathjax: true
---

* content
{:toc}

##### Abstract
We present results that show it is possible to build a competitive, greatly simplified, large vocabulary continuous speech recognition system with whole words as acoustic units. We model the output vocabulary of about 100,000 words directly using deep bi-directional LSTM RNNs with CTC loss. The model is trained on 125,000 hours of semi-supervised acoustic training data, which enables us to alleviate the data sparsity problem for word models. We show that the CTC word models work very well as an end-to-end all-neural speech recognition model without the use of traditional context-dependent sub-word phone units that require a pronunciation lexicon, and without any language model removing the need to decode. We demonstrate that the CTC word models perform better than a strong, more complex, state-of-the-art baseline with sub-word units.

##### Abstract (translated by Google)
我们提出的结果表明，有可能建立一个有全部单词作为声学单元的有竞争力的，大大简化的大型词汇连续语音识别系统。我们使用具有CTC损失的深度双向LSTM RNN直接对大约100,000个字的输出词汇进行建模。该模型训练了125,000小时的半监督声训练数据，使我们能够缓解词模型的数据稀疏性问题。我们表明，CTC字模型工作得非常好，作为一个端到端的全神经语音识别模型，不需要使用传统的上下文相关子字的电话单元，需要一个发音词典，没有任何语言模型消除需要解码。我们证明，CTC单词模型比使用子单词单元的强大，更复杂，最先进的基线表现更好。

##### URL
[https://arxiv.org/abs/1610.09975](https://arxiv.org/abs/1610.09975)

##### PDF
[https://arxiv.org/pdf/1610.09975](https://arxiv.org/pdf/1610.09975)

