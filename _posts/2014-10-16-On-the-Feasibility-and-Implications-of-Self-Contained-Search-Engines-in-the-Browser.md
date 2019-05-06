---
layout: post
title: "On the Feasibility and Implications of Self-Contained Search Engines in the Browser"
date: 2014-10-16 17:17:51
categories: arXiv_CV
tags: arXiv_CV
author: Jimmy Lin
mathjax: true
---

* content
{:toc}

##### Abstract
JavaScript engines inside modern browsers are capable of running sophisticated multi-player games, rendering impressive 3D scenes, and supporting complex, interactive visualizations. Can this processing power be harnessed for information retrieval? This paper explores the feasibility of building a JavaScript search engine that runs completely self-contained on the client side within the browser---this includes building the inverted index, gathering terms statistics for scoring, and performing query evaluation. The design takes advantage of the IndexDB API, which is implemented by the LevelDB key-value store inside Google's Chrome browser. Experiments show that although the performance of the JavaScript prototype falls far short of the open-source Lucene search engine, it is sufficiently responsive for interactive applications. This feasibility demonstration opens the door to interesting applications in offline and private search across multiple platforms as well as hybrid split-execution architectures whereby clients and servers collaboratively perform query evaluation. One possible future scenario is the rise of an online search marketplace in which commercial search engine companies and individual users participate as rational economic actors, balancing privacy, resource usage, latency, and other factors based on customizable utility profiles.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1410.4500](https://arxiv.org/abs/1410.4500)

##### PDF
[https://arxiv.org/pdf/1410.4500](https://arxiv.org/pdf/1410.4500)

