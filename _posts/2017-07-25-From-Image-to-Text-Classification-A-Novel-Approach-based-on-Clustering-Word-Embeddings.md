---
layout: post
title: "From Image to Text Classification: A Novel Approach based on Clustering Word Embeddings"
date: 2017-07-25 17:29:18
categories: arXiv_CL
tags: arXiv_CL Image_Caption Text_Classification Embedding Classification
author: Andrei M. Butnaru, Radu Tudor Ionescu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel approach for text classification based on clustering word embeddings, inspired by the bag of visual words model, which is widely used in computer vision. After each word in a collection of documents is represented as word vector using a pre-trained word embeddings model, a k-means algorithm is applied on the word vectors in order to obtain a fixed-size set of clusters. The centroid of each cluster is interpreted as a super word embedding that embodies all the semantically related word vectors in a certain region of the embedding space. Every embedded word in the collection of documents is then assigned to the nearest cluster centroid. In the end, each document is represented as a bag of super word embeddings by computing the frequency of each super word embedding in the respective document. We also diverge from the idea of building a single vocabulary for the entire collection of documents, and propose to build class-specific vocabularies for better performance. Using this kind of representation, we report results on two text mining tasks, namely text categorization by topic and polarity classification. On both tasks, our model yields better performance than the standard bag of words.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的基于聚类词嵌入的文本分类方法，受到视觉词典模型的启发，在计算机视觉领域得到了广泛的应用。在使用预先训练的词嵌入模型将文档集合中的每个词表示为词向量之后，对词向量应用k均值算法以获得固定大小的集合集合。每个簇的质心被解释为超级字嵌入，其体现了嵌入空间的特定区域中的所有语义相关的字向量。然后将文档集合中的每个嵌入词分配到最近的集群质心。最后，通过计算每个超文本嵌入到相应文档中的频率，将每个文档表示为一个超级词嵌入的包。我们也不同于为整个文档集构建单个词汇表的想法，并建议构建特定于类的词汇表以获得更好的性能。使用这种表示方式，我们报告两个文本挖掘任务的结果，即按主题进行的文本分类和极性分类。在这两个任务上，我们的模型比标准的单词产生更好的性能。

##### URL
[https://arxiv.org/abs/1707.08098](https://arxiv.org/abs/1707.08098)

##### PDF
[https://arxiv.org/pdf/1707.08098](https://arxiv.org/pdf/1707.08098)

