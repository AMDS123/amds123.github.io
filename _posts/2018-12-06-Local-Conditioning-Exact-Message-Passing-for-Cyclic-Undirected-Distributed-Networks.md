---
layout: post
title: "Local Conditioning: Exact Message Passing for Cyclic Undirected Distributed Networks"
date: 2018-12-06 16:19:53
categories: arXiv_AI
tags: arXiv_AI
author: Matthew G. Reyes
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses practical implementation of summing out, expanding, and reordering of messages in Local Conditioning (LC) for undirected networks. In particular, incoming messages conditioned on potentially different subsets of the receiving node's relevant set must be expanded to be conditioned on this relevant set, then reordered so that corresponding columns of the conditioned matrices can be fused through element-wise multiplication. An outgoing message is then reduced by summing out loop cutset nodes that are upstream of the outgoing edge. The emphasis on implementation is the primary contribution over the theoretical justification of LC given in Fay et al. Nevertheless, the complexity of Local Conditioning in grid networks is still no better than that of Clustering.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.02641](http://arxiv.org/abs/1812.02641)

##### PDF
[http://arxiv.org/pdf/1812.02641](http://arxiv.org/pdf/1812.02641)

