---
layout: post
title: "Prior matters: simple and general methods for evaluating and improving topic quality in topic modeling"
date: 2017-10-14 18:25:03
categories: arXiv_SD
tags: arXiv_SD Inference Quantitative
author: Angela Fan, Finale Doshi-Velez, Luke Miratrix
mathjax: true
---

* content
{:toc}

##### Abstract
Latent Dirichlet Allocation (LDA) models trained without stopword removal often produce topics with high posterior probabilities on uninformative words, obscuring the underlying corpus content. Even when canonical stopwords are manually removed, uninformative words common in that corpus will still dominate the most probable words in a topic. In this work, we first show how the standard topic quality measures of coherence and pointwise mutual information act counter-intuitively in the presence of common but irrelevant words, making it difficult to even quantitatively identify situations in which topics may be dominated by stopwords. We propose an additional topic quality metric that targets the stopword problem, and show that it, unlike the standard measures, correctly correlates with human judgements of quality. We also propose a simple-to-implement strategy for generating topics that are evaluated to be of much higher quality by both human assessment and our new metric. This approach, a collection of informative priors easily introduced into most LDA-style inference methods, automatically promotes terms with domain relevance and demotes domain-specific stop words. We demonstrate this approach's effectiveness in three very different domains: Department of Labor accident reports, online health forum posts, and NIPS abstracts. Overall we find that current practices thought to solve this problem do not do so adequately, and that our proposal offers a substantial improvement for those interested in interpreting their topics as objects in their own right.

##### Abstract (translated by Google)
潜在的Dirichlet分配（LDA）模型训练没有停用词删除往往会产生非信息词后验概率高的话题，掩盖了潜在的语料库内容。即使当经典的停用词被人工删除时，该语料库中常见的无用词也将主宰词中最可能的单词。在这项工作中，我们首先展示了标准主题质量测量的连贯性和点状互信息是如何在存在共同但不相关的词的情况下直观地采取行动的，从而难以定量地确定主题可能被停用词所主导的情况。我们提出了一个针对停用词问题的额外话题质量度量，并且表明它与标准度量不同，正确地与人类对质量的判断相关联。我们还提出了一个简单实施的策略，用于生成主题，通过人类评估和我们的新指标评估其质量更高。这种方法是一个很容易引入到大多数LDA风格推断方法中的信息丰富的先验的集合，它自动地促进了与领域相关的术语，并降低了领域特定的停用词。我们在三个不同的领域证明了这种方法的有效性：劳工事故报告，在线健康论坛帖子和NIPS摘要。总的来说，我们发现目前认为解决这个问题的做法并不充分，而且我们的建议为那些有兴趣将自己的话题解释为对象的人提供了实质性的改进。

##### URL
[https://arxiv.org/abs/1701.03227](https://arxiv.org/abs/1701.03227)

##### PDF
[https://arxiv.org/pdf/1701.03227](https://arxiv.org/pdf/1701.03227)

