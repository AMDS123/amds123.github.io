---
layout: post
title: "Online Supervised Hashing for Ever-Growing Datasets"
date: 2015-11-10 20:37:41
categories: arXiv_CV
tags: arXiv_CV
author: Fatih Cakir, Sarah Adel Bargal, Stan Sclaroff
mathjax: true
---

* content
{:toc}

##### Abstract
Supervised hashing methods are widely-used for nearest neighbor search in computer vision applications. Most state-of-the-art supervised hashing approaches employ batch-learners. Unfortunately, batch-learning strategies can be inefficient when confronted with large training datasets. Moreover, with batch-learners, it is unclear how to adapt the hash functions as a dataset continues to grow and diversify over time. Yet, in many practical scenarios the dataset grows and diversifies; thus, both the hash functions and the indexing must swiftly accommodate these changes. To address these issues, we propose an online hashing method that is amenable to changes and expansions of the datasets. Since it is an online algorithm, our approach offers linear complexity with the dataset size. Our solution is supervised, in that we incorporate available label information to preserve the semantic neighborhood. Such an adaptive hashing method is attractive; but it requires recomputing the hash table as the hash functions are updated. If the frequency of update is high, then recomputing the hash table entries may cause inefficiencies in the system, especially for large indexes. Thus, we also propose a framework to reduce hash table updates. We compare our method to state-of-the-art solutions on two benchmarks and demonstrate significant improvements over previous work.

##### Abstract (translated by Google)
监督散列方法广泛用于计算机视觉应用中的最近邻搜索。大多数最先进的监督哈希方法采用批处理学习者。不幸的是，批量学习策略在遇到大量训练数据集时可能效率低下。而且，对于批处理学习者，随着时间的推移，随着数据集的不断发展和多样化，如何调整散列函数还不清楚。然而，在许多实际的情况下，数据集增长和多样化;因此，散列函数和索引都必须迅速适应这些变化。为了解决这些问题，我们提出了一个在线哈希方法，可以修改和扩展数据集。由于它是一个在线算法，我们的方法提供了数据集大小的线性复杂性。我们的解决方案是监督的，因为我们结合了可用的标签信息来保存语义邻域。这种自适应哈希方法是有吸引力的;但是随着哈希函数的更新，它需要重新计算哈希表。如果更新频率较高，那么重新计算散列表条目可能会导致系统效率低下，特别是对于大型索引。因此，我们也提出了一个减少散列表更新的框架。我们将我们的方法与两个基准测试中的最新解决方案进行比较，并证明比以前的工作有了显着的改进。

##### URL
[https://arxiv.org/abs/1511.03257](https://arxiv.org/abs/1511.03257)

##### PDF
[https://arxiv.org/pdf/1511.03257](https://arxiv.org/pdf/1511.03257)

