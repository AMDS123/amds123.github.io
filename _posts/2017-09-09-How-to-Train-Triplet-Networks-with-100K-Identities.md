---
layout: post
title: "How to Train Triplet Networks with 100K Identities?"
date: 2017-09-09 10:18:41
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Face Recognition Face_Recognition
author: Chong Wang, Xue Zhang, Xipeng Lan
mathjax: true
---

* content
{:toc}

##### Abstract
Training triplet networks with large-scale data is challenging in face recognition. Due to the number of possible triplets explodes with the number of samples, previous studies adopt the online hard negative mining(OHNM) to handle it. However, as the number of identities becomes extremely large, the training will suffer from bad local minima because effective hard triplets are difficult to be found. To solve the problem, in this paper, we propose training triplet networks with subspace learning, which splits the space of all identities into subspaces consisting of only similar identities. Combined with the batch OHNM, hard triplets can be found much easier. Experiments on the large-scale MS-Celeb-1M challenge with 100K identities demonstrate that the proposed method can largely improve the performance. In addition, to deal with heavy noise and large-scale retrieval, we also make some efforts on robust noise removing and efficient image retrieval, which are used jointly with the subspace learning to obtain the state-of-the-art performance on the MS-Celeb-1M competition (without external data in Challenge1).

##### Abstract (translated by Google)
培训三重网络与大规模的数据是具有挑战性的人脸识别。由于可能的三胞胎数量随着样本数量的增加而爆炸，以前的研究采用在线硬性负面挖掘（OHNM）来处理。但是，由于身份数量变得非常大，训练将会受到局部最不利的影响，因为难以找到有效的三胞胎。为了解决这个问题，本文提出了一种基于子空间学习的三元组网络，将所有身份空间划分为只有相似身份的子空间。结合批量OHNM，可以发现硬三元组更容易。对100K身份的大规模MS-Celeb-1M挑战进行的实验表明，所提出的方法可以在很大程度上提高性能。此外，为了处理噪声较大和大规模的检索，我们也在鲁棒噪声消除和高效图像检索方面做了一些努力，这些方法与子空间学习一起使用，以获得MS上的最新性能-Celeb-1M竞赛（Challenge1中没有外部数据）。

##### URL
[https://arxiv.org/abs/1709.02940](https://arxiv.org/abs/1709.02940)

##### PDF
[https://arxiv.org/pdf/1709.02940](https://arxiv.org/pdf/1709.02940)

