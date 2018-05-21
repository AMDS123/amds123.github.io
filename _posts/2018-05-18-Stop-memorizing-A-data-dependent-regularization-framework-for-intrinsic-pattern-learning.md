---
layout: post
title: "Stop memorizing: A data-dependent regularization framework for intrinsic pattern learning"
date: 2018-05-18 15:38:06
categories: arXiv_CV
tags: arXiv_CV Regularization Embedding
author: Wei Zhu, Qiang Qiu, Bao Wang, Jianfeng Lu, Guillermo Sapiro, Ingrid Daubechies
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNNs) typically have enough capacity to fit random data by brute force even when conventional data-dependent regularizations focusing on the geometry of the features are imposed. We find out that the reason for this is the inconsistency between the enforced geometry and the standard softmax cross entropy loss. To resolve this, we propose a new framework for data-dependent DNN regularization, the Geometrically-Regularized-Self-Validating neural Networks (GRSVNet). During training, the geometry enforced on one batch of features is simultaneously validated on a separate batch using a validation loss consistent with the geometry. We study a particular case of GRSVNet, the Orthogonal-Low-rank Embedding (OLE)-GRSVNet, which is capable of producing highly discriminative features residing in orthogonal low-rank subspaces. Numerical experiments show that OLE-GRSVNet outperforms DNNs with conventional regularization when trained on real data. More importantly, unlike conventional DNNs, OLE-GRSVNet refuses to memorize random data or random labels, suggesting it only learns intrinsic patterns by reducing the memorizing capacity of the baseline DNN.

##### Abstract (translated by Google)
深层神经网络（DNN）通常具有足够的容量来通过强力适应随机数据，即使强加关注特征几何的常规数据相关正则化也是如此。我们发现其原因是强制几何和标准softmax交叉熵损失之间的不一致。为了解决这个问题，我们提出了一个新的数据依赖DNN正则化框架，几何正则化自我验证神经网络（GRSVNet）。在训练过程中，使用与几何体一致的验证损失，在一个批次的特征上强制执行的几何体将在单独的批次上同时进行验证。我们研究了GRSVNet的一个特例，即正交低秩嵌入（OLE）-GRSVNet，它能够产生位于正交低秩子空间中的高判别性特征。数值实验表明，在实际数据训练时，OLE-GRSVNet优于常规正则化的DNN。更重要的是，与传统的DNN不同，OLE-GRSVNet拒绝记忆随机数据或随机标签，表明它仅通过减少基线DNN的记忆容量来学习内在模式。

##### URL
[http://arxiv.org/abs/1805.07291](http://arxiv.org/abs/1805.07291)

##### PDF
[http://arxiv.org/pdf/1805.07291](http://arxiv.org/pdf/1805.07291)

