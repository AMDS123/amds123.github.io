---
layout: post
title: "Pre-training on high-resource speech recognition improves low-resource speech-to-text translation"
date: 2018-09-05 10:56:30
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Recognition
author: Sameer Bansal, Herman Kamper, Karen Livescu, Adam Lopez, Sharon Goldwater
mathjax: true
---

* content
{:toc}

##### Abstract
We present a simple approach to improve direct speech-to-text translation (ST) when the source language is low-resource: we pre-train the model on a high-resource automatic speech recognition (ASR) task, and then fine-tune its parameters for ST. We demonstrate that our approach is effective by pre-training on 300 hours of English ASR data to improve Spanish-English ST from 10.8 to 20.2 BLEU when only 20 hours of Spanish-English ST training data is available. Through an ablation study, we find that the pre-trained encoder (acoustic model) accounts for most of the improvement, which is surprising since the shared language in these tasks is the target language (text), and not the source language (audio). Applying this insight, we show that pre-training on ASR helps ST even when the ASR language differs from both source and target ST languages: pre-training on French ASR also improves Spanish-English ST. Finally, we show that the approach improves a true low-resource task: pre-training on a combination of English ASR and French ASR improves Mboshi-French ST, where only 4 hours of data are available, from 3.5 to 7.1 BLEU.

##### Abstract (translated by Google)
当源语言资源不足时，我们提出了一种改进直接语音到文本转换（ST）的简单方法：我们在高资源自动语音识别（ASR）任务上预先训练模型，然后进行微调。它的参数为ST。我们通过对300小时的英语ASR数据进行预训练来证明我们的方法是有效的，当只有20小时的西班牙语 - 英语ST训练数据时，将西班牙语 - 英语ST从10.8提高到20.2 BLEU。通过消融研究，我们发现预训练的编码器（声学模型）占了大部分改进，这是令人惊讶的，因为这些任务中的共享语言是目标语言（文本），而不是源语言（音频） 。应用这种见解，我们表明，即使ASR语言与源语言和目标ST语言不同，ASR预训练也有助于ST：法语ASR的预训练也提高了西班牙语 - 英语ST。最后，我们证明该方法改进了真正的低资源任务：英语ASR和法语ASR组合的预训练改进了Mboshi-French ST，其中只有4小时的数据可用，从3.5到7.1 BLEU。

##### URL
[http://arxiv.org/abs/1809.01431](http://arxiv.org/abs/1809.01431)

##### PDF
[http://arxiv.org/pdf/1809.01431](http://arxiv.org/pdf/1809.01431)

