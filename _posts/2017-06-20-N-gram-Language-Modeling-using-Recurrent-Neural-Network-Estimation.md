---
layout: post
title: "N-gram Language Modeling using Recurrent Neural Network Estimation"
date: 2017-06-20 01:22:18
categories: arXiv_SD
tags: arXiv_SD RNN Language_Model
author: Ciprian Chelba, Mohammad Norouzi, Samy Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate the effective memory depth of RNN models by using them for $n$-gram language model (LM) smoothing. Experiments on a small corpus (UPenn Treebank, one million words of training data and 10k vocabulary) have found the LSTM cell with dropout to be the best model for encoding the $n$-gram state when compared with feed-forward and vanilla RNN models. When preserving the sentence independence assumption the LSTM $n$-gram matches the LSTM LM performance for $n=9$ and slightly outperforms it for $n=13$. When allowing dependencies across sentence boundaries, the LSTM $13$-gram almost matches the perplexity of the unlimited history LSTM LM. LSTM $n$-gram smoothing also has the desirable property of improving with increasing $n$-gram order, unlike the Katz or Kneser-Ney back-off estimators. Using multinomial distributions as targets in training instead of the usual one-hot target is only slightly beneficial for low $n$-gram orders. Experiments on the One Billion Words benchmark show that the results hold at larger scale: while LSTM smoothing for short $n$-gram contexts does not provide significant advantages over classic N-gram models, it becomes effective with long contexts ($n > 5$); depending on the task and amount of data it can match fully recurrent LSTM models at about $n=13$. This may have implications when modeling short-format text, e.g. voice search/query LMs. Building LSTM $n$-gram LMs may be appealing for some practical situations: the state in a $n$-gram LM can be succinctly represented with $(n-1)*4$ bytes storing the identity of the words in the context and batches of $n$-gram contexts can be processed in parallel. On the downside, the $n$-gram context encoding computed by the LSTM is discarded, making the model more expensive than a regular recurrent LSTM LM.

##### Abstract (translated by Google)
我们通过使用$ n $ -gram语言模型（LM）平滑来研究RNN模型的有效存储深度。在一个小的语料库（UPenn Treebank，一百万字训练数据和10k词汇表）上的实验发现，与前馈和香草RNN模型相比，具有丢失的LSTM单元是编码$ n $ -gram状态的最佳模型。当保留句子独立性假设时，LSTM $ n $ -gram与$ n = 9 $的LSTM LM性能匹配，并且对于$ n = 13 $略优于它。当允许跨越句子的依赖性时，LSTM $ 13 $ -gram几乎匹配无限历史LSTM LM的困惑。与Katz或Kneser-Ney回退估计器不同，LSTM $ n-gram平滑也具有随着$ n $ -gram顺序的增加而改善的理想性质。使用多项分布作为训练目标，而不是通常的一个热门目标，对低$ n $ -gram指令只有一点好处。在十亿字基准上的实验表明，结果保持在较大规模上：对于短$ n $ -gram上下文的LSTM平滑不提供比传统N-gram模型显着的优势，它在长的上下文中变得有效（$ n> 5 $）;取决于任务和数据量，它可以匹配完全经常性的LSTM模型，大约$ n = 13 $。在对短格式文本进行建模时，这可能会有影响。语音搜索/查询LM。构建LSTM $ n $ -gram LM可能对一些实际情况有吸引力：$ n $ -gram LM中的状态可以简洁地用$（n-1）* 4 $ bytes来表示，存储上下文中单词的标识并且可以并行处理$ n $ -gram上下文的批处理。不利的是，由LSTM计算的$ n $ -gram上下文编码被丢弃，使得该模型比常规的经常性LSTM LM更昂贵。

##### URL
[https://arxiv.org/abs/1703.10724](https://arxiv.org/abs/1703.10724)

##### PDF
[https://arxiv.org/pdf/1703.10724](https://arxiv.org/pdf/1703.10724)

