---
layout: post
title: "Split-door criterion: Identification of causal effects through auxiliary outcomes"
date: 2018-06-14 13:09:13
categories: arXiv_AI
tags: arXiv_AI Recommendation
author: Amit Sharma, Jake M. Hofman, Duncan J. Watts
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method for estimating causal effects in time series data when fine-grained information about the outcome of interest is available. Specifically, we examine what we call the split-door setting, where the outcome variable can be split into two parts: one that is potentially affected by the cause being studied and another that is independent of it, with both parts sharing the same (unobserved) confounders. We show that under these conditions, the problem of identification reduces to that of testing for independence among observed variables, and present a method that uses this approach to automatically find subsets of the data that are causally identified. We demonstrate the method by estimating the causal impact of Amazon's recommender system on traffic to product pages, finding thousands of examples within the dataset that satisfy the split-door criterion. Unlike past studies based on natural experiments that were limited to a single product category, our method applies to a large and representative sample of products viewed on the site. In line with previous work, we find that the widely-used click-through rate (CTR) metric overestimates the causal impact of recommender systems; depending on the product category, we estimate that 50-80\% of the traffic attributed to recommender systems would have happened even without any recommendations. We conclude with guidelines for using the split-door criterion as well as a discussion of other contexts where the method can be applied.

##### Abstract (translated by Google)
我们提出了一种当关于感兴趣的结果的细粒度信息可用时估计时间序列数据中的因果效应的方法。具体来说，我们研究了我们所说的分裂门设置，其中结果变量可以分为两部分：一部分可能受所研究原因的影响，另一部分与其独立，两部分共享相同（未观测到）混杂因素。我们表明，在这些条件下，识别问题会降低到在观察变量之间测试独立性的问题，并提出一种使用此方法自动查找因果识别数据的子集的方法。我们通过估计亚马逊推荐系统对产品页面流量的因果影响来演示该方法，在数据集中找到数千个满足分门标准的示例。与以往仅限于单一产品类别的自然实验研究不同，我们的方法适用于在网站上查看的大量具有代表性的产品样品。根据之前的工作，我们发现广泛使用的点击率（CTR）指标高估了推荐系统的因果影响;根据产品类别的不同，我们估计即使没有任何建议，归因于推荐系统的流量的50-80％也会发生。我们以使用分门标准的准则结束，并讨论可应用该方法的其他上下文。

##### URL
[http://arxiv.org/abs/1611.09414](http://arxiv.org/abs/1611.09414)

##### PDF
[http://arxiv.org/pdf/1611.09414](http://arxiv.org/pdf/1611.09414)

