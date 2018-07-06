---
layout: post
title: "Global Transition-based Non-projective Dependency Parsing"
date: 2018-07-04 19:09:40
categories: arXiv_CL
tags: arXiv_CL RNN
author: Carlos G&#xf3;mez-Rodr&#xed;guez, Tianze Shi, Lillian Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Shi, Huang, and Lee (2017) obtained state-of-the-art results for English and Chinese dependency parsing by combining dynamic-programming implementations of transition-based dependency parsers with a minimal set of bidirectional LSTM features. However, their results were limited to projective parsing. In this paper, we extend their approach to support non-projectivity by providing the first practical implementation of the MH_4 algorithm, an $O(n^4)$ mildly nonprojective dynamic-programming parser with very high coverage on non-projective treebanks. To make MH_4 compatible with minimal transition-based feature sets, we introduce a transition-based interpretation of it in which parser items are mapped to sequences of transitions. We thus obtain the first implementation of global decoding for non-projective transition-based parsing, and demonstrate empirically that it is more effective than its projective counterpart in parsing a number of highly non-projective languages

##### Abstract (translated by Google)
Shi，Huang和Lee（2017）通过将基于转换的依赖解析器的动态编程实现与最小的双向LSTM特征组合在一起，获得了英语和中文依赖解析的最新结果。但是，他们的结果仅限于投影解析。在本文中，我们通过提供MH_4算法的第一个实际实现来扩展他们的方法以支持非投射性，这是一种$ O（n ^ 4）$温和的非投影动态编程解析器，在非投影树库上具有非常高的覆盖率。为了使MH_4与最小的基于转换的特征集兼容，我们引入了基于转换的解释，其中解析器项被映射到转换序列。因此，我们获得了基于非投影过渡的解析的全局解码的第一个实现，并且凭经验证明它在解析许多高度非投射语言时比它的投射对应物更有效。

##### URL
[http://arxiv.org/abs/1807.01745](http://arxiv.org/abs/1807.01745)

##### PDF
[http://arxiv.org/pdf/1807.01745](http://arxiv.org/pdf/1807.01745)

