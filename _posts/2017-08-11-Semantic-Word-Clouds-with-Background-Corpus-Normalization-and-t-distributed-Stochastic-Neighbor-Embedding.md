---
layout: post
title: "Semantic Word Clouds with Background Corpus Normalization and t-distributed Stochastic Neighbor Embedding"
date: 2017-08-11 15:19:53
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Erich Schubert, Andreas Spitz, Michael Weiler, Johanna Geiß, Michael Gertz
mathjax: true
---

* content
{:toc}

##### Abstract
Many word clouds provide no semantics to the word placement, but use a random layout optimized solely for aesthetic purposes. We propose a novel approach to model word significance and word affinity within a document, and in comparison to a large background corpus. We demonstrate its usefulness for generating more meaningful word clouds as a visual summary of a given document. We then select keywords based on their significance and construct the word cloud based on the derived affinity. Based on a modified t-distributed stochastic neighbor embedding (t-SNE), we generate a semantic word placement. For words that cooccur significantly, we include edges, and cluster the words according to their cooccurrence. For this we designed a scalable and memory-efficient sketch-based approach usable on commodity hardware to aggregate the required corpus statistics needed for normalization, and for identifying keywords as well as significant cooccurences. We empirically validate our approch using a large Wikipedia corpus.

##### Abstract (translated by Google)
许多单词云对单词放置没有提供任何语义，而是使用仅针对美学目的进行了优化的随机布局。我们提出了一种新颖的方法来模拟文档中的单词重要性和单词亲和力，并与大型背景语料库进行比较。我们展示了它作为给定文档的可视摘要来生成更有意义的词云的有用性。然后，我们根据它们的意义选择关键字，并基于派生的亲和力构建词云。基于改进的t分布随机相邻嵌入（t-SNE），我们生成语义词的位置。对于共同显着的单词，我们包括边缘，并根据它们的共现将这些单词聚类在一起。为此，我们设计了一种可扩展的，高效的基于草图的方法，可用于商品硬件，以汇总所需的归一化所需的语料库统计信息，以及识别关键字以及重要的共同作用。我们用经验丰富的维基百科语料库验证了我们的正确性。

##### URL
[https://arxiv.org/abs/1708.03569](https://arxiv.org/abs/1708.03569)

##### PDF
[https://arxiv.org/pdf/1708.03569](https://arxiv.org/pdf/1708.03569)

