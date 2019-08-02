---
layout: post
title: "Central Similarity Hashing via Hadamard matrix"
date: 2019-08-01 12:07:57
categories: arXiv_CV
tags: arXiv_CV Relation
author: Li Yuan, Tao Wang, Xiaopeng Zhang, Zequn Jie, Francis EH Tay, Jiashi Feng
mathjax: true
---

* content
{:toc}

##### Abstract
Hashing has been widely used for efficient large-scale multimedia data retrieval. Most existing methods learn hashing functions from data pairwise similarity to generate binary hash codes. However, in practice we find only learning from the local relationships of pairwise similarity cannot capture the global distribution of large-scale data, which would degrade the discriminability of the generated hash codes and harm the retrieval performance. To overcome this limitation, we propose a new global similarity metric, termed as \emph{central similarity}, to learn better hashing functions. The target of central similarity learning is to encourage hash codes for similar data pairs to be close to a common center and those for dissimilar pairs to converge to different centers in the Hamming space, which substantially improves retrieval accuracy. In order to principally formulate the central similarity learning, we define a new concept, \emph{hash center}, to be a set of points scattered in the Hamming space with a sufficient distance between each other, and propose to use Hadamard matrix to construct high-quality hash centers efficiently. Based on these definitions and designs, we devise a new hash center network (HCN) that learns hashing functions by optimizing the central similarity w.r.t.\ these hash centers. The central similarity learning and HCN are generic and can be applied for both image and video hashing. Extensive experiments for both image and video retrieval demonstrate HCN can generate cohesive hash codes for similar data pairs and dispersed hash codes for dissimilar pairs, and achieve noticeable boost in retrieval performance, i.e. 4\%-13\% in MAP over latest state-of-the-arts. The codes are in: \url{https://github.com/yuanli2333/Hadamard-Matrix-for-hashing}

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.00347](http://arxiv.org/abs/1908.00347)

##### PDF
[http://arxiv.org/pdf/1908.00347](http://arxiv.org/pdf/1908.00347)

