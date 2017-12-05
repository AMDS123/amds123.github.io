---
layout: post
title: 'English-Japanese Neural Machine Translation with Encoder-Decoder-Reconstructor'
date: 2017-12-06 02:59:39
categories: arXiv_CL
tags: arXiv_CL NMT
author: Yukio Matsumura, Takayuki Sato, Mamoru Komachi
---

* content
{:toc}

##### Abstract
Neural machine translation (NMT) has recently become popular in the field of machine translation. However, NMT suffers from the problem of repeating or missing words in the translation. To address this problem, Tu et al. (2017) proposed an encoder-decoder-reconstructor framework for NMT using back-translation. In this method, they selected the best forward translation model in the same manner as Bahdanau et al. (2015), and then trained a bi-directional translation model as fine-tuning. Their experiments show that it offers significant improvement in BLEU scores in Chinese-English translation task. We confirm that our re-implementation also shows the same tendency and alleviates the problem of repeating and missing words in the translation on a English-Japanese task too. In addition, we evaluate the effectiveness of pre-training by comparing it with a jointly-trained model of forward translation and back-translation.

##### Abstract (translated by Google)
神经机器翻译（NMT）最近在机器翻译领域受到欢迎。然而，NMT在翻译中存在重复或遗漏的问题。为了解决这个问题，Tu et al。 （2017）提出了一种使用反向翻译的NMT的编码器 - 解码器 - 重构器框架。在这种方法中，他们选择了最好的正向翻译模式，就像Bahdanau等人一样。 （2015），然后训练双向翻译模型作为微调。他们的实验表明，在中英文翻译任务中，BLEU得分显着提高。我们确认我们的重新执行也表现出同样的倾向，也缓解了英日任务中翻译中重复和遗漏的问题。另外，我们通过与前向翻译和后向翻译的联合训练模型进行比较来评估预训练的有效性。

##### URL
[https://arxiv.org/abs/1706.08198](https://arxiv.org/abs/1706.08198)

