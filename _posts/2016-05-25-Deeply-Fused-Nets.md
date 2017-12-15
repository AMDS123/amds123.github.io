---
layout: post
title: "Deeply-Fused Nets"
date: 2016-05-25 03:35:11
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Jingdong Wang, Zhen Wei, Ting Zhang, Wenjun Zeng
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a novel deep learning approach, deeply-fused nets. The central idea of our approach is deep fusion, i.e., combine the intermediate representations of base networks, where the fused output serves as the input of the remaining part of each base network, and perform such combinations deeply over several intermediate representations. The resulting deeply fused net enjoys several benefits. First, it is able to learn multi-scale representations as it enjoys the benefits of more base networks, which could form the same fused network, other than the initial group of base networks. Second, in our suggested fused net formed by one deep and one shallow base networks, the flows of the information from the earlier intermediate layer of the deep base network to the output and from the input to the later intermediate layer of the deep base network are both improved. Last, the deep and shallow base networks are jointly learnt and can benefit from each other. More interestingly, the essential depth of a fused net composed from a deep base network and a shallow base network is reduced because the fused net could be composed from a less deep base network, and thus training the fused net is less difficult than training the initial deep base network. Empirical results demonstrate that our approach achieves superior performance over two closely-related methods, ResNet and Highway, and competitive performance compared to the state-of-the-arts.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的深度学习方法，深度融合的网络。我们的方法的核心思想是深度融合，即将基础网络的中间表示结合起来，其中融合输出作为每个基础网络的剩余部分的输入，并且在几个中间表示上深入地执行这种组合。由此产生的深熔网络享有几个好处。首先，它能够学习多尺度表示，因为它享有更多的基础网络的好处，可以形成相同的融合网络，而不是最初的一组基础网络。其次，在我们所建议的由一个深基和一个浅基网组成的融合网中，从深基网的较早中间层到输出以及从深输入到较深基网的后一中间层的信息流是都有所改善。最后，深层和浅层基础网络共同学习，可以相互获益。更有意思的是，由于深网基和深基网组成的融合网的基本深度减小了，因此融合网可以由较深的基网构成，因此训练融合网比训练初始网深基础网络。实证结果表明，与最先进的技术相比，我们的方法在两个紧密相关的方法ResNet和Highway上实现了优越的性能，并且具有竞争力。

##### URL
[https://arxiv.org/abs/1605.07716](https://arxiv.org/abs/1605.07716)

##### PDF
[https://arxiv.org/pdf/1605.07716](https://arxiv.org/pdf/1605.07716)

