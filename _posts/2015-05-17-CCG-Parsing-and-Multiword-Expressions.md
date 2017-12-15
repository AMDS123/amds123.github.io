---
layout: post
title: "CCG Parsing and Multiword Expressions"
date: 2015-05-17 17:26:36
categories: arXiv_CL
tags: arXiv_CL Recognition
author: Miryam de Lhoneux
mathjax: true
---

* content
{:toc}

##### Abstract
This thesis presents a study about the integration of information about Multiword Expressions (MWEs) into parsing with Combinatory Categorial Grammar (CCG). We build on previous work which has shown the benefit of adding information about MWEs to syntactic parsing by implementing a similar pipeline with CCG parsing. More specifically, we collapse MWEs to one token in training and test data in CCGbank, a corpus which contains sentences annotated with CCG derivations. Our collapsing algorithm however can only deal with MWEs when they form a constituent in the data which is one of the limitations of our approach. We study the effect of collapsing training and test data. A parsing effect can be obtained if collapsed data help the parser in its decisions and a training effect can be obtained if training on the collapsed data improves results. We also collapse the gold standard and show that our model significantly outperforms the baseline model on our gold standard, which indicates that there is a training effect. We show that the baseline model performs significantly better on our gold standard when the data are collapsed before parsing than when the data are collapsed after parsing which indicates that there is a parsing effect. We show that these results can lead to improved performance on the non-collapsed standard benchmark although we fail to show that it does so significantly. We conclude that despite the limited settings, there are noticeable improvements from using MWEs in parsing. We discuss ways in which the incorporation of MWEs into parsing can be improved and hypothesize that this will lead to more substantial results. We finally show that turning the MWE recognition part of the pipeline into an experimental part is a useful thing to do as we obtain different results with different recognizers.

##### Abstract (translated by Google)
本文提出了一个关于将多词表达式（MWE）的信息集成到组合分类语法（CCG）解析中的研究。我们在前面的工作的基础上，通过实现一个类似的CCG解析流水线，显示了将MWE的信息添加到句法分析中的好处。更具体地说，我们在CCGbank的一个包含句子注释的CCGbank的训练和测试数据中将MWE折叠成一个标记。然而，我们的折叠算法只能在MWE构成数据时处理MWE，这是我们方法的局限性之一。我们研究折叠训练和测试数据的效果。如果折叠数据帮助解析器做出决定，则可以获得解析效果，并且如果对折叠数据进行训练可以改善结果，则可以获得训练效果。我们也摧毁了黄金标准，显示我们的模型明显优于我们黄金标准的基线模型，这表明存在培训效应。我们发现基准模型在解析之前折叠的数据比在解析之后折叠的数据表示存在解析效果时在我们的黄金标准上表现得更好。我们表明，这些结果可以导致未折叠标准基准测试的性能得到提高，尽管我们未能证明它是如此显着。我们的结论是，尽管设置有限，但在解析中使用MWE有显着的改进。我们讨论如何将MWE纳入解析的方法，并假设这将导致更多的实质性结果。我们最终表明，把MWE识别部分转换成实验部分是一个有用的事情，因为我们获得不同的识别结果。

##### URL
[https://arxiv.org/abs/1505.04420](https://arxiv.org/abs/1505.04420)

##### PDF
[https://arxiv.org/pdf/1505.04420](https://arxiv.org/pdf/1505.04420)

