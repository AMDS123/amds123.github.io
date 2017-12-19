---
layout: post
title: "Parameterized Neural Network Language Models for Information Retrieval"
date: 2015-10-06 13:07:31
categories: arXiv_CL
tags: arXiv_CL Language_Model Detection Relation
author: Benjamin Piwowarski, Sylvain Lamprier, Nicolas Despres
mathjax: true
---

* content
{:toc}

##### Abstract
Information Retrieval (IR) models need to deal with two difficult issues, vocabulary mismatch and term dependencies. Vocabulary mismatch corresponds to the difficulty of retrieving relevant documents that do not contain exact query terms but semantically related terms. Term dependencies refers to the need of considering the relationship between the words of the query when estimating the relevance of a document. A multitude of solutions has been proposed to solve each of these two problems, but no principled model solve both. In parallel, in the last few years, language models based on neural networks have been used to cope with complex natural language processing tasks like emotion and paraphrase detection. Although they present good abilities to cope with both term dependencies and vocabulary mismatch problems, thanks to the distributed representation of words they are based upon, such models could not be used readily in IR, where the estimation of one language model per document (or query) is required. This is both computationally unfeasible and prone to over-fitting. Based on a recent work that proposed to learn a generic language model that can be modified through a set of document-specific parameters, we explore use of new neural network models that are adapted to ad-hoc IR tasks. Within the language model IR framework, we propose and study the use of a generic language model as well as a document-specific language model. Both can be used as a smoothing component, but the latter is more adapted to the document at hand and has the potential of being used as a full document language model. We experiment with such models and analyze their results on TREC-1 to 8 datasets.

##### Abstract (translated by Google)
信息检索（IR）模型需要处理两个难题，词汇不匹配和术语依赖。词汇不匹配对应于检索不包含确切查询词语但是语义相关词语的相关文档的难度。术语依赖性是指在估计文档的相关性时需要考虑查询词语之间的关系。已经提出了许多解决方案来解决这两个问题中的每一个，但是没有原理模型解决这两个问题。同时，在过去的几年里，基于神经网络的语言模型已经被用来应对复杂的自然语言处理任务，如情绪和释义检测。虽然他们提出了很好的能力来处理术语依赖和词汇不匹配问题，但是由于他们所基于的词的分布式表示，这样的模型不能在IR中被容易地使用，在IR中，每个文档（或查询） 是必须的。这在计算上是不可行的，并且倾向于过度拟合。基于最近的一项研究提出要学习一个通用语言模型，可以通过一组文档特定的参数进行修改，我们探索使用适合于特定IR任务的新的神经网络模型。在语言模型IR框架内，我们提出并研究了通用语言模型的使用以及文档特定的语言模型。两者都可以作为一个平滑的组件，但后者更适合于手头的文档，并有可能被用作一个完整的文档语言模型。我们试验这些模型，并分析他们在TREC-1到8数据集上的结果。

##### URL
[https://arxiv.org/abs/1510.01562](https://arxiv.org/abs/1510.01562)

##### PDF
[https://arxiv.org/pdf/1510.01562](https://arxiv.org/pdf/1510.01562)

