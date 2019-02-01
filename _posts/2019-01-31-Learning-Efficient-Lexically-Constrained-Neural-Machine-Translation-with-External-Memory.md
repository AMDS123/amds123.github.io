---
layout: post
title: "Learning Efficient Lexically-Constrained Neural Machine Translation with External Memory"
date: 2019-01-31 13:26:28
categories: arXiv_AI
tags: arXiv_AI Attention NMT
author: Ya Li, Xinyu Liu, Dan Liu, Xueqiang Zhang, Junhua Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Recent years has witnessed dramatic progress of neural machine translation (NMT), however, the method of manually guiding the translation procedure remains to be better explored. Previous works proposed to handle such problem through lexcially-constrained beam search in the decoding phase. Unfortunately, these lexically-constrained beam search methods suffer two fatal disadvantages: high computational complexity and hard beam search which generates unexpected translations. In this paper, we propose to learn the ability of lexically-constrained translation with external memory, which can overcome the above mentioned disadvantages. For the training process, automatically extracted phrase pairs are extracted from alignment and sentence parsing, then further be encoded into an external memory. This memory is then used to provide lexically-constrained information for training through a memory-attention machanism. Various experiments are conducted on WMT Chinese to English and English to German tasks. All the results can demonstrate the effectiveness of our method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.11344](http://arxiv.org/abs/1901.11344)

##### PDF
[http://arxiv.org/pdf/1901.11344](http://arxiv.org/pdf/1901.11344)

