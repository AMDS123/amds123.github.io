---
layout: post
title: "Cover Detection using Dominant Melody Embeddings"
date: 2019-07-03 09:56:58
categories: arXiv_SD
tags: arXiv_SD Embedding Detection
author: Guillaume Doras, Geoffroy Peeters
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic cover detection -- the task of finding in an audio database all the covers of one or several query tracks -- has long been seen as a challenging theoretical problem in the MIR community and as an acute practical problem for authors and composers societies. Original algorithms proposed for this task have proven their accuracy on small datasets, but are unable to scale up to modern real-life audio corpora. On the other hand, faster approaches designed to process thousands of pairwise comparisons resulted in lower accuracy, making them unsuitable for practical use. 
 In this work, we propose a neural network architecture that is trained to represent each track as a single embedding vector. The computation burden is therefore left to the embedding extraction -- that can be conducted offline and stored, while the pairwise comparison task reduces to a simple Euclidean distance computation. We further propose to extract each track's embedding out of its dominant melody representation, obtained by another neural network trained for this task. We then show that this architecture improves state-of-the-art accuracy both on small and large datasets, and is able to scale to query databases of thousands of tracks in a few seconds.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.01824](http://arxiv.org/abs/1907.01824)

##### PDF
[http://arxiv.org/pdf/1907.01824](http://arxiv.org/pdf/1907.01824)

