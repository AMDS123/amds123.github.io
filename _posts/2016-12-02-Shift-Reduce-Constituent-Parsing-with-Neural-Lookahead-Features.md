---
layout: post
title: "Shift-Reduce Constituent Parsing with Neural Lookahead Features"
date: 2016-12-02 04:55:24
categories: arXiv_CL
tags: arXiv_CL RNN
author: Jiangming Liu, Yue Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Transition-based models can be fast and accurate for constituent parsing. Compared with chart-based models, they leverage richer features by extracting history information from a parser stack, which spans over non-local constituents. On the other hand, during incremental parsing, constituent information on the right hand side of the current word is not utilized, which is a relative weakness of shift-reduce parsing. To address this limitation, we leverage a fast neural model to extract lookahead features. In particular, we build a bidirectional LSTM model, which leverages the full sentence information to predict the hierarchy of constituents that each word starts and ends. The results are then passed to a strong transition-based constituent parser as lookahead features. The resulting parser gives 1.3% absolute improvement in WSJ and 2.3% in CTB compared to the baseline, given the highest reported accuracies for fully-supervised parsing.

##### Abstract (translated by Google)
基于转换的模型可以快速准确地进行组成分析。与基于图表的模型相比，它们通过从解析器堆栈中提取历史信息来利用更丰富的功能，解析器堆栈跨越非本地组成部分。另一方面，在增量解析过程中，当前单词右侧的组成信息未被利用，这是移位 - 归约解析的一个相对弱点。为了解决这个限制，我们利用快速神经模型来提取先行特征。特别是，我们建立了一个双向LSTM模型，它利用完整的句子信息来预测每个单词开始和结束的成分的层次结构。然后将结果作为先行功能传递给强大的基于转换的组成分析器。由于完全监督解析的报告精度最高，所以得到的解析器与WSDL相比，在WSJ和CTB中的绝对改进为1.3％，CTB为2.3％。

##### URL
[https://arxiv.org/abs/1612.00567](https://arxiv.org/abs/1612.00567)

##### PDF
[https://arxiv.org/pdf/1612.00567](https://arxiv.org/pdf/1612.00567)

