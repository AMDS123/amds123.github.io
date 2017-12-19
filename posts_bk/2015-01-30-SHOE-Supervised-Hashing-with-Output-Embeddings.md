---
layout: post
title: "SHOE: Supervised Hashing with Output Embeddings"
date: 2015-01-30 22:04:12
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Embedding Optimization Classification Relation
author: Sravanthi Bondugula, Varun Manjunatha, Larry S. Davis, David Doermann
mathjax: true
---

* content
{:toc}

##### Abstract
We present a supervised binary encoding scheme for image retrieval that learns projections by taking into account similarity between classes obtained from output embeddings. Our motivation is that binary hash codes learned in this way improve both the visual quality of retrieval results and existing supervised hashing schemes. We employ a sequential greedy optimization that learns relationship aware projections by minimizing the difference between inner products of binary codes and output embedding vectors. We develop a joint optimization framework to learn projections which improve the accuracy of supervised hashing over the current state of the art with respect to standard and sibling evaluation metrics. We further boost performance by applying the supervised dimensionality reduction technique on kernelized input CNN features. Experiments are performed on three datasets: CUB-2011, SUN-Attribute and ImageNet ILSVRC 2010. As a by-product of our method, we show that using a simple k-nn pooling classifier with our discriminative codes improves over the complex classification models on fine grained datasets like CUB and offer an impressive compression ratio of 1024 on CNN features.

##### Abstract (translated by Google)
我们提出了一个有监督的图像检索二进制编码方案，通过考虑从输出嵌入获得的类之间的相似性来学习投影。我们的动机是，以这种方式学习的二进制散列码提高了检索结果的视觉质量和现有的监督散列方案。我们采用连续贪婪优化，通过最小化二进制编码和输出嵌入向量的内积之间的差异来学习关系感知投影。我们开发了一个联合优化框架来学习预测，这些预测在标准和同级评估指标方面提高了监督散列的精确度。通过将监督降维技术应用于核化输入CNN特征，我们进一步提高了性能。实验在CUB-2011，SUN-Attribute和ImageNet ILSVRC 2010三个数据集上进行。作为我们方法的一个副产品，我们证明了使用简单的k-nn池分类器和我们的判别性代码可以改进复杂的分类模型细粒度的数据集如CUB，在CNN特性上提供了令人印象深刻的1024压缩比率。

##### URL
[https://arxiv.org/abs/1502.00030](https://arxiv.org/abs/1502.00030)

##### PDF
[https://arxiv.org/pdf/1502.00030](https://arxiv.org/pdf/1502.00030)

