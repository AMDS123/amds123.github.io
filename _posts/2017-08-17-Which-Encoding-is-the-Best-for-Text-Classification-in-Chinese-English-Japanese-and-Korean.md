---
layout: post
title: "Which Encoding is the Best for Text Classification in Chinese, English, Japanese and Korean?"
date: 2017-08-17 00:34:08
categories: arXiv_CL
tags: arXiv_CL Segmentation Text_Classification Embedding CNN Classification
author: Xiang Zhang, Yann LeCun
mathjax: true
---

* content
{:toc}

##### Abstract
This article offers an empirical study on the different ways of encoding Chinese, Japanese, Korean (CJK) and English languages for text classification. Different encoding levels are studied, including UTF-8 bytes, characters, words, romanized characters and romanized words. For all encoding levels, whenever applicable, we provide comparisons with linear models, fastText and convolutional networks. For convolutional networks, we compare between encoding mechanisms using character glyph images, one-hot (or one-of-n) encoding, and embedding. In total there are 473 models, using 14 large-scale text classification datasets in 4 languages including Chinese, English, Japanese and Korean. Some conclusions from these results include that byte-level one-hot encoding based on UTF-8 consistently produces competitive results for convolutional networks, that word-level n-grams linear models are competitive even without perfect word segmentation, and that fastText provides the best result using character-level n-gram encoding but can overfit when the features are overly rich.

##### Abstract (translated by Google)
本文对中文，日文，韩文（CJK）和英文文本分类的不同编码方式进行了实证研究。研究了不同的编码级别，包括UTF-8字节，字符，单词，罗马字符和罗马字。对于所有编码级别，只要适用，我们提供与线性模型，fastText和卷积网络的比较。对于卷积网络，我们比较使用字符字形图像的编码机制，单热编码（或单编码）编码和嵌入。总共有473个模型，使用包括中文，英文，日文和韩文在内的4种语言的14个大型文本分类数据集。从这些结果得出的一些结论包括，基于UTF-8的字节级单热编码一致地为卷积网络产生竞争结果，即使没有完美的分词，字级n-gram线性模型也是有竞争力的，并且fastText提供了最好的结果使用字符级别的n-gram编码，但是当特征过于丰富时可以适合。

##### URL
[https://arxiv.org/abs/1708.02657](https://arxiv.org/abs/1708.02657)

##### PDF
[https://arxiv.org/pdf/1708.02657](https://arxiv.org/pdf/1708.02657)

