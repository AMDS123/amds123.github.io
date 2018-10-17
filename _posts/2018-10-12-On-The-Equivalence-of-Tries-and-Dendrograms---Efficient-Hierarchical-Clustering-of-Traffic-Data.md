---
layout: post
title: "On The Equivalence of Tries and Dendrograms - Efficient Hierarchical Clustering of Traffic Data"
date: 2018-10-12 05:02:29
categories: arXiv_AI
tags: arXiv_AI
author: Chia-Tung Kuo, Ian Davidson
mathjax: true
---

* content
{:toc}

##### Abstract
The widespread use of GPS-enabled devices generates voluminous and continuous amounts of traffic data but analyzing such data for interpretable and actionable insights poses challenges. A hierarchical clustering of the trips has many uses such as discovering shortest paths, common routes and often traversed areas. However, hierarchical clustering typically has time complexity of $O(n^2 \log n)$ where $n$ is the number of instances, and is difficult to scale to large data sets associated with GPS data. Furthermore, incremental hierarchical clustering is still a developing area. Prefix trees (also called tries) can be efficiently constructed and updated in linear time (in $n$). We show how a specially constructed trie can compactly store the trips and further show this trie is equivalent to a dendrogram that would have been built by classic agglomerative hierarchical algorithms using a specific distance metric. This allows creating hierarchical clusterings of GPS trip data and updating this hierarchy in linear time. %we can extract a meaningful kernel and can also interpret the structure as clusterings of differing granularity as one progresses down the tree. We demonstrate the usefulness of our proposed approach on a real world data set of half a million taxis' GPS traces, well beyond the capabilities of agglomerative clustering methods. Our work is not limited to trip data and can be used with other data with a string representation.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.05357](https://arxiv.org/abs/1810.05357)

##### PDF
[https://arxiv.org/pdf/1810.05357](https://arxiv.org/pdf/1810.05357)

