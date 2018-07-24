---
layout: post
title: "Towards Neural Theorem Proving at Scale"
date: 2018-07-21 20:48:53
categories: arXiv_AI
tags: arXiv_AI Knowledge Embedding Represenation_Learning Inference
author: Pasquale Minervini, Matko Bosnjak, Tim Rockt&#xe4;schel, Sebastian Riedel
mathjax: true
---

* content
{:toc}

##### Abstract
Neural models combining representation learning and reasoning in an end-to-end trainable manner are receiving increasing interest. However, their use is severely limited by their computational complexity, which renders them unusable on real world datasets. We focus on the Neural Theorem Prover (NTP) model proposed by Rockt{\"{a}}schel and Riedel (2017), a continuous relaxation of the Prolog backward chaining algorithm where unification between terms is replaced by the similarity between their embedding representations. For answering a given query, this model needs to consider all possible proof paths, and then aggregate results - this quickly becomes infeasible even for small Knowledge Bases (KBs). We observe that we can accurately approximate the inference process in this model by considering only proof paths associated with the highest proof scores. This enables inference and learning on previously impracticable KBs.

##### Abstract (translated by Google)
将表示学习和推理以端对端可训练方式相结合的神经模型正在受到越来越多的关注。但是，它们的使用受到计算复杂性的严重限制，这使得它们在现实世界数据集中无法使用。我们专注于Rockt {\“{a}} schel和Riedel（2017）提出的神经定理证明（NTP）模型，这是Prolog后向链算法的连续放松，其中术语之间的统一被其嵌入表示之间的相似性所取代。为了回答一个给定的查询，这个模型需要考虑所有可能的证明路径，然后汇总结果 - 即使对于小知识库（KB），这也很快变得不可行。我们观察到我们可以通过考虑准确地近似该模型中的推理过程。只有与最高证据分数相关联的证明路径。这使得能够推断和学习以前不可行的KB。

##### URL
[http://arxiv.org/abs/1807.08204](http://arxiv.org/abs/1807.08204)

##### PDF
[http://arxiv.org/pdf/1807.08204](http://arxiv.org/pdf/1807.08204)

