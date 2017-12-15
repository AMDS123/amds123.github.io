---
layout: post
title: "Neural Vector Spaces for Unsupervised Information Retrieval"
date: 2017-11-13 14:26:58
categories: arXiv_CL
tags: arXiv_CL Language_Model Gradient_Descent
author: Christophe Van Gysel, Maarten de Rijke, Evangelos Kanoulas
mathjax: true
---

* content
{:toc}

##### Abstract
We propose the Neural Vector Space Model (NVSM), a method that learns representations of documents in an unsupervised manner for news article retrieval. In the NVSM paradigm, we learn low-dimensional representations of words and documents from scratch using gradient descent and rank documents according to their similarity with query representations that are composed from word representations. We show that NVSM performs better at document ranking than existing latent semantic vector space methods. The addition of NVSM to a mixture of lexical language models and a state-of-the-art baseline vector space model yields a statistically significant increase in retrieval effectiveness. Consequently, NVSM adds a complementary relevance signal. Next to semantic matching, we find that NVSM performs well in cases where lexical matching is needed. NVSM learns a notion of term specificity directly from the document collection without feature engineering. We also show that NVSM learns regularities related to Luhn significance. Finally, we give advice on how to deploy NVSM in situations where model selection (e.g., cross-validation) is infeasible. We find that an unsupervised ensemble of multiple models trained with different hyperparameter values performs better than a single cross-validated model. Therefore, NVSM can safely be used for ranking documents without supervised relevance judgments.

##### Abstract (translated by Google)
我们提出神经向量空间模型（NVSM），一种以无监督的方式学习新闻文章检索的文档表示方法。在NVSM范例中，我们使用梯度下降从零开始学习单词和文档的低维表示，并根据它们与由词表示组成的查询表示的相似度对文档进行排序。我们证明NVSM在文档排名方面比现有的潜在语义向量空间方法更好。将NVSM添加到词汇语言模型和最先进的基线向量空间模型的混合中，可以在检索效率方面获得统计学显着的提高。因此，NVSM增加了一个互补的相关信号。除语义匹配之外，我们发现NVSM在需要词法匹配的情况下表现良好。 NVSM直接从文档集合中学习术语特征的概念，而不需要特征工程。我们还显示，NVSM学习与Luhn重要性相关的规律性。最后，我们给出如何在模型选择（例如交叉验证）不可行的情况下部署NVSM的建议。我们发现，使用不同的超参数值训练的多模型的无监督集成比单个交叉验证的模型更好。因此，NVSM可以安全地用于排序的文件没有监督的相关性判断。

##### URL
[https://arxiv.org/abs/1708.02702](https://arxiv.org/abs/1708.02702)

##### PDF
[https://arxiv.org/pdf/1708.02702](https://arxiv.org/pdf/1708.02702)

