---
layout: post
title: "Exploring Recombination for Efficient Decoding of Neural Machine Translation"
date: 2018-08-25 23:26:10
categories: arXiv_CL
tags: arXiv_CL NMT Prediction
author: Zhisong Zhang, Rui Wang, Masao Utiyama, Eiichiro Sumita, Hai Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
In Neural Machine Translation (NMT), the decoder can capture the features of the entire prediction history with neural connections and representations. This means that partial hypotheses with different prefixes will be regarded differently no matter how similar they are. However, this might be inefficient since some partial hypotheses can contain only local differences that will not influence future predictions. In this work, we introduce recombination in NMT decoding based on the concept of the "equivalence" of partial hypotheses. Heuristically, we use a simple $n$-gram suffix based equivalence function and adapt it into beam search decoding. Through experiments on large-scale Chinese-to-English and English-to-Germen translation tasks, we show that the proposed method can obtain similar translation quality with a smaller beam size, making NMT decoding more efficient.

##### Abstract (translated by Google)
在神经机器翻译（NMT）中，解码器可以利用神经连接和表示来捕获整个预测历史的特征。这意味着具有不同前缀的部分假设将被视为不同，无论它们有多么相似。然而，这可能是低效的，因为一些部分假设只能包含不会影响未来预测的局部差异。在这项工作中，我们基于部分假设的“等价”的概念在NMT解码中引入重组。启发式地，我们使用简单的$ n $ -gram后缀基于等价函数并将其调整为波束搜索解码。通过大规模汉英翻译和英语到德语翻译任务的实验，我们证明了所提出的方法可以获得类似的翻译质量和更小的光束尺寸，使NMT解码更有效。

##### URL
[http://arxiv.org/abs/1808.08482](http://arxiv.org/abs/1808.08482)

##### PDF
[http://arxiv.org/pdf/1808.08482](http://arxiv.org/pdf/1808.08482)

