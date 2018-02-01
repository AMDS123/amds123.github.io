---
layout: post
title: "Nested LSTMs"
date: 2018-01-31 05:52:08
categories: arXiv_CL
tags: arXiv_CL RNN Language_Model
author: Joel Ruben Antony Moniz, David Krueger
mathjax: true
---

* content
{:toc}

##### Abstract
We propose Nested LSTMs (NLSTM), a novel RNN architecture with multiple levels of memory. Nested LSTMs add depth to LSTMs via nesting as opposed to stacking. The value of a memory cell in an NLSTM is computed by an LSTM cell, which has its own inner memory cell. Specifically, instead of computing the value of the (outer) memory cell as $c^{outer}_t = f_t \odot c_{t-1} + i_t \odot g_t$, NLSTM memory cells use the concatenation $(f_t \odot c_{t-1}, i_t \odot g_t)$ as input to an inner LSTM (or NLSTM) memory cell, and set $c^{outer}_t$ = $h^{inner}_t$. Nested LSTMs outperform both stacked and single-layer LSTMs with similar numbers of parameters in our experiments on various character-level language modeling tasks, and the inner memories of an LSTM learn longer term dependencies compared with the higher-level units of a stacked LSTM.

##### Abstract (translated by Google)
我们提出嵌套式LSTM（NLSTM），一种具有多级内存的新型RNN架构。嵌套的LSTM通过嵌套添加深度到LSTM，而不是堆叠。在NLSTM中的存储器单元的值由具有其自己的内部存储器单元的LSTM单元计算。具体而言，NLSTM存储器单元不是将（外部）存储器单元的值计算为$，而是使用串联$（f_t \ odot c_ {t-1}，i_t \ odot g_t）$作为内部LSTM（或NLSTM）存储单元的输入，并设置$ c ^ {outer} _t $ = $ h ^ {inner} _t $。嵌套式LSTM在我们的各种特性语言建模任务的实验中，性能优于叠层和单层LSTM，参数数目相似，而LSTM的内部记忆与堆叠式LSTM的高层单元相比，学习到更长期的相关性。

##### URL
[http://arxiv.org/abs/1801.10308](http://arxiv.org/abs/1801.10308)

##### PDF
[http://arxiv.org/pdf/1801.10308](http://arxiv.org/pdf/1801.10308)

