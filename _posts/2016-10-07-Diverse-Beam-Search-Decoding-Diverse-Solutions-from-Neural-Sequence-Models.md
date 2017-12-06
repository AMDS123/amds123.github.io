---
layout: post
title: 'Diverse Beam Search: Decoding Diverse Solutions from Neural Sequence Models'
date: 2016-10-07 20:56:47
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption VQA
author: Ashwin K Vijayakumar, Michael Cogswell, Ramprasath R. Selvaraju, Qing Sun, Stefan Lee, David Crandall, Dhruv Batra
---

* content
{:toc}

##### Abstract
Neural sequence models are widely used to model time-series data in many fields. Equally ubiquitous is the usage of beam search (BS) as an approximate inference algorithm to decode output sequences from these models. BS explores the search space in a greedy left-right fashion retaining only the top-$B$ candidates -- resulting in sequences that differ only slightly from each other. Producing lists of nearly identical sequences is not only computationally wasteful but also typically fails to capture the inherent ambiguity of complex AI tasks. To overcome this problem, we propose \emph{Diverse Beam Search} (DBS), an alternative to BS that decodes a list of diverse outputs by optimizing for a diversity-augmented objective. We observe that our method finds better top-1 solutions by controlling for the exploration and exploitation of the search space -- implying that DBS is a \emph{better search algorithm}. Moreover, these gains are achieved with minimal computational or memory overhead as compared to beam search. To demonstrate the broad applicability of our method, we present results on image captioning, machine translation and visual question generation using both standard quantitative metrics and qualitative human studies. Our method consistently outperforms BS and previously proposed techniques for diverse decoding from neural sequence models.

##### Abstract (translated by Google)
神经序列模型被广泛用于许多领域的时间序列数据建模。同样无处不在的是使用波束搜索（BS）作为近似推理算法来解码来自这些模型的输出序列。 BS以贪婪的左右方式探索搜索空间，只保留顶部$ B $候选人 - 导致序列只相差很小。生成几乎相同的序列的列表不仅在计算上是浪费的，而且通常也不能捕捉到复杂的AI任务的固有的模糊性。为了克服这个问题，我们提出了一种替代BS的替代方案，即通过优化多样性增强的目标来解码不同输出的列表。我们观察到，我们的方法通过控制搜索空间的探索和利用来找到更好的top-1解决方案，这意味着DBS是一个更好的搜索算法。而且，与波束搜索相比，这些增益是以最小的计算或存储开销实现的。为了证明我们的方法具有广泛的适用性，我们使用标准的定量度量和定性的人体研究来展示图像字幕，机器翻译和视觉问题生成的结果。我们的方法始终优于BS和先前提出的用于从神经序列模型进行不同解码的技术。

##### URL
[https://arxiv.org/abs/1610.02424](https://arxiv.org/abs/1610.02424)

