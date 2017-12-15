---
layout: post
title: "Term-Class-Max-Support : A Simple Text Document Categorization Approach Using Term-Class Relevance Measure"
date: 2016-10-16 03:40:13
categories: arXiv_CL
tags: arXiv_CL Knowledge
author: D S Guru, Mahamad Suhil
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, a simple text categorization method using term-class relevance measures is proposed. Initially, text documents are processed to extract significant terms present in them. For every term extracted from a document, we compute its importance in preserving the content of a class through a novel term-weighting scheme known as Term_Class Relevance (TCR) measure proposed by Guru and Suhil (2015) [1]. In this way, for every term, its relevance for all the classes present in the corpus is computed and stored in the knowledgebase. During testing, the terms present in the test document are extracted and the term-class relevance of each term is obtained from the stored knowledgebase. To achieve quick search of term weights, Btree indexing data structure has been adapted. Finally, the class which receives maximum support in terms of term-class relevance is decided to be the class of the given test document. The proposed method works in logarithmic complexity in testing time and simple to implement when compared to any other text categorization techniques available in literature. The experiments conducted on various benchmarking datasets have revealed that the performance of the proposed method is satisfactory and encouraging.

##### Abstract (translated by Google)
本文提出了一种使用词类相关性度量的简单文本分类方法。最初，处理文本文档以提取其中的重要术语。对于从文档中提取的每一个术语，我们通过Guru和Suhil（2015）[1]提出的称为Term_Class Relevance（TCR）度量的新型术语加权方案来计算它在保存类别内容中的重要性。通过这种方式，对于每一个术语，它与语料库中存在的所有类别的相关性被计算并存储在知识库中。在测试期间，提取测试文档中存在的术语，并且从存储的知识库获得每个术语的术语类别相关性。为了快速搜索词权重，Btree索引数据结构已经被调整。最后，在术语类相关性方面得到最大支持的类被确定为给定的测试文档的类。与文献中可用的任何其他文本分类技术相比，所提出的方法在测试时间上对数复杂地工作并且易于实现。在各种基准数据集上进行的实验表明，所提出的方法的性能令人满意和令人鼓舞。

##### URL
[https://arxiv.org/abs/1610.04814](https://arxiv.org/abs/1610.04814)

##### PDF
[https://arxiv.org/pdf/1610.04814](https://arxiv.org/pdf/1610.04814)

