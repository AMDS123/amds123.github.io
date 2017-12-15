---
layout: post
title: "Incremental Parsing with Minimal Features Using Bi-Directional LSTM"
date: 2016-06-21 03:20:59
categories: arXiv_CL
tags: arXiv_CL RNN
author: James Cross, Liang Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, neural network approaches for parsing have largely automated the combination of individual features, but still rely on (often a larger number of) atomic features created from human linguistic intuition, and potentially omitting important global context. To further reduce feature engineering to the bare minimum, we use bi-directional LSTM sentence representations to model a parser state with only three sentence positions, which automatically identifies important aspects of the entire sentence. This model achieves state-of-the-art results among greedy dependency parsers for English. We also introduce a novel transition system for constituency parsing which does not require binarization, and together with the above architecture, achieves state-of-the-art results among greedy parsers for both English and Chinese.

##### Abstract (translated by Google)
最近，解析的神经网络方法在很大程度上自动化了各个特征的组合，但仍依赖于（通常是大量的）从人类语言直觉创造的原子特征，并可能忽略重要的全球背景。为了进一步将特征工程减少到最低限度，我们使用双向LSTM句子表示来模拟只有三个句子位置的解析器状态，这自动识别整个句子的重要方面。该模型在英语的贪婪依赖分析器中实现了最先进的结果。我们还介绍了一种不需要二进制化的用户选择分析过渡系统，并结合上述体系结构，实现了英汉两种贪婪分析器的最新成果。

##### URL
[https://arxiv.org/abs/1606.06406](https://arxiv.org/abs/1606.06406)

##### PDF
[https://arxiv.org/pdf/1606.06406](https://arxiv.org/pdf/1606.06406)

