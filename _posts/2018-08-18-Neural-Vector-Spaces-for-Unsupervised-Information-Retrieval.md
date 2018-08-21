---
layout: post
title: "Neural Vector Spaces for Unsupervised Information Retrieval"
date: 2018-08-18 13:44:56
categories: arXiv_CL
tags: arXiv_CL Language_Model Gradient_Descent
author: Christophe Van Gysel, Maarten de Rijke, Evangelos Kanoulas
mathjax: true
---

* content
{:toc}

##### Abstract
We propose the Neural Vector Space Model (NVSM), a method that learns representations of documents in an unsupervised manner for news article retrieval. In the NVSM paradigm, we learn low-dimensional representations of words and documents from scratch using gradient descent and rank documents according to their similarity with query representations that are composed from word representations. We show that NVSM performs better at document ranking than existing latent semantic vector space methods. The addition of NVSM to a mixture of lexical language models and a state-of-the-art baseline vector space model yields a statistically significant increase in retrieval effectiveness. Consequently, NVSM adds a complementary relevance signal. Next to semantic matching, we find that NVSM performs well in cases where lexical matching is needed. 
 NVSM learns a notion of term specificity directly from the document collection without feature engineering. We also show that NVSM learns regularities related to Luhn significance. Finally, we give advice on how to deploy NVSM in situations where model selection (e.g., cross-validation) is infeasible. We find that an unsupervised ensemble of multiple models trained with different hyperparameter values performs better than a single cross-validated model. Therefore, NVSM can safely be used for ranking documents without supervised relevance judgments.

##### Abstract (translated by Google)
我们提出了神经向量空间模型（NVSM），这种方法以无人监督的方式学习文档的表示以用于新闻文章检索。在NVSM范例中，我们使用梯度下降从头开始学习单词和文档的低维表示，并根据它们与由单词表示组成的查询表示的相似性对文档进行排序。我们表明NVSM在文档排名方面的表现优于现有的潜在语义向量空间方法。将NVSM添加到词汇语言模型和最先进的基线向量空间模型的混合中，可以在统计上显着提高检索效率。因此，NVSM添加了互补的相关信号。在语义匹配之后，我们发现NVSM在需要词汇匹配的情况下表现良好。
 NVSM在没有特征工程的情况下直接从文档集合中学习术语特异性的概念。我们还表明，NVSM学习与Luhn重要性相关的规律性。最后，我们就如何在模型选择（例如，交叉验证）不可行的情况下部署NVSM提供建议。我们发现，使用不同超参数值训练的多个模型的无监督集合比单个交叉验证模型执行得更好。因此，NVSM可以安全地用于排序文档而无需监督相关性判断。

##### URL
[http://arxiv.org/abs/1708.02702](http://arxiv.org/abs/1708.02702)

##### PDF
[http://arxiv.org/pdf/1708.02702](http://arxiv.org/pdf/1708.02702)

