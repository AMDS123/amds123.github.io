---
layout: post
title: "Memory vectors for similarity search in high-dimensional spaces"
date: 2017-03-01 21:14:52
categories: arXiv_CV
tags: arXiv_CV Relation
author: Ahmet Iscen, Teddy Furon, Vincent Gripon, Michael Rabbat, Hervé Jégou
mathjax: true
---

* content
{:toc}

##### Abstract
We study an indexing architecture to store and search in a database of high-dimensional vectors from the perspective of statistical signal processing and decision theory. This architecture is composed of several memory units, each of which summarizes a fraction of the database by a single representative vector. The potential similarity of the query to one of the vectors stored in the memory unit is gauged by a simple correlation with the memory unit's representative vector. This representative optimizes the test of the following hypothesis: the query is independent from any vector in the memory unit vs. the query is a simple perturbation of one of the stored vectors. Compared to exhaustive search, our approach finds the most similar database vectors significantly faster without a noticeable reduction in search quality. Interestingly, the reduction of complexity is provably better in high-dimensional spaces. We empirically demonstrate its practical interest in a large-scale image search scenario with off-the-shelf state-of-the-art descriptors.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1412.3328](https://arxiv.org/abs/1412.3328)

##### PDF
[https://arxiv.org/pdf/1412.3328](https://arxiv.org/pdf/1412.3328)

