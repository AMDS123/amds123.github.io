---
layout: post
title: "TGSum: Build Tweet Guided Multi-Document Summarization Dataset"
date: 2015-11-26 15:22:54
categories: arXiv_CL
tags: arXiv_CL Summarization
author: Ziqiang Cao, Chengyao Chen, Wenjie Li, Sujian Li, Furu Wei, Ming Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
The development of summarization research has been significantly hampered by the costly acquisition of reference summaries. This paper proposes an effective way to automatically collect large scales of news-related multi-document summaries with reference to social media's reactions. We utilize two types of social labels in tweets, i.e., hashtags and hyper-links. Hashtags are used to cluster documents into different topic sets. Also, a tweet with a hyper-link often highlights certain key points of the corresponding document. We synthesize a linked document cluster to form a reference summary which can cover most key points. To this aim, we adopt the ROUGE metrics to measure the coverage ratio, and develop an Integer Linear Programming solution to discover the sentence set reaching the upper bound of ROUGE. Since we allow summary sentences to be selected from both documents and high-quality tweets, the generated reference summaries could be abstractive. Both informativeness and readability of the collected summaries are verified by manual judgment. In addition, we train a Support Vector Regression summarizer on DUC generic multi-document summarization benchmarks. With the collected data as extra training resource, the performance of the summarizer improves a lot on all the test sets. We release this dataset for further research.

##### Abstract (translated by Google)
摘要研究的发展受到昂贵的参考摘要收购的严重阻碍。本文针对社交媒体的反应，提出一种自动收集大规模新闻相关多文档摘要的有效方法。我们在推文中使用了两种类型的社交标签，即主题标签和超链接。散列标签用于将文档聚类成不同的主题集。此外，带有超链接的推文通常会突出显示相应文档的某些关键点。我们综合链接文档集群，形成一个可以覆盖大多数关键点的参考摘要。为此，我们采用ROUGE度量度量覆盖率，并开发整数线性规划解决方案来发现达到ROUGE上限的句子集。由于我们允许从文档和高质量的推文中选择摘要句子，因此生成的参考摘要可能是抽象的。所收集摘要的信息量和可读性都通过人工判断来验证。此外，我们还对DUC通用多文档汇总基准进行了支持向量回归总结。将所收集的数据作为额外的培训资源，汇总器的性能在所有的测试集上都有很大提高。我们发布这个数据集进行进一步的研究。

##### URL
[https://arxiv.org/abs/1511.08417](https://arxiv.org/abs/1511.08417)

##### PDF
[https://arxiv.org/pdf/1511.08417](https://arxiv.org/pdf/1511.08417)

