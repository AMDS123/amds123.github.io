---
layout: post
title: "SCH-GAN: Semi-supervised Cross-modal Hashing by Generative Adversarial Network"
date: 2018-02-07 15:45:12
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Reinforcement_Learning Relation
author: Jian Zhang, Yuxin Peng, Mingkuan Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
Cross-modal hashing aims to map heterogeneous multimedia data into a common Hamming space, which can realize fast and flexible retrieval across different modalities. Supervised cross-modal hashing methods have achieved considerable progress by incorporating semantic side information. However, they mainly have two limitations: (1) Heavily rely on large-scale labeled cross-modal training data which are labor intensive and hard to obtain. (2) Ignore the rich information contained in the large amount of unlabeled data across different modalities, especially the margin examples that are easily to be incorrectly retrieved, which can help to model the correlations. To address these problems, in this paper we propose a novel Semi-supervised Cross-Modal Hashing approach by Generative Adversarial Network (SCH-GAN). We aim to take advantage of GAN's ability for modeling data distributions to promote cross-modal hashing learning in an adversarial way. The main contributions can be summarized as follows: (1) We propose a novel generative adversarial network for cross-modal hashing. In our proposed SCH-GAN, the generative model tries to select margin examples of one modality from unlabeled data when giving a query of another modality. While the discriminative model tries to distinguish the selected examples and true positive examples of the query. These two models play a minimax game so that the generative model can promote the hashing performance of discriminative model. (2) We propose a reinforcement learning based algorithm to drive the training of proposed SCH-GAN. The generative model takes the correlation score predicted by discriminative model as a reward, and tries to select the examples close to the margin to promote discriminative model by maximizing the margin between positive and negative data. Experiments on 3 widely-used datasets verify the effectiveness of our proposed approach.

##### Abstract (translated by Google)
跨模态散列的目的是将异构多媒体数据映射到一个共同的汉明空间，可以实现跨不同模式的快速和灵活的检索。有监督的跨模态哈希方法通过结合语义边信息已经取得了相当大的进步。但主要存在两方面的局限性：（1）严重依赖劳动密集型，难以获得的大规模标注的跨模态训练数据。 （2）忽略不同模态下大量未标记数据中包含的丰富信息，特别是容易被错误检索的边缘例子，有助于对相关性进行建模。为了解决这些问题，本文提出了一种基于生成对抗网络（SCH-GAN）的新型半监督跨模态哈希方法。我们的目标是利用GAN的数据分布建模能力，以对抗的方式促进跨模态哈希学习。主要贡献可概括如下：（1）提出了一种新的生成对抗网络进行交叉模式散列。在我们提出的SCH-GAN中，生成模型试图在给出另一种模式的查询时，从未标记的数据中选择一种模式的边缘示例。尽管区分模型试图区分所选示例和查询的真正正面示例。这两种模型发挥了极大极小的游戏性，使生成模型能够提高判别模型的哈希性能。 （2）提出了一种基于强化学习的算法来推动SCH-GAN的训练。生成模型以区分模型预测的相关性得分作为奖励，试图通过选择接近边际的例子，通过最大化正负数据间的差距来促进区分模型。 3个广泛使用的数据集上的实验验证了我们提出的方法的有效性。

##### URL
[https://arxiv.org/abs/1802.02488](https://arxiv.org/abs/1802.02488)

##### PDF
[https://arxiv.org/pdf/1802.02488](https://arxiv.org/pdf/1802.02488)

