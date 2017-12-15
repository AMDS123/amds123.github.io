---
layout: post
title: "Modality-specific Cross-modal Similarity Measurement with Recurrent Attention Network"
date: 2017-08-16 05:43:54
categories: arXiv_CL
tags: arXiv_CL Attention Embedding Relation
author: Yuxin Peng, Jinwei Qi, Yuxin Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
Nowadays, cross-modal retrieval plays an indispensable role to flexibly find information across different modalities of data. Effectively measuring the similarity between different modalities of data is the key of cross-modal retrieval. Different modalities such as image and text have imbalanced and complementary relationships, which contain unequal amount of information when describing the same semantics. For example, images often contain more details that cannot be demonstrated by textual descriptions and vice versa. Existing works based on Deep Neural Network (DNN) mostly construct one common space for different modalities to find the latent alignments between them, which lose their exclusive modality-specific characteristics. Different from the existing works, we propose modality-specific cross-modal similarity measurement (MCSM) approach by constructing independent semantic space for each modality, which adopts end-to-end framework to directly generate modality-specific cross-modal similarity without explicit common representation. For each semantic space, modality-specific characteristics within one modality are fully exploited by recurrent attention network, while the data of another modality is projected into this space with attention based joint embedding to utilize the learned attention weights for guiding the fine-grained cross-modal correlation learning, which can capture the imbalanced and complementary relationships between different modalities. Finally, the complementarity between the semantic spaces for different modalities is explored by adaptive fusion of the modality-specific cross-modal similarities to perform cross-modal retrieval. Experiments on the widely-used Wikipedia and Pascal Sentence datasets as well as our constructed large-scale XMediaNet dataset verify the effectiveness of our proposed approach, outperforming 9 state-of-the-art methods.

##### Abstract (translated by Google)
目前，跨模式检索对于灵活地在不同的数据模式中查找信息起着不可或缺的作用。有效地度量不同数据模式之间的相似度是跨模式检索的关键。图像和文本等不同的模态具有不平衡和互补的关系，当描述相同的语义时，包含不同的信息量。例如，图像往往包含更多的细节，不能由文字描述，反之亦然。基于深度神经网络（DNN）的现有作品大多为不同的模式构建了一个公共空间，以找到它们之间的潜在对齐，从而失去了独特的特定模式特征。与现有的研究工作不同，我们针对每种模态构建了独立的语义空间，提出了特定模态的跨模态相似性度量（MCSM）方法，采用端到端框架直接生成特定模态的跨模态相似度，表示。对于每个语义空间，反复注意网络充分利用一种模态内特定于模态的特征，而另一种模式的数据通过注意联合嵌入投影到该空间中，利用学习到的注意权重指导细粒度的交叉关联，模态相关学习，可以捕捉不同模式之间的不平衡和互补关系。最后，通过模态特定的跨模态相似性的自适应融合来探索不同模态的语义空间之间的互补性以执行跨模态检索。对广泛使用的维基百科和Pascal句子数据集以及我们构建的大规模XMediaNet数据集的实验验证了我们提出的方法的有效性，超过了9种最先进的方法。

##### URL
[https://arxiv.org/abs/1708.04776](https://arxiv.org/abs/1708.04776)

##### PDF
[https://arxiv.org/pdf/1708.04776](https://arxiv.org/pdf/1708.04776)

