---
layout: post
title: "CNN Based Hashing for Image Retrieval"
date: 2015-09-04 07:08:44
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval
author: Jinma Guo, Jianmin Li
mathjax: true
---

* content
{:toc}

##### Abstract
Along with data on the web increasing dramatically, hashing is becoming more and more popular as a method of approximate nearest neighbor search. Previous supervised hashing methods utilized similarity/dissimilarity matrix to get semantic information. But the matrix is not easy to construct for a new dataset. Rather than to reconstruct the matrix, we proposed a straightforward CNN-based hashing method, i.e. binarilizing the activations of a fully connected layer with threshold 0 and taking the binary result as hash codes. This method achieved the best performance on CIFAR-10 and was comparable with the state-of-the-art on MNIST. And our experiments on CIFAR-10 suggested that the signs of activations may carry more information than the relative values of activations between samples, and that the co-adaption between feature extractor and hash functions is important for hashing.

##### Abstract (translated by Google)
随着网络数据量的急剧增加，哈希算法作为近似最近邻搜索的方法变得越来越流行。先前的有监督哈希方法利用相似/不相似矩阵来获得语义信息。但是对于一个新的数据集来说，矩阵并不容易构建。我们没有重建矩阵，而是提出了一个简单的基于CNN的哈希方法，即对阈值为0的完全连接层的激活进行二值化，并将二进制结果作为哈希码。这种方法在CIFAR-10上达到了最佳性能，并与MNIST的最新技术相媲美。而我们在CIFAR-10上的实验表明，激活的信号可能比样本之间激活的相对值携带更多的信息，并且特征提取器和散列函数之间的协调适合于哈希。

##### URL
[https://arxiv.org/abs/1509.01354](https://arxiv.org/abs/1509.01354)

##### PDF
[https://arxiv.org/pdf/1509.01354](https://arxiv.org/pdf/1509.01354)

