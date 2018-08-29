---
layout: post
title: "Open Set Chinese Character Recognition using Multi-typed Attributes"
date: 2018-08-27 18:53:31
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval CNN Classification Recognition
author: Sheng He, Lambert Schomaker
mathjax: true
---

* content
{:toc}

##### Abstract
Recognition of Off-line Chinese characters is still a challenging problem, especially in historical documents, not only in the number of classes extremely large in comparison to contemporary image retrieval methods, but also new unseen classes can be expected under open learning conditions (even for CNN). Chinese character recognition with zero or a few training samples is a difficult problem and has not been studied yet. In this paper, we propose a new Chinese character recognition method by multi-type attributes, which are based on pronunciation, structure and radicals of Chinese characters, applied to character recognition in historical books. This intermediate attribute code has a strong advantage over the common `one-hot' class representation because it allows for understanding complex and unseen patterns symbolically using attributes. First, each character is represented by four groups of attribute types to cover a wide range of character possibilities: Pinyin label, layout structure, number of strokes, three different input methods such as Cangjie, Zhengma and Wubi, as well as a four-corner encoding method. A convolutional neural network (CNN) is trained to learn these attributes. Subsequently, characters can be easily recognized by these attributes using a distance metric and a complete lexicon that is encoded in attribute space. We evaluate the proposed method on two open data sets: printed Chinese character recognition for zero-shot learning, historical characters for few-shot learning and a closed set: handwritten Chinese characters. Experimental results show a good general classification of seen classes but also a very promising generalization ability to unseen characters.

##### Abstract (translated by Google)
对离线汉字的识别仍然是一个具有挑战性的问题，特别是在历史文献中，不仅与当代图像检索方法相比，它的数量非常大，而且在开放学习条件下也可以预期新的看不见的类（即使对于CNN）。零训练样本或少量训练样本的汉字识别是一个难题，尚未研究过。在本文中，我们提出了一种基于汉字的发音，结构和字根的多类型属性的新汉字识别方法，应用于历史书籍中的字符识别。这个中间属性代码比常见的“one-hot”类表示具有强大的优势，因为它允许使用属性以符号方式理解复杂和不可见的模式。首先，每个字符由四组属性类型表示，以涵盖广泛的字符可能性：拼音标签，布局结构，笔画数，三种不同的输入方法，如仓颉，正马和五笔，以及一个四角编码方法。训练卷积神经网络（CNN）以学习这些属性。随后，使用距离度量和在属性空间中编码的完整词典，可以通过这些属性容易地识别字符。我们在两个开放数据集上评估所提出的方法：零射击学习的印刷汉字识别，少射击学习的历史特征和闭合集：手写汉字。实验结果表明，对于看到的类具有良好的一般分类，但对于看不见的字符也具有非常有希望的泛化能力。

##### URL
[http://arxiv.org/abs/1808.08993](http://arxiv.org/abs/1808.08993)

##### PDF
[http://arxiv.org/pdf/1808.08993](http://arxiv.org/pdf/1808.08993)

