---
layout: post
title: "Logic Rules Powered Knowledge Graph Embedding"
date: 2019-03-09 10:01:12
categories: arXiv_AI
tags: arXiv_AI Knowledge_Graph Knowledge Attention Embedding Inference Classification Prediction Relation
author: Pengwei Wang, Dejing Dou, Fangzhao Wu, Nisansa de Silva, Lianwen Jin
mathjax: true
---

* content
{:toc}

##### Abstract
Large scale knowledge graph embedding has attracted much attention from both academia and industry in the field of Artificial Intelligence. However, most existing methods concentrate solely on fact triples contained in the given knowledge graph. Inspired by the fact that logic rules can provide a flexible and declarative language for expressing rich background knowledge, it is natural to integrate logic rules into knowledge graph embedding, to transfer human knowledge to entity and relation embedding, and strengthen the learning process. In this paper, we propose a novel logic rule-enhanced method which can be easily integrated with any translation based knowledge graph embedding model, such as TransE . We first introduce a method to automatically mine the logic rules and corresponding confidences from the triples. And then, to put both triples and mined logic rules within the same semantic space, all triples in the knowledge graph are represented as first-order logic. Finally, we define several operations on the first-order logic and minimize a global loss over both of the mined logic rules and the transformed first-order logics. We conduct extensive experiments for link prediction and triple classification on three datasets: WN18, FB166, and FB15K. Experiments show that the rule-enhanced method can significantly improve the performance of several baselines. The highlight of our model is that the filtered Hits@1, which is a pivotal evaluation in the knowledge inference task, has a significant improvement (up to 700% improvement).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.03772](http://arxiv.org/abs/1903.03772)

##### PDF
[http://arxiv.org/pdf/1903.03772](http://arxiv.org/pdf/1903.03772)

