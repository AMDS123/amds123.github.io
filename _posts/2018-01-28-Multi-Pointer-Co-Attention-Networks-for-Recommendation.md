---
layout: post
title: "Multi-Pointer Co-Attention Networks for Recommendation"
date: 2018-01-28 17:14:13
categories: arXiv_AI
tags: arXiv_AI Review Attention Represenation_Learning Prediction Relation Recommendation
author: Yi Tay, Luu Anh Tuan, Siu Cheung Hui
mathjax: true
---

* content
{:toc}

##### Abstract
Many recent state-of-the-art recommender systems such as D-ATT, TransNet and DeepCoNN exploit reviews for representation learning. This paper proposes a new neural architecture for recommendation with reviews. Our model operates on a multi-hierarchical paradigm and is based on the intuition that not all reviews are created equal, i.e., only a select few are important. The importance, however, should be dynamically inferred depending on the current target. To this end, we propose a review-by-review pointer-based learning scheme that extracts important reviews, subsequently matching them in a word-by-word fashion. This enables not only the most informative reviews to be utilized for prediction but also a deeper word-level interaction. Our pointer-based method operates with a novel gumbel-softmax based pointer mechanism that enables the incorporation of discrete vectors within differentiable neural architectures. Our pointer mechanism is co-attentive in nature, learning pointers which are co-dependent on user-item relationships. Finally, we propose a multi-pointer learning scheme that learns to combine multiple views of interactions between user and item. Overall, we demonstrate the effectiveness of our proposed model via extensive experiments on \textbf{24} benchmark datasets from Amazon and Yelp. Empirical results show that our approach significantly outperforms existing state-of-the-art, with up to 19% and 71% relative improvement when compared to TransNet and DeepCoNN respectively. We study the behavior of our multi-pointer learning mechanism, shedding light on evidence aggregation patterns in review-based recommender systems.

##### Abstract (translated by Google)
许多最近推荐的推荐系统，如D-ATT，TransNet和DeepCoNN利用评论进行表示学习。本文提出了一种新的评论推荐神经架构。我们的模型运行在一个多层次的范例中，并且基于不是所有的评论都是平等的直觉，也就是说，只有少数人是重要的。但是，重要性应根据当前目标动态推断。为此，我们提出了一个基于指针的审查方案，提取重要的评论，随后逐字匹配。这使得不仅能够将最丰富的评论用于预测，而且还能够进行更深层次的词级交互。我们基于指针的方法使用基于gumbel-softmax的新型指针机制来运行，该指针机制能够将离散向量合并到可微的神经架构中。我们的指针机制本质上是相互关注的，学习指针是依赖于用户项目的关系。最后，我们提出了一个多指针学习方案，学习结合用户和项目之间交互的多个视图。总的来说，我们通过对来自Amazon和Yelp的\ textbf {24}基准数据集进行广泛的实验来证明我们提出的模型的有效性。实证结果表明，我们的方法明显优于现有技术，与TransNet和DeepCoNN相比分别提高了19％和71％。我们研究了我们的多指针学习机制的行为，揭示了基于评论的推荐系统中的证据聚合模式。

##### URL
[http://arxiv.org/abs/1801.09251](http://arxiv.org/abs/1801.09251)

##### PDF
[http://arxiv.org/pdf/1801.09251](http://arxiv.org/pdf/1801.09251)

