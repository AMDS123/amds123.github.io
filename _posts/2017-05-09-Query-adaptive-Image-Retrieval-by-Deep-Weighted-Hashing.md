---
layout: post
title: "Query-adaptive Image Retrieval by Deep Weighted Hashing"
date: 2017-05-09 02:40:20
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval QA Attention
author: Jian Zhang, Yuxin Peng
mathjax: true
---

* content
{:toc}

##### Abstract
Hashing methods have attracted much attention for large scale image retrieval. Some deep hashing methods have achieved promising results by taking advantage of the strong representation power of deep networks recently. However, existing deep hashing methods treat all hash bits equally. On one hand, a large number of images share the same distance to a query image due to the discrete Hamming distance, which raises a critical issue of image retrieval where fine-grained rankings are very important. On the other hand, different hash bits actually contribute to the image retrieval differently, and treating them equally greatly affects the retrieval accuracy of image. To address the above two problems, we propose the query-adaptive deep weighted hashing (QaDWH) approach, which can perform fine-grained ranking for different queries by weighted Hamming distance. First, a novel deep hashing network is proposed to learn the hash codes and corresponding class-wise weights jointly, so that the learned weights can reflect the importance of different hash bits for different image classes. Second, a query-adaptive image retrieval method is proposed, which rapidly generates hash bit weights for different query images by fusing its semantic probability and the learned class-wise weights. Fine-grained image retrieval is then performed by the weighted Hamming distance, which can provide more accurate ranking than the traditional Hamming distance. Experiments on four widely used datasets show that the proposed approach outperforms eight state-of-the-art hashing methods.

##### Abstract (translated by Google)
散列方法已经引起了大规模图像检索的重视。近年来，一些深度哈希方法利用深度网络的强大代表性，取得了可喜的成果。但是，现有的深度散列方法对所有散列位均等对待。一方面，由于离散的汉明距离，大量图像与查询图像共享相同的距离，这就提出了图像检索的关键问题，其中细粒度的排名非常重要。另一方面，不同的哈希位实际上对图像检索有不同的贡献，对它们的处理同样极大地影响了图像的检索精度。为了解决上述两个问题，我们提出了查询自适应深度加权散列（QaDWH）方法，可以通过加权汉明距离对不同的查询进行细粒度的排序。首先，提出了一种新的深度哈希网络，联合学习哈希码和相应的分类权重，使学习权重能够反映不同哈希码对不同图像类别的重要性。其次，提出了一种查询自适应图像检索方法，通过融合语义概率和学习分类权重，为不同查询图像快速生成哈希位权重。然后通过加权的汉明距离进行细粒度的图像检索，这可以提供比传统汉明距离更精确的排序。在四个广泛使用的数据集上的实验表明，所提出的方法优于八个最先进的哈希方法。

##### URL
[https://arxiv.org/abs/1612.02541](https://arxiv.org/abs/1612.02541)

##### PDF
[https://arxiv.org/pdf/1612.02541](https://arxiv.org/pdf/1612.02541)

