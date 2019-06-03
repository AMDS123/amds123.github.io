---
layout: post
title: "Ordinal Bucketing for Game Trees using Dynamic Quantile Approximation"
date: 2019-05-31 07:35:03
categories: arXiv_AI
tags: arXiv_AI
author: Tobias Joppen, Tilman Str&#xfc;big, Johannes F&#xfc;rnkranz
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a simple and cheap ordinal bucketing algorithm that approximately generates $q$-quantiles from an incremental data stream. The bucketing is done dynamically in the sense that the amount of buckets $q$ increases with the number of seen samples. We show how this can be used in Ordinal Monte Carlo Tree Search (OMCTS) to yield better bounds on time and space complexity, especially in the presence of noisy rewards. Besides complexity analysis and quality tests of quantiles, we evaluate our method using OMCTS in the General Video Game Framework (GVGAI). Our results demonstrate its dominance over vanilla Monte Carlo Tree Search in the presence of noise, where OMCTS without bucketing has a very bad time and space complexity.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.13449](http://arxiv.org/abs/1905.13449)

##### PDF
[http://arxiv.org/pdf/1905.13449](http://arxiv.org/pdf/1905.13449)

