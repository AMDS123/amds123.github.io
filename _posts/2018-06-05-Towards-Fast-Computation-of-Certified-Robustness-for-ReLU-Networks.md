---
layout: post
title: "Towards Fast Computation of Certified Robustness for ReLU Networks"
date: 2018-06-05 20:50:00
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Tsui-Wei Weng, Huan Zhang, Hongge Chen, Zhao Song, Cho-Jui Hsieh, Duane Boning, Inderjit S. Dhillon, Luca Daniel
mathjax: true
---

* content
{:toc}

##### Abstract
Verifying the robustness property of a general Rectified Linear Unit (ReLU) network is an NP-complete problem [Katz, Barrett, Dill, Julian and Kochenderfer CAV17]. Although finding the exact minimum adversarial distortion is hard, giving a certified lower bound of the minimum distortion is possible. Current available methods of computing such a bound are either time-consuming or delivering low quality bounds that are too loose to be useful. In this paper, we exploit the special structure of ReLU networks and provide two computationally efficient algorithms Fast-Lin and Fast-Lip that are able to certify non-trivial lower bounds of minimum distortions, by bounding the ReLU units with appropriate linear functions Fast-Lin, or by bounding the local Lipschitz constant Fast-Lip. Experiments show that (1) our proposed methods deliver bounds close to (the gap is 2-3X) exact minimum distortion found by Reluplex in small MNIST networks while our algorithms are more than 10,000 times faster; (2) our methods deliver similar quality of bounds (the gap is within 35% and usually around 10%; sometimes our bounds are even better) for larger networks compared to the methods based on solving linear programming problems but our algorithms are 33-14,000 times faster; (3) our method is capable of solving large MNIST and CIFAR networks up to 7 layers with more than 10,000 neurons within tens of seconds on a single CPU core. 
 In addition, we show that, in fact, there is no polynomial time algorithm that can approximately find the minimum $\ell_1$ adversarial distortion of a ReLU network with a $0.99\ln n$ approximation ratio unless $\mathsf{NP}$=$\mathsf{P}$, where $n$ is the number of neurons in the network.

##### Abstract (translated by Google)
验证通用整流线性单元（ReLU）网络的鲁棒性属性是一个NP完全问题[Katz，Barrett，Dill，Julian and Kochenderfer CAV17]。虽然找到确切的最小对抗失真很难，但可以给出最小失真的认证下限。计算这种界限的当前可用的方法要么耗时，要么提供低质量的边界，这些边界太松散而无用。在本文中，我们利用ReLU网络的特殊结构，并通过将ReLU单元与适当的线性函数进行约束，提供两种能够证明最小失真的非平凡下界的计算有效的Fast-Lin和Fast-Lip算法Fast-林，或通过限制当地Lipschitz常量快速唇。实验表明：（1）我们提出的方法提供的接近（小间距是2-3X）精确的最小失真由Reluplex在小型MNIST网络中发现，而我们的算法速度提高了10,000倍以上; （2）与基于求解线性规划问题的方法相比，我们的方法对于较大的网络提供相似的边界质量（差距在35％以内，通常在10％左右;有时我们的边界甚至更好），但我们的算法是33-14,000时间更快; （3）我们的方法能够在单个CPU核心上在数十秒内解决多达7层的大MNIST和CIFAR网络以及10,000多个神经元。
 此外，我们证明，事实上，没有多项式时间算法可以近似地找到ReLU网络的最小$ \ ell_1 $对抗失真，除非$ \ mathsf {NP} $ = $ \ mathsf {P} $，其中$ n $是网络中神经元的数量。

##### URL
[http://arxiv.org/abs/1804.09699](http://arxiv.org/abs/1804.09699)

##### PDF
[http://arxiv.org/pdf/1804.09699](http://arxiv.org/pdf/1804.09699)

