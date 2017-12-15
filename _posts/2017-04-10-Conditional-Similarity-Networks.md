---
layout: post
title: "Conditional Similarity Networks"
date: 2017-04-10 15:18:21
categories: arXiv_CV
tags: arXiv_CV Image_Caption Embedding
author: Andreas Veit, Serge Belongie, Theofanis Karaletsos
mathjax: true
---

* content
{:toc}

##### Abstract
What makes images similar? To measure the similarity between images, they are typically embedded in a feature-vector space, in which their distance preserve the relative dissimilarity. However, when learning such similarity embeddings the simplifying assumption is commonly made that images are only compared to one unique measure of similarity. A main reason for this is that contradicting notions of similarities cannot be captured in a single space. To address this shortcoming, we propose Conditional Similarity Networks (CSNs) that learn embeddings differentiated into semantically distinct subspaces that capture the different notions of similarities. CSNs jointly learn a disentangled embedding where features for different similarities are encoded in separate dimensions as well as masks that select and reweight relevant dimensions to induce a subspace that encodes a specific similarity notion. We show that our approach learns interpretable image representations with visually relevant semantic subspaces. Further, when evaluating on triplet questions from multiple similarity notions our model even outperforms the accuracy obtained by training individual specialized networks for each notion separately.

##### Abstract (translated by Google)
是什么使图像相似？为了测量图像之间的相似性，它们通常嵌入在特征向量空间中，其中它们的距离保持相对不相似性。然而，当学习这样的相似性嵌入时，通常只是将图像与一个独特的相似性度量进行比较来进行简化的假设。一个主要的原因是矛盾的相似概念不能在一个空间中被捕获。为了解决这个缺点，我们提出了条件相似网络（CSN），它学习了嵌入语义上不同的子空间，这些子空间捕捉到相似性的不同概念。 CSN共同学习一个解开的嵌入，其中不同的相似性的特征被编码在不同的维度中，以及掩码选择和重新加权相关的维度以引发编码特定相似性概念的子空间。我们表明，我们的方法学习与视觉相关的语义子空间可解释的图像表示。此外，当从多个相似性概念对三重问题进行评估时，我们的模型甚至比通过分别为每个概念训练单个专门网络所获得的准确性更好。

##### URL
[https://arxiv.org/abs/1603.07810](https://arxiv.org/abs/1603.07810)

##### PDF
[https://arxiv.org/pdf/1603.07810](https://arxiv.org/pdf/1603.07810)

