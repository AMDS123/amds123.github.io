---
layout: post
title: "Transfer Learning across Low-Resource, Related Languages for Neural Machine Translation"
date: 2017-09-21 17:04:20
categories: arXiv_CL
tags: arXiv_CL Embedding Transfer_Learning
author: Toan Q. Nguyen, David Chiang
mathjax: true
---

* content
{:toc}

##### Abstract
We present a simple method to improve neural translation of a low-resource language pair using parallel data from a related, also low-resource, language pair. The method is based on the transfer method of Zoph et al., but whereas their method ignores any source vocabulary overlap, ours exploits it. First, we split words using Byte Pair Encoding (BPE) to increase vocabulary overlap. Then, we train a model on the first language pair and transfer its parameters, including its source word embeddings, to another model and continue training on the second language pair. Our experiments show that transfer learning helps word-based translation only slightly, but when used on top of a much stronger BPE baseline, it yields larger improvements of up to 4.3 BLEU.

##### Abstract (translated by Google)
我们提出了一个简单的方法来改善使用来自相关的，也是低资源的语言对的并行数据的低资源语言对的神经翻译。该方法是基于Zoph等人的转移方法，但是他们的方法忽略了任何来源词汇的重叠，我们的利用它。首先，我们使用字节对编码（BPE）分割单词以增加词汇重叠。然后，我们在第一语言对上训练模型，并将其参数（包括其源词嵌入）转移到另一个模型，并继续对第二语言对进行训练。我们的实验表明，转移学习只能帮助基于词的翻译稍微有点用处，但是如果在更强的BPE基线之上使用，则可以获得高达4.3 BLEU的更大改进。

##### URL
[https://arxiv.org/abs/1708.09803](https://arxiv.org/abs/1708.09803)

##### PDF
[https://arxiv.org/pdf/1708.09803](https://arxiv.org/pdf/1708.09803)

