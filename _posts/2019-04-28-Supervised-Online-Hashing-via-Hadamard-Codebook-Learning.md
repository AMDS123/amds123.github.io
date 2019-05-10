---
layout: post
title: "Supervised Online Hashing via Hadamard Codebook Learning"
date: 2019-04-28 02:33:53
categories: arXiv_CV
tags: arXiv_CV Attention Embedding
author: Mingbao Lin, Rongrong Ji, Hong Liu, Yongjian Liu
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, binary code learning, a.k.a hashing, has received extensive attention in large-scale multimedia retrieval. It aims to encode high-dimensional data points to binary codes, hence the original high-dimensional metric space can be efficiently approximated via Hamming space. However, most existing hashing methods adopted offline batch learning, which is not suitable to handle incremental datasets with streaming data or new instances. In contrast, the robustness of the existing online hashing remains as an open problem, while the embedding of supervised/semantic information hardly boosts the performance of the online hashing, mainly due to the defect of unknown category numbers in supervised learning. In this paper, we proposed an online hashing scheme, termed Hadamard Codebook based Online Hashing (HCOH), which aims to solve the above problems towards robust and supervised online hashing. In particular, we first assign an appropriate high-dimensional binary codes to each class label, which is generated randomly by Hadamard codes to each class label, which is generated randomly by Hadamard codes. Subsequently, LSH is adopted to reduce the length of such Hadamard codes in accordance with the hash bits, which can adapt the predefined binary codes online, and theoretically guarantee the semantic similarity. Finally, we consider the setting of stochastic data acquisition, which facilitates our method to efficiently learn the corresponding hashing functions via stochastic gradient descend (SGD) online. Notably, the proposed HCOH can be embedded with supervised labels and it not limited to a predefined category number. Extensive experiments on three widely-used benchmarks demonstrate the merits of the proposed scheme over the state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.03694](http://arxiv.org/abs/1905.03694)

##### PDF
[http://arxiv.org/pdf/1905.03694](http://arxiv.org/pdf/1905.03694)

