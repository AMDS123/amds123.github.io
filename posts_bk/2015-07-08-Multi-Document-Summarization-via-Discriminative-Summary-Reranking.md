---
layout: post
title: "Multi-Document Summarization via Discriminative Summary Reranking"
date: 2015-07-08 08:26:23
categories: arXiv_CL
tags: arXiv_CL Summarization Quantitative
author: Xiaojun Wan, Ziqiang Cao, Furu Wei, Sujian Li, Ming Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Existing multi-document summarization systems usually rely on a specific summarization model (i.e., a summarization method with a specific parameter setting) to extract summaries for different document sets with different topics. However, according to our quantitative analysis, none of the existing summarization models can always produce high-quality summaries for different document sets, and even a summarization model with good overall performance may produce low-quality summaries for some document sets. On the contrary, a baseline summarization model may produce high-quality summaries for some document sets. Based on the above observations, we treat the summaries produced by different summarization models as candidate summaries, and then explore discriminative reranking techniques to identify high-quality summaries from the candidates for difference document sets. We propose to extract a set of candidate summaries for each document set based on an ILP framework, and then leverage Ranking SVM for summary reranking. Various useful features have been developed for the reranking process, including word-level features, sentence-level features and summary-level features. Evaluation results on the benchmark DUC datasets validate the efficacy and robustness of our proposed approach.

##### Abstract (translated by Google)
现有的多文档摘要系统通常依靠特定的摘要模型（即具有特定参数设置的摘要方法）来为具有不同主题的不同文档集提取概要。然而，根据我们的定量分析，现有的摘要模型都不能总是为不同的文档集产生高质量的摘要，即使是总体性能良好的摘要模型也可能会产生低质量的摘要。相反，基线汇总模型可以为某些文件集产生高质量的汇总。基于上述观察，我们将不同摘要模型产生的摘要作为候选摘要，然后探索歧视性的重新排序技术，从差异文档集的候选人中识别出高质量摘要。我们建议基于ILP框架为每个文档集提取一组候选摘要，然后利用排名SVM进行总结重新排序。为重新调整过程开发了各种有用的功能，包括字级功能，句级功能和汇总级功能。基准DUC数据集的评估结果验证了我们提出的方法的有效性和鲁棒性。

##### URL
[https://arxiv.org/abs/1507.02062](https://arxiv.org/abs/1507.02062)

##### PDF
[https://arxiv.org/pdf/1507.02062](https://arxiv.org/pdf/1507.02062)

