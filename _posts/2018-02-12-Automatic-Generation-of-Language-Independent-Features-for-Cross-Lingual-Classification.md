---
layout: post
title: "Automatic Generation of Language-Independent Features for Cross-Lingual Classification"
date: 2018-02-12 13:20:57
categories: arXiv_CL
tags: arXiv_CL Ontology Classification
author: Sarai Duek, Shaul Markovitch
mathjax: true
---

* content
{:toc}

##### Abstract
Many applications require categorization of text documents using predefined categories. The main approach to performing text categorization is learning from labeled examples. For many tasks, it may be difficult to find examples in one language but easy in others. The problem of learning from examples in one or more languages and classifying (categorizing) in another is called cross-lingual learning. In this work, we present a novel approach that solves the general cross-lingual text categorization problem. Our method generates, for each training document, a set of language-independent features. Using these features for training yields a language-independent classifier. At the classification stage, we generate language-independent features for the unlabeled document, and apply the classifier on the new representation. 
 To build the feature generator, we utilize a hierarchical language-independent ontology, where each concept has a set of support documents for each language involved. In the preprocessing stage, we use the support documents to build a set of language-independent feature generators, one for each language. The collection of these generators is used to map any document into the language-independent feature space. 
 Our methodology works on the most general cross-lingual text categorization problems, being able to learn from any mix of languages and classify documents in any other language. We also present a method for exploiting the hierarchical structure of the ontology to create virtual supporting documents for languages that do not have them. We tested our method, using Wikipedia as our ontology, on the most commonly used test collections in cross-lingual text categorization, and found that it outperforms existing methods.

##### Abstract (translated by Google)
许多应用程序需要使用预定义的类别对文本文档进行分类。执行文本分类的主要方法是从标记的例子中学习。对于许多任务来说，可能很难用一种语言找到例子，但在其他语言中很容易。从一种或多种语言的例子中学习并在另一种语言中分类（分类）的问题称为跨语言学习。在这项工作中，我们提出了一种解决一般跨语言文本分类问题的新方法。我们的方法为每个培训文档生成一组与语言无关的功能。使用这些功能进行训练会产生一个与语言无关的分类器。在分类阶段，我们为未标记的文档生成与语言无关的特征，并将分类器应用于新的表示。
 为了构建特征生成器，我们使用了一个与语言无关的分层本体，其中每个概念都有一套针对每种语言的支持文档。在预处理阶段，我们使用支持文档来构建一组与语言无关的特征生成器，每种语言都有一个。这些生成器的集合用于将任何文档映射到与语言无关的特征空间。
 我们的方法论适用于最常见的跨语言文本分类问题，能够从任何语言混合中学习，并以任何其他语言对文档进行分类。我们还提出了一种利用本体的分层结构来为没有它们的语言创建虚拟支持文档的方法。我们使用维基百科作为我们的本体论测试了我们的方法，并将其用于跨语言文本分类中最常用的测试集合，并发现它的性能优于现有的方法。

##### URL
[http://arxiv.org/abs/1802.04028](http://arxiv.org/abs/1802.04028)

##### PDF
[http://arxiv.org/pdf/1802.04028](http://arxiv.org/pdf/1802.04028)

