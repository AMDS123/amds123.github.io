---
layout: post
title: "Ask the GRU: Multi-Task Learning for Deep Text Recommendations"
date: 2016-09-09 19:27:19
categories: arXiv_CL
tags: arXiv_CL Embedding RNN Prediction Recommendation
author: Trapit Bansal, David Belanger, Andrew McCallum
mathjax: true
---

* content
{:toc}

##### Abstract
In a variety of application domains the content to be recommended to users is associated with text. This includes research papers, movies with associated plot summaries, news articles, blog posts, etc. Recommendation approaches based on latent factor models can be extended naturally to leverage text by employing an explicit mapping from text to factors. This enables recommendations for new, unseen content, and may generalize better, since the factors for all items are produced by a compactly-parametrized model. Previous work has used topic models or averages of word embeddings for this mapping. In this paper we present a method leveraging deep recurrent neural networks to encode the text sequence into a latent vector, specifically gated recurrent units (GRUs) trained end-to-end on the collaborative filtering task. For the task of scientific paper recommendation, this yields models with significantly higher accuracy. In cold-start scenarios, we beat the previous state-of-the-art, all of which ignore word order. Performance is further improved by multi-task learning, where the text encoder network is trained for a combination of content recommendation and item metadata prediction. This regularizes the collaborative filtering model, ameliorating the problem of sparsity of the observed rating matrix.

##### Abstract (translated by Google)
在各种应用领域中，要推荐给用户的内容与文本相关联。这包括研究论文，带有相关情节摘要的电影，新闻文章，博客文章等。基于潜在因素模型的推荐方法可以自然扩展，以通过从文本到因素的明确映射来利用文本。这样可以为新的，看不见的内容提供建议，并且可以更好地推广，因为所有项目的因素都是由紧凑参数化模型生成的。以前的工作已经使用主题模型或字嵌入的平均值来进行映射。在本文中，我们提出了一种利用深度递归神经网络将文本序列编码成潜在向量的方法，特别是在协同过滤任务上端到端训练的门控重复单元（GRU）。对于科学论文推荐的任务，这将产生具有更高准确度的模型。在冷启动的情况下，我们击败了先前的艺术，所有这些都忽略了语序。通过多任务学习进一步提高了性能，其中文本编码器网络被训练用于内容推荐和项目元数据预测的组合。这就规范了协同过滤模型，改善了观测评分矩阵的稀疏性问题。

##### URL
[https://arxiv.org/abs/1609.02116](https://arxiv.org/abs/1609.02116)

##### PDF
[https://arxiv.org/pdf/1609.02116](https://arxiv.org/pdf/1609.02116)

