---
layout: post
title: "Fast Locality Sensitive Hashing for Beam Search on GPU"
date: 2018-06-02 06:18:15
categories: arXiv_CV
tags: arXiv_CV
author: Xing Shi, Shizhen Xu, Kevin Knight
mathjax: true
---

* content
{:toc}

##### Abstract
We present a GPU-based Locality Sensitive Hashing (LSH) algorithm to speed up beam search for sequence models. We utilize the winner-take-all (WTA) hash, which is based on relative ranking order of hidden dimensions and thus resilient to perturbations in numerical values. Our algorithm is designed by fully considering the underling architecture of CUDA-enabled GPUs (Algorithm/Architecture Co-design): 1) A parallel Cuckoo hash table is applied for LSH code lookup (guaranteed O(1) lookup time); 2) Candidate lists are shared across beams to maximize the parallelism; 3) Top frequent words are merged into candidate lists to improve performance. Experiments on 4 large-scale neural machine translation models demonstrate that our algorithm can achieve up to 4x speedup on softmax module, and 2x overall speedup without hurting BLEU on GPU.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1806.00588](https://arxiv.org/abs/1806.00588)

##### PDF
[https://arxiv.org/pdf/1806.00588](https://arxiv.org/pdf/1806.00588)

