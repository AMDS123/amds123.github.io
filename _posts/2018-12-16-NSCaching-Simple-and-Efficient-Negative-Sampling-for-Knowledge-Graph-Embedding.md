---
layout: post
title: "NSCaching: Simple and Efficient Negative Sampling for Knowledge Graph Embedding"
date: 2018-12-16 07:32:02
categories: arXiv_AI
tags: arXiv_AI Adversarial Knowledge_Graph Knowledge GAN Reinforcement_Learning Embedding Relation
author: Yongqi Zhang, Quanming Yao, Yingxia Shao, Lei Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Knowledge Graph (KG) embedding is a fundamental problem in data mining research with many real-world applications. It aims to encode the entities and relations in the graph into low dimensional vector space, which can be used for subsequent algorithms. Negative sampling, which samples negative triplets from non-observed ones in the training data, is an important step in KG embedding. Recently, generative adversarial network (GAN), has been introduced in negative sampling. By sampling negative triplets with large scores, these methods avoid the problem of vanishing gradient and thus obtain better performance. However, using GAN makes the original model more complex and hard to train, where reinforcement learning must be used. In this paper, motivated by the observation that negative triplets with large scores are important but rare, we propose to directly keep track of them with the cache. However, how to sample from and update the cache are two important questions. We carefully design the solutions, which are not only efficient but also achieve a good balance between exploration and exploitation. In this way, our method acts as a "distilled" version of previous GA-based methods, which does not waste training time on additional parameters to fit the full distribution of negative triplets. The extensive experiments show that our method can gain significant improvement in various KG embedding models, and outperform the state-of-the-art negative sampling methods based on GAN.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.06410](http://arxiv.org/abs/1812.06410)

##### PDF
[http://arxiv.org/pdf/1812.06410](http://arxiv.org/pdf/1812.06410)

