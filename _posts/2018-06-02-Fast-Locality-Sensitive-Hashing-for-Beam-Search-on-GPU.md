---
layout: post
title: "Fast Locality Sensitive Hashing for Beam Search on GPU"
date: 2018-06-02 06:18:15
categories: arXiv_AI
tags: arXiv_AI
author: Xing Shi, Shizhen Xu, Kevin Knight
mathjax: true
---

* content
{:toc}

##### Abstract
We present a GPU-based Locality Sensitive Hashing (LSH) algorithm to speed up beam search for sequence models. We utilize the winner-take-all (WTA) hash, which is based on relative ranking order of hidden dimensions and thus resilient to perturbations in numerical values. Our algorithm is designed by fully considering the underling architecture of CUDA-enabled GPUs (Algorithm/Architecture Co-design): 1) A parallel Cuckoo hash table is applied for LSH code lookup (guaranteed O(1) lookup time); 2) Candidate lists are shared across beams to maximize the parallelism; 3) Top frequent words are merged into candidate lists to improve performance. Experiments on 4 large-scale neural machine translation models demonstrate that our algorithm can achieve up to 4x speedup on softmax module, and 2x overall speedup without hurting BLEU on GPU.

##### Abstract (translated by Google)
我们提出了一种基于GPU的局部敏感散列（LSH）算法来加速序列模型的波束搜索。我们利用赢家通吃（WTA）哈希，该哈希基于隐藏维度的相对排名顺序，因此可以适应数值的扰动。我们的算法是在充分考虑支持CUDA的GPU的基础架构（算法/架构协同设计）的基础上设计的：1）将一个并行布谷鸟哈希表应用于LSH代码查找（保证O（1）查找时间）。 2）候选列表在光束之间共享以最大化并行性; 3）最常用的单词被合并到候选列表中以提高性能。对4个大型神经机器翻译模型的实验表明，我们的算法可以在softmax模块上实现高达4倍的加速，并且在不损害GPU上的BLEU的情况下实现2倍的总体加速。

##### URL
[http://arxiv.org/abs/1806.00588](http://arxiv.org/abs/1806.00588)

##### PDF
[http://arxiv.org/pdf/1806.00588](http://arxiv.org/pdf/1806.00588)

