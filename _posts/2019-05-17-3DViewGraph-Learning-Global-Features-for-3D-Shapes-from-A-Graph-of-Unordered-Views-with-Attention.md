---
layout: post
title: "3DViewGraph: Learning Global Features for 3D Shapes from A Graph of Unordered Views with Attention"
date: 2019-05-17 23:52:05
categories: arXiv_CV
tags: arXiv_CV Attention Embedding Deep_Learning Relation
author: Zhizhong Han, Xiyang Wang, Chi-Man Vong, Yu-Shen Liu, Matthias Zwicker, C.L. Philip Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Learning global features by aggregating information over multiple views has been shown to be effective for 3D shape analysis. For view aggregation in deep learning models, pooling has been applied extensively. However, pooling leads to a loss of the content within views, and the spatial relationship among views, which limits the discriminability of learned features. We propose 3DViewGraph to resolve this issue, which learns 3D global features by more effectively aggregating unordered views with attention. Specifically, unordered views taken around a shape are regarded as view nodes on a view graph. 3DViewGraph first learns a novel latent semantic mapping to project low-level view features into meaningful latent semantic embeddings in a lower dimensional space, which is spanned by latent semantic patterns. Then, the content and spatial information of each pair of view nodes are encoded by a novel spatial pattern correlation, where the correlation is computed among latent semantic patterns. Finally, all spatial pattern correlations are integrated with attention weights learned by a novel attention mechanism. This further increases the discriminability of learned features by highlighting the unordered view nodes with distinctive characteristics and depressing the ones with appearance ambiguity. We show that 3DViewGraph outperforms state-of-the-art methods under three large-scale benchmarks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.07503](http://arxiv.org/abs/1905.07503)

##### PDF
[http://arxiv.org/pdf/1905.07503](http://arxiv.org/pdf/1905.07503)

