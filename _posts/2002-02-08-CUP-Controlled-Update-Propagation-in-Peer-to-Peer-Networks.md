---
layout: post
title: "CUP: Controlled Update Propagation in Peer-to-Peer Networks"
date: 2002-02-08 02:27:43
categories: arXiv_CV
tags: arXiv_CV Attention
author: Mema Roussopoulos, Mary Baker
mathjax: true
---

* content
{:toc}

##### Abstract
Recently the problem of indexing and locating content in peer-to-peer networks has received much attention. Previous work suggests caching index entries at intermediate nodes that lie on the paths taken by search queries, but until now there has been little focus on how to maintain these intermediate caches. This paper proposes CUP, a new comprehensive architecture for Controlled Update Propagation in peer-to-peer networks. CUP asynchronously builds caches of index entries while answering search queries. It then propagates updates of index entries to maintain these caches. Under unfavorable conditions, when compared with standard caching based on expiration times, CUP reduces the average miss latency by as much as a factor of three. Under favorable conditions, CUP can reduce the average miss latency by more than a factor of ten. CUP refreshes intermediate caches, reduces query latency, and reduces network load by coalescing bursts of queries for the same item. CUP controls and confines propagation to updates whose cost is likely to be recovered by subsequent queries. CUP gives peer-to-peer nodes the flexibility to use their own incentive-based policies to determine when to receive and when to propagate updates. Finally, the small propagation overhead incurred by CUP is more than compensated for by its savings in cache misses.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/cs/0202008](https://arxiv.org/abs/cs/0202008)

##### PDF
[https://arxiv.org/pdf/cs/0202008](https://arxiv.org/pdf/cs/0202008)

