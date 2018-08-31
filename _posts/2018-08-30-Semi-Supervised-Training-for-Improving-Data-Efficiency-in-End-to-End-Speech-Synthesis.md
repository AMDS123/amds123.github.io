---
layout: post
title: "Semi-Supervised Training for Improving Data Efficiency in End-to-End Speech Synthesis"
date: 2018-08-30 05:51:30
categories: arXiv_CL
tags: arXiv_CL Knowledge
author: Yu-An Chung, Yuxuan Wang, Wei-Ning Hsu, Yu Zhang, RJ Skerry-Ryan
mathjax: true
---

* content
{:toc}

##### Abstract
Although end-to-end text-to-speech (TTS) models such as Tacotron have shown excellent results, they typically require a sizable set of high-quality &lt;text, audio&gt; pairs for training, which are expensive to collect. In this paper, we propose a semi-supervised training framework to improve the data efficiency of Tacotron. The idea is to allow Tacotron to utilize textual and acoustic knowledge contained in large, publicly-available text and speech corpora. Importantly, these external data are unpaired and potentially noisy. Specifically, first we embed each word in the input text into word vectors and condition the Tacotron encoder on them. We then use an unpaired speech corpus to pre-train the Tacotron decoder in the acoustic domain. Finally, we fine-tune the model using available paired data. We demonstrate that the proposed framework enables Tacotron to generate intelligible speech using less than half an hour of paired training data.

##### Abstract (translated by Google)
尽管诸如Tacotron的端到端文本到语音（TTS）模型已经显示出优异的结果，但是它们通常需要大量高质量的＆lt;文本，音频＆gt;。训练对，收集费用昂贵。在本文中，我们提出了一个半监督的培训框架，以提高Tacotron的数据效率。这个想法是允许Tacotron利用大型公开文本和语音语料库中包含的文本和声学知识。重要的是，这些外部数据不配对且可能有噪音。具体来说，首先我们将输入文本中的每个单词嵌入到单词向量中，然后在其上调整Tacotron编码器。然后，我们使用不成对的语音语料库在声学域中预训练Tacotron解码器。最后，我们使用可用的配对数据对模型进行微调。我们证明了所提出的框架使Tacotron能够使用不到半小时的配对训练数据生成可理解的语音。

##### URL
[http://arxiv.org/abs/1808.10128](http://arxiv.org/abs/1808.10128)

##### PDF
[http://arxiv.org/pdf/1808.10128](http://arxiv.org/pdf/1808.10128)

