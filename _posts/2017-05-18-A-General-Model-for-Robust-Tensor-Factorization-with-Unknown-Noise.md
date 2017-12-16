---
layout: post
title: "A General Model for Robust Tensor Factorization with Unknown Noise"
date: 2017-05-18 18:04:15
categories: arXiv_CV
tags: arXiv_CV
author: Xi'ai Chen, Zhi Han, Yao Wang, Qian Zhao, Deyu Meng, Lin Lin, Yandong Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Because of the limitations of matrix factorization, such as losing spatial structure information, the concept of low-rank tensor factorization (LRTF) has been applied for the recovery of a low dimensional subspace from high dimensional visual data. The low-rank tensor recovery is generally achieved by minimizing the loss function between the observed data and the factorization representation. The loss function is designed in various forms under different noise distribution assumptions, like $L_1$ norm for Laplacian distribution and $L_2$ norm for Gaussian distribution. However, they often fail to tackle the real data which are corrupted by the noise with unknown distribution. In this paper, we propose a generalized weighted low-rank tensor factorization method (GWLRTF) integrated with the idea of noise modelling. This procedure treats the target data as high-order tensor directly and models the noise by a Mixture of Gaussians, which is called MoG GWLRTF. The parameters in the model are estimated under the EM framework and through a new developed algorithm of weighted low-rank tensor factorization. We provide two versions of the algorithm with different tensor factorization operations, i.e., CP factorization and Tucker factorization. Extensive experiments indicate the respective advantages of this two versions in different applications and also demonstrate the effectiveness of MoG GWLRTF compared with other competing methods.

##### Abstract (translated by Google)
由于矩阵分解的局限性，例如丢失空间结构信息，低维张量分解（LRTF）的概念已经被应用于从高维视觉数据中恢复低维子空间。低秩张量恢复通常通过最小化观测数据和分解表示之间的损失函数来实现。在不同的噪声分布假设下，损失函数被设计成各种形式，如拉普拉斯分布的$ L_1 $ norm和高斯分布的$ L_2 $ norm。但是，它们往往不能处理被分布不明的噪声破坏的实际数据。本文提出了一种基于噪声建模思想的广义加权低秩张量因子分解方法（GWLRTF）。该程序将目标数据直接作为高阶张量处理，并通过高斯混合模型对噪声进行建模，称为MoG GWLRTF。该模型中的参数在EM框架下通过加权低秩张量因子分解的新算法进行估计。我们提供了具有不同张量分解操作的算法的两个版本，即CP分解和塔克因式分解。大量的实验表明了这两个版本在不同的应用中各自的优势，也证明了与其他竞争方法相比MoG GWLRTF的有效性。

##### URL
[https://arxiv.org/abs/1705.06755](https://arxiv.org/abs/1705.06755)

##### PDF
[https://arxiv.org/pdf/1705.06755](https://arxiv.org/pdf/1705.06755)

