---
layout: post
title: "Aggregating Binary Local Descriptors for Image Retrieval"
date: 2017-02-03 15:19:15
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Summarization CNN
author: Giuseppe Amato, Fabrizio Falchi, Lucia Vadicamo
mathjax: true
---

* content
{:toc}

##### Abstract
Content-Based Image Retrieval based on local features is computationally expensive because of the complexity of both extraction and matching of local feature. On one hand, the cost for extracting, representing, and comparing local visual descriptors has been dramatically reduced by recently proposed binary local features. On the other hand, aggregation techniques provide a meaningful summarization of all the extracted feature of an image into a single descriptor, allowing us to speed up and scale up the image search. Only a few works have recently mixed together these two research directions, defining aggregation methods for binary local features, in order to leverage on the advantage of both approaches. In this paper, we report an extensive comparison among state-of-the-art aggregation methods applied to binary features. Then, we mathematically formalize the application of Fisher Kernels to Bernoulli Mixture Models. Finally, we investigate the combination of the aggregated binary features with the emerging Convolutional Neural Network (CNN) features. Our results show that aggregation methods on binary features are effective and represent a worthwhile alternative to the direct matching. Moreover, the combination of the CNN with the Fisher Vector (FV) built upon binary features allowed us to obtain a relative improvement over the CNN results that is in line with that recently obtained using the combination of the CNN with the FV built upon SIFTs. The advantage of using the FV built upon binary features is that the extraction process of binary features is about two order of magnitude faster than SIFTs.

##### Abstract (translated by Google)
基于局部特征的基于内容的图像检索在计算上是昂贵的，因为局部特征的提取和匹配的复杂性。一方面，提取，表示和比较局部视觉描述符的成本已经被最近提出的二进制局部特征大大降低了。另一方面，聚合技术将所有提取的图像特征汇总成单个描述符，使我们能够加快和放大图像搜索。最近只有少数作品将这两个研究方向混合在一起，定义了二元局部特征的聚合方法，以利用这两种方法的优点。在本文中，我们报告了应用于二进制特征的最先进的聚合方法之间的广泛比较。然后，我们将数学形式化的Fisher核函数形式化为伯努利混合模型。最后，我们研究聚合二进制特征与新兴的卷积神经网络（CNN）特征的组合。我们的研究结果表明，二进制特征的聚合方法是有效的，代表了直接匹配的有价值的选择。此外，CNN与基于二进制特征的Fisher矢量（FV）的组合使得我们能够相对于CNN结果获得相对改善，这与最近使用在SIFT上建立的CNN与FV的组合获得的结果是一致的。使用基于二进制特征的FV的优点是二进制特征的提取过程比SIFT快两个数量级。

##### URL
[https://arxiv.org/abs/1608.00813](https://arxiv.org/abs/1608.00813)

##### PDF
[https://arxiv.org/pdf/1608.00813](https://arxiv.org/pdf/1608.00813)

