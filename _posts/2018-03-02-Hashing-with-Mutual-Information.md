---
layout: post
title: "Hashing with Mutual Information"
date: 2018-03-02 18:12:04
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Embedding Gradient_Descent
author: Fatih Cakir, Kun He, Sarah Adel Bargal, Stan Sclaroff
mathjax: true
---

* content
{:toc}

##### Abstract
Binary vector embeddings enable fast nearest neighbor retrieval in large databases of high-dimensional objects, and play an important role in many practical applications, such as image and video retrieval. We study the problem of learning binary vector embeddings under a supervised setting, also known as hashing. We propose a novel supervised hashing method based on optimizing an information-theoretic quantity, mutual information. We show that optimizing mutual information can reduce ambiguity in the induced neighborhood structure in learned Hamming space, which is essential in obtaining high retrieval performance. To this end, we optimize mutual information in deep neural networks with minibatch stochastic gradient descent, with a formulation that maximally and efficiently utilizes available supervision. Experiments on four image retrieval benchmarks, including ImageNet, confirm the effectiveness of our method in learning high-quality binary embeddings for nearest neighbor retrieval.

##### Abstract (translated by Google)
二进制向量嵌入使高维对象的大型数据库能够进行快速最近邻检索，并且在诸如图像和视频检索等许多实际应用中发挥重要作用。我们研究了在监督设置下学习二元向量嵌入的问题，也称为哈希。我们提出了一种基于信息理论量，互信息优化的新型监督哈希方法。我们表明，优化互信息可以减少学习海明空间中的诱导邻域结构的模糊性，这对于获得高检索性能是必不可少的。为此，我们利用minibatch随机梯度下降来优化深层神经网络中的互信息，其中最大化地和有效地利用可用监督的公式。包括ImageNet在内的四个图像检索基准的实验证实了我们的方法在学习用于最近邻居检索的高质量二进制嵌入中的有效性。

##### URL
[http://arxiv.org/abs/1803.00974](http://arxiv.org/abs/1803.00974)

##### PDF
[http://arxiv.org/pdf/1803.00974](http://arxiv.org/pdf/1803.00974)

