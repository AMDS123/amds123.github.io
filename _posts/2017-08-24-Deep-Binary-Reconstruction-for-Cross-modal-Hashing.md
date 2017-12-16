---
layout: post
title: "Deep Binary Reconstruction for Cross-modal Hashing"
date: 2017-08-24 01:35:54
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Attention GAN
author: Xuelong Li, Di Hu, Feiping Nie
mathjax: true
---

* content
{:toc}

##### Abstract
With the increasing demand of massive multimodal data storage and organization, cross-modal retrieval based on hashing technique has drawn much attention nowadays. It takes the binary codes of one modality as the query to retrieve the relevant hashing codes of another modality. However, the existing binary constraint makes it difficult to find the optimal cross-modal hashing function. Most approaches choose to relax the constraint and perform thresholding strategy on the real-value representation instead of directly solving the original objective. In this paper, we first provide a concrete analysis about the effectiveness of multimodal networks in preserving the inter- and intra-modal consistency. Based on the analysis, we provide a so-called Deep Binary Reconstruction (DBRC) network that can directly learn the binary hashing codes in an unsupervised fashion. The superiority comes from a proposed simple but efficient activation function, named as Adaptive Tanh (ATanh). The ATanh function can adaptively learn the binary codes and be trained via back-propagation. Extensive experiments on three benchmark datasets demonstrate that DBRC outperforms several state-of-the-art methods in both image2text and text2image retrieval task.

##### Abstract (translated by Google)
随着海量多模态数据存储和组织的需求日益增长，基于哈希技术的跨模式检索技术引起了越来越多的关注。它将一种模式的二进制代码作为查询来检索另一种模式的相关哈希代码。但是，现有的二进制约束条件很难找到最优的交叉模式散列函数。大多数方法选择放宽约束条件，对实值表示进行阈值化策略，而不是直接解决原始目标。在本文中，我们首先对多模网络在保持模式间和模式间一致性方面的有效性进行具体分析。基于此分析，我们提供了一个所谓的深度二进制重构（Deep Binary Reconstruction，DBRC）网络，能够以无监督的方式直接学习二进制散列码。这个优势来自一个简单而有效的激活函数，称为Adaptive Tanh（ATanh）。 ATanh函数可以自适应地学习二进制码，并通过反向传播进行训练。在三个基准数据集上的大量实验表明，DBRC在image2text和text2image检索任务中都优于几种最先进的方法。

##### URL
[https://arxiv.org/abs/1708.05127](https://arxiv.org/abs/1708.05127)

##### PDF
[https://arxiv.org/pdf/1708.05127](https://arxiv.org/pdf/1708.05127)

