---
layout: post
title: "Improved training of end-to-end attention models for speech recognition"
date: 2018-05-08 21:27:04
categories: arXiv_CL
tags: arXiv_CL Attention Speech_Recognition RNN Language_Model Recognition
author: Albert Zeyer, Kazuki Irie, Ralf Schl&#xfc;ter, Hermann Ney
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence-to-sequence attention-based models on subword units allow simple open-vocabulary end-to-end speech recognition. In this work, we show that such models can achieve competitive results on the Switchboard 300h and LibriSpeech 1000h tasks. In particular, we report the state-of-the-art word error rates (WER) of 3.54% on the dev-clean and 3.82% on the test-clean evaluation subsets of LibriSpeech. We introduce a new pretraining scheme by starting with a high time reduction factor and lowering it during training, which is crucial both for convergence and final performance. In some experiments, we also use an auxiliary CTC loss function to help the convergence. In addition, we train long short-term memory (LSTM) language models on subword units. By shallow fusion, we report up to 27% relative improvements in WER over the attention baseline without a language model.

##### Abstract (translated by Google)
基于序列的基于注意的子字单元模型允许简单的开放式词汇端对端语音识别。在这项工作中，我们表明这些模型可以在交换机300h和LibriSpeech 1000h任务上实现竞争结果。特别是，我们报告了dev-clean的3.54％和LibriSpeech测试清理评估子集的最新错误率（WER）。我们引入了一种新的预训练方案，从高时间缩减因子开始，并在训练期间降低它，这对收敛和最终性能都是至关重要的。在一些实验中，我们还使用辅助CTC损失函数来帮助收敛。另外，我们在子字单元上训练长期短期记忆（LSTM）语言模型。通过浅层融合，我们报告了WER相对于没有语言模型的关注基线的相对改进27％。

##### URL
[http://arxiv.org/abs/1805.03294](http://arxiv.org/abs/1805.03294)

##### PDF
[http://arxiv.org/pdf/1805.03294](http://arxiv.org/pdf/1805.03294)

