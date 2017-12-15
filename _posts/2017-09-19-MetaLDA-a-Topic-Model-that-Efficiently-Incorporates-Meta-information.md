---
layout: post
title: "MetaLDA: a Topic Model that Efficiently Incorporates Meta information"
date: 2017-09-19 12:09:21
categories: arXiv_CL
tags: arXiv_CL Sparse Embedding
author: He Zhao, Lan Du, Wray Buntine, Gang Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Besides the text content, documents and their associated words usually come with rich sets of meta informa- tion, such as categories of documents and semantic/syntactic features of words, like those encoded in word embeddings. Incorporating such meta information directly into the generative process of topic models can improve modelling accuracy and topic quality, especially in the case where the word-occurrence information in the training data is insufficient. In this paper, we present a topic model, called MetaLDA, which is able to leverage either document or word meta information, or both of them jointly. With two data argumentation techniques, we can derive an efficient Gibbs sampling algorithm, which benefits from the fully local conjugacy of the model. Moreover, the algorithm is favoured by the sparsity of the meta information. Extensive experiments on several real world datasets demonstrate that our model achieves comparable or improved performance in terms of both perplexity and topic quality, particularly in handling sparse texts. In addition, compared with other models using meta information, our model runs significantly faster.

##### Abstract (translated by Google)
除文本内容之外，文档及其关联词通常还有丰富的元信息集合，如文档的类别和词的语义/句法特征，如词嵌入中的编码。将这样的元信息直接结合到主题模型的生成过程中可以提高建模精度和主题质量，特别是在训练数据中的词语出现信息不足的情况下。在本文中，我们提出了一个称为MetaLDA的主题模型，它可以共同利用文档或词汇元信息，或者两者兼而有之。利用两种数据论证技术，我们可以推导出一种高效的吉布斯采样算法，该算法从模型的完全局部共轭中受益。而且，该算法受到元信息稀疏性的青睐。在多个现实世界的数据集上的大量实验表明，我们的模型在混淆性和主题质量方面都达到了可比或改进的性能，特别是在处理稀疏文本方面。另外，与使用元信息的其他模型相比，我们的模型运行速度更快。

##### URL
[https://arxiv.org/abs/1709.06365](https://arxiv.org/abs/1709.06365)

##### PDF
[https://arxiv.org/pdf/1709.06365](https://arxiv.org/pdf/1709.06365)

