---
layout: post
title: "Parameter Sharing Methods for Multilingual Self-Attentional Translation Models"
date: 2018-09-01 21:12:09
categories: arXiv_CL
tags: arXiv_CL Attention
author: Devendra Singh Sachan, Graham Neubig
mathjax: true
---

* content
{:toc}

##### Abstract
In multilingual neural machine translation, it has been shown that sharing a single translation model between multiple languages can achieve competitive performance, sometimes even leading to performance gains over bilingually trained models. However, these improvements are not uniform; often multilingual parameter sharing results in a decrease in accuracy due to translation models not being able to accommodate different languages in their limited parameter space. In this work, we examine parameter sharing techniques that strike a happy medium between full sharing and individual training, specifically focusing on the self-attentional Transformer model. We find that the full parameter sharing approach leads to increases in BLEU scores mainly when the target languages are from a similar language family. However, even in the case where target languages are from different families where full parameter sharing leads to a noticeable drop in BLEU scores, our proposed methods for partial sharing of parameters can lead to substantial improvements in translation accuracy.

##### Abstract (translated by Google)
在多语言神经机器翻译中，已经表明在多种语言之间共享单个翻译模型可以实现竞争性能，有时甚至导致比双向训练模型的性能提升。但是，这些改进并不统一;由于翻译模型无法在其有限的参数空间中容纳不同的语言，因此多语言参数共享通常会导致准确度降低。在这项工作中，我们研究了参数共享技术，这些技术在完全共享和个人培训之间取得了愉快的关注，特别是关注自我关注的Transformer模型。我们发现，当目标语言来自相似的语言族时，完整的参数共享方法会导致BLEU分数的增加。然而，即使在目标语言来自不同家庭的情况下，其中完全参数共享导致BLEU得分的显着下降，我们提出的用于部分共享参数的方法可以导致翻译准确性的实质性改进。

##### URL
[http://arxiv.org/abs/1809.00252](http://arxiv.org/abs/1809.00252)

##### PDF
[http://arxiv.org/pdf/1809.00252](http://arxiv.org/pdf/1809.00252)

