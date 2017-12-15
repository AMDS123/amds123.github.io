---
layout: post
title: "Neural Semantic Parsing by Character-based Translation: Experiments with Abstract Meaning Representations"
date: 2017-10-09 08:30:33
categories: arXiv_CL
tags: arXiv_CL
author: Rik van Noord, Johan Bos
mathjax: true
---

* content
{:toc}

##### Abstract
We evaluate the character-level translation method for neural semantic parsing on a large corpus of sentences annotated with Abstract Meaning Representations (AMRs). Using a sequence-to-sequence model, and some trivial preprocessing and postprocessing of AMRs, we obtain a baseline accuracy of 53.1 (F-score on AMR-triples). We examine five different approaches to improve this baseline result: (i) reordering AMR branches to match the word order of the input sentence increases performance to 58.3; (ii) adding part-of-speech tags (automatically produced) to the input shows improvement as well (57.2); (iii) So does the introduction of super characters (conflating frequent sequences of characters to a single character), reaching 57.4; (iv) optimizing the training process by using pre-training and averaging a set of models increases performance to 58.7; (v) adding silver-standard training data obtained by an off-the-shelf parser yields the biggest improvement, resulting in an F-score of 64.0. Combining all five techniques leads to an F-score of 71.0 on holdout data, which is state-of-the-art in AMR parsing. This is remarkable because of the relative simplicity of the approach.

##### Abstract (translated by Google)
我们评估用抽象意义表示（AMRs）注释的句子的大量语料库上的神经语义解析的字符级翻译方法。使用序列到序列模型，以及对AMR的一些简单的预处理和后处理，我们获得53.1的基线准确性（AMR三元组的F分数）。我们研究了五种不同的方法来改善这个基线结果：（i）重新排列AMR分支以匹配输入句子的词序将性能提高到58.3; （ii）向输入添加词性标签（自动生成的）也显示出改进（57.2）; （iii）引入超级字符（将频繁的字符序列混合成一个字符）达到57.4; （iv）通过使用预先训练和平均一组模型来优化训练过程将性能提高到58.7; （v）通过现成解析器获得的银级标准训练数据产生最大的改善，导致64.0的F分数。结合所有五种技术，保持数据的F值为71.0，这在AMR解析中是最先进的。这是显着的，因为这种方法相对简单。

##### URL
[https://arxiv.org/abs/1705.09980](https://arxiv.org/abs/1705.09980)

##### PDF
[https://arxiv.org/pdf/1705.09980](https://arxiv.org/pdf/1705.09980)

