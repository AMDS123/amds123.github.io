---
layout: post
title: "High-speed Tracking with Multi-kernel Correlation Filters"
date: 2018-06-17 17:38:15
categories: arXiv_CV
tags: arXiv_CV Tracking Relation
author: Ming Tang, Bin Yu, Fan Zhang, Jinqiao Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Correlation filter (CF) based trackers are currently ranked top in terms of their performances. Nevertheless, only some of them, such as KCF~\cite{henriques15} and MKCF~\cite{tangm15}, are able to exploit the powerful discriminability of non-linear kernels. Although MKCF achieves more powerful discriminability than KCF through introducing multi-kernel learning (MKL) into KCF, its improvement over KCF is quite limited and its computational burden increases significantly in comparison with KCF. In this paper, we will introduce the MKL into KCF in a different way than MKCF. We reformulate the MKL version of CF objective function with its upper bound, alleviating the negative mutual interference of different kernels significantly. Our novel MKCF tracker, MKCFup, outperforms KCF and MKCF with large margins and can still work at very high fps. Extensive experiments on public datasets show that our method is superior to state-of-the-art algorithms for target objects of small move at very high speed.

##### Abstract (translated by Google)
基于相关滤波器（CF）的跟踪器目前在其性能方面排名第一。尽管如此，只有其中的一些，如KCF_cite {henriques15}和MKCF_cite {tangm15}能够利用非线性内核的强大可区分性。虽然MKCF通过在KCF中引入多内核学习（MKL）实现了比KCF更强大的可区分性，但与KCF相比，其对KCF的改进相当有限且其计算负担显着增加。在本文中，我们将以与MKCF不同的方式将MKL引入KCF。我们用它的上限重新构造了CF目标函数的MKL版本，显着减轻了不同粒子的负面相互干扰。我们的新型MKCF跟踪器MKCFup优于KCF和MKCF，利润率很高，仍然可以以非常高的fps工作。在公共数据集上进行大量实验表明，我们的方法在超高速度下优于小动作目标物体的最新算法。

##### URL
[http://arxiv.org/abs/1806.06418](http://arxiv.org/abs/1806.06418)

##### PDF
[http://arxiv.org/pdf/1806.06418](http://arxiv.org/pdf/1806.06418)

