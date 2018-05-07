---
layout: post
title: "Apply Chinese Radicals Into Neural Machine Translation: Deeper Than Character Level"
date: 2018-05-03 22:58:54
categories: arXiv_CL
tags: arXiv_CL Knowledge Attention Face NMT
author: Shaohui Kuang, Lifeng Han
mathjax: true
---

* content
{:toc}

##### Abstract
In neural machine translation (NMT), researchers face the challenge of un-seen (or out-of-vocabulary OOV) words translation. To solve this, some researchers propose the splitting of western languages such as English and German into sub-words or compounds. In this paper, we try to address this OOV issue and improve the NMT adequacy with a harder language Chinese whose characters are even more sophisticated in composition. We integrate the Chinese radicals into the NMT model with different settings to address the unseen words challenge in Chinese to English translation. On the other hand, this also can be considered as semantic part of the MT system since the Chinese radicals usually carry the essential meaning of the words they are constructed in. Meaningful radicals and new characters can be integrated into the NMT systems with our models. We use an attention-based NMT system as a strong baseline system. The experiments on standard Chinese-to-English NIST translation shared task data 2006 and 2008 show that our designed models outperform the baseline model in a wide range of state-of-the-art evaluation metrics including LEPOR, BEER, and CharacTER, in addition to the traditional BLEU and NIST scores, especially on the adequacy-level translation. We also have some interesting findings from the results of our various experiment settings about the performance of words and characters in Chinese NMT, which is different with other languages. For instance, the full character level NMT may perform very well or the state of the art in some other languages as researchers demonstrated recently, however, in the Chinese NMT model, word boundary knowledge is important for the model learning.

##### Abstract (translated by Google)
在神经机器翻译（NMT）中，研究人员面临着未见过的（或词汇外OOV）单词翻译的挑战。为了解决这个问题，一些研究人员提出将西方语言如英语和德语分解为子词或复合词。在本文中，我们试图解决这个OOV问题，并用更难的语言来提高NMT的适应性，这些汉语的人物组成更复杂。我们将中文部首纳入具有不同设置的NMT模式，以解决在汉语中看不见的单词挑战与英文翻译。另一方面，这也可以被认为是MT系统的语义部分，因为中文部首通常带有他们所构建单词的基本含义。有意义的部首和新角色可以用我们的模型整合到NMT系统中。我们使用基于注意力的NMT系统作为强大的基线系统。对标准的中英文NIST翻译共享任务数据2006年和2008年的实验表明，我们的设计模型在各种最先进的评估指标（包括LEPOR，BEER和Character）方面均优于基准模型到传统的BLEU和NIST成绩，特别是在充足程度上的翻译。我们还从我们的各种实验设置的结果中得到了一些有趣的发现，这些实验设置关于中文NMT中的文字和字符的表现，这与其他语言不同。例如，最近研究人员证明，全角色水平的NMT可能表现得非常好，或者在其他一些语言中表现得非常好，但是在中国的NMT模型中，字边界知识对于模型学习很重要。

##### URL
[http://arxiv.org/abs/1805.01565](http://arxiv.org/abs/1805.01565)

##### PDF
[http://arxiv.org/pdf/1805.01565](http://arxiv.org/pdf/1805.01565)

