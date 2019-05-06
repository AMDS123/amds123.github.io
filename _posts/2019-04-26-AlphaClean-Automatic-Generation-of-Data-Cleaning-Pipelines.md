---
layout: post
title: "AlphaClean: Automatic Generation of Data Cleaning Pipelines"
date: 2019-04-26 13:07:53
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Sanjay Krishnan, Eugene Wu
mathjax: true
---

* content
{:toc}

##### Abstract
The analyst effort in data cleaning is gradually shifting away from the design of hand-written scripts to building and tuning complex pipelines of automated data cleaning libraries. Hyper-parameter tuning for data cleaning is very different than hyper-parameter tuning for machine learning since the pipeline components and objective functions have structure that tuning algorithms can exploit. This paper proposes a framework, called AlphaClean, that rethinks parameter tuning for data cleaning pipelines. AlphaClean provides users with a rich library to define data quality measures with weighted sums of SQL aggregate queries. AlphaClean applies generate-then-search framework where each pipelined cleaning operator contributes candidate transformations to a shared pool. Asynchronously, in separate threads, a search algorithm sequences them into cleaning pipelines that maximize the user-defined quality measures. This architecture allows AlphaClean to apply a number of optimizations including incremental evaluation of the quality measures and learning dynamic pruning rules to reduce the search space. Our experiments on real and synthetic benchmarks suggest that AlphaClean finds solutions of up-to 9x higher quality than naively applying state-of-the-art parameter tuning methods, is significantly more robust to straggling data cleaning methods and redundancy in the data cleaning library, and can incorporate state-of-the-art cleaning systems such as HoloClean as cleaning operators.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.11827](https://arxiv.org/abs/1904.11827)

##### PDF
[https://arxiv.org/pdf/1904.11827](https://arxiv.org/pdf/1904.11827)

