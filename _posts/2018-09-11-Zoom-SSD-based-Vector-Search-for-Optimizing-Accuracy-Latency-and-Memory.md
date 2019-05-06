---
layout: post
title: "Zoom: SSD-based Vector Search for Optimizing Accuracy, Latency and Memory"
date: 2018-09-11 23:46:33
categories: arXiv_CV
tags: arXiv_CV Review Deep_Learning
author: Minjia Zhang, Yuxiong He
mathjax: true
---

* content
{:toc}

##### Abstract
With the advancement of machine learning and deep learning, vector search becomes instrumental to many information retrieval systems, to search and find best matches to user queries based on their semantic similarities.These online services require the search architecture to be both effective with high accuracy and efficient with low latency and memory footprint, which existing work fails to offer. We develop, Zoom, a new vector search solution that collaboratively optimizes accuracy, latency and memory based on a multiview approach. (1) A "preview" step generates a small set of good candidates, leveraging compressed vectors in memory for reduced footprint and fast lookup. (2) A "fullview" step on SSDs reranks those candidates with their full-length vector, striking high accuracy. Our evaluation shows that, Zoom achieves an order of magnitude improvements on efficiency while attaining equal or higher accuracy, comparing with the state-of-the-art.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1809.04067](https://arxiv.org/abs/1809.04067)

##### PDF
[https://arxiv.org/pdf/1809.04067](https://arxiv.org/pdf/1809.04067)

