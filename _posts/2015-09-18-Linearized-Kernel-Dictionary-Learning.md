---
layout: post
title: "Linearized Kernel Dictionary Learning"
date: 2015-09-18 13:52:56
categories: arXiv_CV
tags: arXiv_CV Classification Relation
author: Alona Golts, Michael Elad
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present a new approach of incorporating kernels into dictionary learning. The kernel K-SVD algorithm (KKSVD), which has been introduced recently, shows an improvement in classification performance, with relation to its linear counterpart K-SVD. However, this algorithm requires the storage and handling of a very large kernel matrix, which leads to high computational cost, while also limiting its use to setups with small number of training examples. We address these problems by combining two ideas: first we approximate the kernel matrix using a cleverly sampled subset of its columns using the Nystr\"{o}m method; secondly, as we wish to avoid using this matrix altogether, we decompose it by SVD to form new "virtual samples," on which any linear dictionary learning can be employed. Our method, termed "Linearized Kernel Dictionary Learning" (LKDL) can be seamlessly applied as a pre-processing stage on top of any efficient off-the-shelf dictionary learning scheme, effectively "kernelizing" it. We demonstrate the effectiveness of our method on several tasks of both supervised and unsupervised classification and show the efficiency of the proposed scheme, its easy integration and performance boosting properties.

##### Abstract (translated by Google)
在本文中，我们提出了一种将内核并入字典学习的新方法。最近引入的核K-SVD算法（KKSVD）显示出与线性对应K-SVD有关的分类性能的改善。然而，这种算法需要存储和处理一个非常大的核矩阵，这导致了高计算成本，同时也限制了其用于少量训练实例的设置。我们通过结合两个思路来解决这些问题：首先，我们使用Nystr \“{o} m方法，使用一个巧妙采样的列子集来近似核矩阵;其次，我们希望避免使用这个矩阵， SVD，形成新的“虚拟样本”，可以采用任何线性字典学习方法，我们称之为“线性化核心字典学习”（LKDL）的方法可以作为预处理阶段无缝地应用于任何有效的off-the我们证明了该方法在有监督和无监督分类的几个任务中的有效性，并且表明了该方案的有效性，易于集成和性能提升的特性。

##### URL
[https://arxiv.org/abs/1509.05634](https://arxiv.org/abs/1509.05634)

##### PDF
[https://arxiv.org/pdf/1509.05634](https://arxiv.org/pdf/1509.05634)

