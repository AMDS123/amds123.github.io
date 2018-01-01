---
layout: post
title: "Corpus specificity in LSA and Word2vec: the role of out-of-domain documents"
date: 2017-12-28 20:56:16
categories: arXiv_AI
tags: arXiv_AI Knowledge Embedding Language_Model Relation
author: Edgar Altszyler, Mariano Sigman, Diego Fernandez Slezak
mathjax: true
---

* content
{:toc}

##### Abstract
Latent Semantic Analysis (LSA) and Word2vec are some of the most widely used word embeddings. Despite the popularity of these techniques, the precise mechanisms by which they acquire new semantic relations between words remain unclear. In the present article we investigate whether LSA and Word2vec capacity to identify relevant semantic dimensions increases with size of corpus. One intuitive hypothesis is that the capacity to identify relevant dimensions should increase as the amount of data increases. However, if corpus size grow in topics which are not specific to the domain of interest, signal to noise ratio may weaken. Here we set to examine and distinguish these alternative hypothesis. To investigate the effect of corpus specificity and size in word-embeddings we study two ways for progressive elimination of documents: the elimination of random documents vs. the elimination of documents unrelated to a specific task. We show that Word2vec can take advantage of all the documents, obtaining its best performance when it is trained with the whole corpus. On the contrary, the specialization (removal of out-of-domain documents) of the training corpus, accompanied by a decrease of dimensionality, can increase LSA word-representation quality while speeding up the processing time. Furthermore, we show that the specialization without the decrease in LSA dimensionality can produce a strong performance reduction in specific tasks. From a cognitive-modeling point of view, we point out that LSA's word-knowledge acquisitions may not be efficiently exploiting higher-order co-occurrences and global relations, whereas Word2vec does.

##### Abstract (translated by Google)
潜在语义分析（LSA）和Word2vec是一些最广泛使用的词嵌入。尽管这些技术的普及，他们之间获得新的语义关系的确切机制仍不清楚。在本文中，我们调查LSA和Word2vec识别相关语义维度的能力是否随着语料库的大小而增加。一个直观的假设是，识别相关维度的能力应随着数据量的增加而增加。但是，如果语料库的规模在不属于特定领域的话题中增长，则信噪比可能会减弱。这里我们设定检查和区分这些替代假设。为了调查语料嵌入的语料库特征和大小的影响，我们研究了逐步消除文档的两种方法：消除随机文档与消除与特定任务无关的文档。我们表明，Word2vec可以利用所有的文件，获得其最好的表现，当它与整个语料库训练。相反，训练语料库的专业化（删除域外文档）伴随着维度的降低，可以在加快处理时间的同时提高LSA的文字表示质量。此外，我们表明，没有减少LSA维度的专业化可以在特定任务中产生强大的性能降低。从认知建模的角度来看，我们指出，LSA的单词知识获取可能不能有效地利用高阶共现和全球关系，而Word2vec则是如此。

##### URL
[https://arxiv.org/abs/1712.10054](https://arxiv.org/abs/1712.10054)

##### PDF
[https://arxiv.org/pdf/1712.10054](https://arxiv.org/pdf/1712.10054)

