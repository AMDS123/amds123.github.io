---
layout: post
title: "Learning Embedding Adaptation for Few-Shot Learning"
date: 2018-12-10 07:55:56
categories: arXiv_CV
tags: arXiv_CV Attention Embedding Transfer_Learning Classification Recognition
author: Han-Jia Ye, Hexiang Hu, De-Chuan Zhan, Fei Sha
mathjax: true
---

* content
{:toc}

##### Abstract
Learning with limited data is a key challenge for visual recognition. Few-shot learning methods address this challenge by learning an instance embedding function from seen classes and apply the function to instances from unseen classes with limited labels. This style of transfer learning is task-agnostic: the embedding function is not learned optimally discriminative with respect to the unseen classes, where discerning among them is the target task. In this paper, we propose a novel approach to adapt the embedding model to the target classification task, yielding embeddings that are task-specific and are discriminative. To this end, we employ a type of self-attention mechanism called Transformer to transform the embeddings from task-agnostic to task-specific by focusing on relating instances from the test instances to the training instances in both seen and unseen classes. Our approach also extends to both transductive and generalized few-shot classification, two important settings that have essential use cases. We verify the effectiveness of our model on two standard benchmark few-shot classification datasets --- MiniImageNet and CUB, where our approach demonstrates state-of-the-art empirical performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.03664](http://arxiv.org/abs/1812.03664)

##### PDF
[http://arxiv.org/pdf/1812.03664](http://arxiv.org/pdf/1812.03664)

