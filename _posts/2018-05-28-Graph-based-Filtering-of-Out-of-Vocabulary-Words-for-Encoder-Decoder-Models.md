---
layout: post
title: "Graph-based Filtering of Out-of-Vocabulary Words for Encoder-Decoder Models"
date: 2018-05-28 22:09:49
categories: arXiv_CL
tags: arXiv_CL
author: Satoru Katsumata, Yukio Matsumura, Hayahide Yamagishi, Mamoru Komachi
mathjax: true
---

* content
{:toc}

##### Abstract
Encoder-decoder models typically only employ words that are frequently used in the training corpus to reduce the computational costs and exclude noise. However, this vocabulary set may still include words that interfere with learning in encoder-decoder models. This paper proposes a method for selecting more suitable words for learning encoders by utilizing not only frequency, but also co-occurrence information, which we capture using the HITS algorithm. We apply our proposed method to two tasks: machine translation and grammatical error correction. For Japanese-to-English translation, this method achieves a BLEU score that is 0.56 points more than that of a baseline. It also outperforms the baseline method for English grammatical error correction, with an F0.5-measure that is 1.48 points higher.

##### Abstract (translated by Google)
编码器 - 解码器模型通常仅使用在训练语料库中经常使用的词来降低计算成本并排除噪声。但是，这个词汇集可能仍然包含干扰编码器 - 解码器模型中的学习的词汇。本文提出了一种通过不仅利用频率而且利用HITS算法捕获的同现信息来选择更适合学习编码器的单词的方法。我们将我们提出的方法应用于两项任务：机器翻译和语法错误修正。对于日语到英语的翻译，此方法的BLEU分数比基线高0.56分。它也优于英语语法错误修正的基准方法，F0.5-测量值高出1.48点。

##### URL
[http://arxiv.org/abs/1805.11189](http://arxiv.org/abs/1805.11189)

##### PDF
[http://arxiv.org/pdf/1805.11189](http://arxiv.org/pdf/1805.11189)

