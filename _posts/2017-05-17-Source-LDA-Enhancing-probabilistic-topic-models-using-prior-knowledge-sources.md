---
layout: post
title: "Source-LDA: Enhancing probabilistic topic models using prior knowledge sources"
date: 2017-05-17 21:03:06
categories: arXiv_CL
tags: arXiv_CL Knowledge Summarization Inference
author: Justin Wood, Patrick Tan, Wei Wang, Corey Arnold
mathjax: true
---

* content
{:toc}

##### Abstract
A popular approach to topic modeling involves extracting co-occurring n-grams of a corpus into semantic themes. The set of n-grams in a theme represents an underlying topic, but most topic modeling approaches are not able to label these sets of words with a single n-gram. Such labels are useful for topic identification in summarization systems. This paper introduces a novel approach to labeling a group of n-grams comprising an individual topic. The approach taken is to complement the existing topic distributions over words with a known distribution based on a predefined set of topics. This is done by integrating existing labeled knowledge sources representing known potential topics into the probabilistic topic model. These knowledge sources are translated into a distribution and used to set the hyperparameters of the Dirichlet generated distribution over words. In the inference these modified distributions guide the convergence of the latent topics to conform with the complementary distributions. This approach ensures that the topic inference process is consistent with existing knowledge. The label assignment from the complementary knowledge sources are then transferred to the latent topics of the corpus. The results show both accurate label assignment to topics as well as improved topic generation than those obtained using various labeling approaches based off Latent Dirichlet allocation (LDA).

##### Abstract (translated by Google)
主题建模的流行方法涉及将语料库的共现n-gram提取为语义主题。主题中的n元组代表一个潜在的主题，但大多数主题建模方法不能用单个n元组来标记这些单词集合。这样的标签对摘要系统中的主题识别是有用的。本文介绍了一种新颖的方法来标记一组包含单个主题的n元组。所采取的方法是基于预定义的话题来补充已知话题的现有话题分布。这是通过将代表已知潜在主题的现有标记知识源集成到概率主题模型中来完成的。这些知识源被翻译成一个分布，用来设置Dirichlet生成分布的超参数。在推论中，这些修改后的分布指导潜在主题的收敛符合互补分布。这种方法确保了主题推理过程与现有的知识是一致的。然后将互补知识源的标签分配转移到语料库的潜在主题。结果显示标题分配的主题精确，以及改善的话题生成比那些获得使用基于潜在狄利克雷分配（LDA）的各种标签方法。

##### URL
[https://arxiv.org/abs/1606.00577](https://arxiv.org/abs/1606.00577)

##### PDF
[https://arxiv.org/pdf/1606.00577](https://arxiv.org/pdf/1606.00577)

