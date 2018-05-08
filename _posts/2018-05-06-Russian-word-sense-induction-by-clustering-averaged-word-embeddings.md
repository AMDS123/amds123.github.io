---
layout: post
title: "Russian word sense induction by clustering averaged word embeddings"
date: 2018-05-06 18:25:12
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Andrey Kutuzov
mathjax: true
---

* content
{:toc}

##### Abstract
The paper reports our participation in the shared task on word sense induction and disambiguation for the Russian language (RUSSE-2018). Our team was ranked 2nd for the wiki-wiki dataset (containing mostly homonyms) and 5th for the bts-rnc and active-dict datasets (containing mostly polysemous words) among all 19 participants. 
 The method we employed was extremely naive. It implied representing contexts of ambiguous words as averaged word embedding vectors, using off-the-shelf pre-trained distributional models. Then, these vector representations were clustered with mainstream clustering techniques, thus producing the groups corresponding to the ambiguous word senses. As a side result, we show that word embedding models trained on small but balanced corpora can be superior to those trained on large but noisy data - not only in intrinsic evaluation, but also in downstream tasks like word sense induction.

##### Abstract (translated by Google)
该论文报告我们参与了俄语语义感应和消歧的共同任务（RUSSE-2018）。我们的团队在所有19位参与者中排名第2位，包含维基百科的数据集（包含大部分同音异义词），第5位为bts-rnc和主动词典数据集（主要含多义词）。
 我们采用的方法非常天真。它意味着使用现成的预先训练的分布式模型将歧义词的上下文表示为平均词嵌入向量。然后，将这些向量表示与主流聚类技术聚类，从而产生对应于模糊词义的组。作为一个副作用，我们表明，在小而平衡的语料库上训练的单词嵌入模型可能优于那些训练大量但有噪音数据的词 - 不仅在内在评估中，而且在像词义感应这样的下游任务中。

##### URL
[http://arxiv.org/abs/1805.02258](http://arxiv.org/abs/1805.02258)

##### PDF
[http://arxiv.org/pdf/1805.02258](http://arxiv.org/pdf/1805.02258)

