---
layout: post
title: "Similarity Preserving Representation Learning for Time Series Clustering"
date: 2019-06-02 04:15:50
categories: arXiv_AI
tags: arXiv_AI Represenation_Learning
author: Qi Lei, Jinfeng Yi, Roman Vaculin, Lingfei Wu, Inderjit S. Dhillon
mathjax: true
---

* content
{:toc}

##### Abstract
A considerable amount of clustering algorithms take instance-feature matrices as their inputs. As such, they cannot directly analyze time series data due to its temporal nature, usually unequal lengths, and complex properties. This is a great pity since many of these algorithms are effective, robust, efficient, and easy to use. In this paper, we bridge this gap by proposing an efficient representation learning framework that is able to convert a set of time series with various lengths to an instance-feature matrix. In particular, we guarantee that the pairwise similarities between time series are well preserved after the transformation, thus the learned feature representation is particularly suitable for the time series clustering task. Given a set of $n$ time series, we first construct an $n\times n$ partially-observed similarity matrix by randomly sampling $\mathcal{O}(n \log n)$ pairs of time series and computing their pairwise similarities. We then propose an efficient algorithm that solves a non-convex and NP-hard problem to learn new features based on the partially-observed similarity matrix. By conducting extensive empirical studies, we show that the proposed framework is more effective, efficient, and flexible, compared to other state-of-the-art time series clustering methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1702.03584](http://arxiv.org/abs/1702.03584)

##### PDF
[http://arxiv.org/pdf/1702.03584](http://arxiv.org/pdf/1702.03584)

