---
layout: post
title: "Latent Relational Metric Learning via Memory-based Attention for Collaborative Ranking"
date: 2018-01-07 13:42:09
categories: arXiv_AI
tags: arXiv_AI Sentiment Attention Relation Recommendation
author: Yi Tay, Anh Tuan Luu, Siu Cheung Hui
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a new neural architecture for collaborative ranking with implicit feedback. Our model, LRML (\textit{Latent Relational Metric Learning}) is a novel metric learning approach for recommendation. More specifically, instead of simple push-pull mechanisms between user and item pairs, we propose to learn latent relations that describe each user item interaction. This helps to alleviate the potential geometric inflexibility of existing metric learing approaches. This enables not only better performance but also a greater extent of modeling capability, allowing our model to scale to a larger number of interactions. In order to do so, we employ a augmented memory module and learn to attend over these memory blocks to construct latent relations. The memory-based attention module is controlled by the user-item interaction, making the learned relation vector specific to each user-item pair. Hence, this can be interpreted as learning an exclusive and optimal relational translation for each user-item interaction. The proposed architecture demonstrates the state-of-the-art performance across multiple recommendation benchmarks. LRML outperforms other metric learning models by $6\%-7.5\%$ in terms of Hits@10 and nDCG@10 on large datasets such as Netflix and MovieLens20M. Moreover, qualitative studies also demonstrate evidence that our proposed model is able to infer and encode explicit sentiment, temporal and attribute information despite being only trained on implicit feedback. As such, this ascertains the ability of LRML to uncover hidden relational structure within implicit datasets.

##### Abstract (translated by Google)
本文提出了一种隐式反馈协同排序的神经网络体系结构。我们的模型，LRML（\ textit {潜在的关系度量学习}）是一种新的推荐度量学习方法。更具体地说，我们建议学习描述每个用户项目交互的潜在关系，而不是用户和项目对之间的简单的推拉机制。这有助于减轻现有的公制学习方法潜在的几何不灵活性。这不仅可以实现更好的性能，而且还可以提高建模能力，从而使我们的模型可以扩展到更多的交互。为了做到这一点，我们使用了增强的内存模块，并学习参与这些内存块来构建潜在的关系。基于记忆的注意模块由用户 - 项目交互控制，使学习的关系矢量特定于每个用户 - 项目对。因此，这可以被解释为学习每个用户 - 项目交互的排他和最佳关系翻译。所提出的架构展示了跨多个推荐基准的最先进的性能。在大型数据集（例如Netflix和MovieLens20M）中，LRML比其他度量学习模型的命中率（Hits @ 10和nDCG @ 10）高出$ 6 \％ -  7.5 \％$。此外，定性研究也证明了我们提出的模型能够推断和编码明确的情绪，时间和属性信息，尽管只是在隐式反馈方面进行了训练。因此，这确定了LRML在隐式数据集中发现隐藏的关系结构的能力。

##### URL
[http://arxiv.org/abs/1707.05176](http://arxiv.org/abs/1707.05176)

##### PDF
[http://arxiv.org/pdf/1707.05176](http://arxiv.org/pdf/1707.05176)

