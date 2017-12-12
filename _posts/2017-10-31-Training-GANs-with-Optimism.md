---
layout: post
title: "Training GANs with Optimism"
date: 2017-10-31 23:09:08
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Constantinos Daskalakis, Andrew Ilyas, Vasilis Syrgkanis, Haoyang Zeng
mathjax: true
---

* content
{:toc}

##### Abstract
We address the issue of limit cycling behavior in training Generative Adversarial Networks and propose the use of Optimistic Mirror Decent (OMD) for training Wasserstein GANs. Recent theoretical results have shown that optimistic mirror decent (OMD) can enjoy faster regret rates in the context of zero-sum games. WGANs is exactly a context of solving a zero-sum game with simultaneous no-regret dynamics. Moreover, we show that optimistic mirror decent addresses the limit cycling problem in training WGANs. We formally show that in the case of bi-linear zero-sum games the last iterate of OMD dynamics converges to an equilibrium, in contrast to GD dynamics which are bound to cycle. We also portray the huge qualitative difference between GD and OMD dynamics with toy examples, even when GD is modified with many adaptations proposed in the recent literature, such as gradient penalty or momentum. We apply OMD WGAN training to a bioinformatics problem of generating DNA sequences. We observe that models trained with OMD achieve consistently smaller KL divergence with respect to the true underlying distribution, than models trained with GD variants. Finally, we introduce a new algorithm, Optimistic Adam, which is an optimistic variant of Adam. We apply it to WGAN training on CIFAR10 and observe improved performance in terms of inception score as compared to Adam.

##### Abstract (translated by Google)
我们解决了生成对抗网络训练中极限自行车行为的问题，并提出使用乐观镜像体验（OMD）来训练Wasserstein GANs。最近的理论结果表明乐观镜像体验（OMD）在零和博弈中可以享受更快的遗憾率。 WGAN恰好是解决零和游戏同时不后悔的动态环境。此外，我们表明，乐观的镜像体面解决了训练WGAN中的极限单车问题。我们正式地表明，在双线性零和博弈的情况下，OMD动态的最后一次迭代收敛到一个平衡点，而GD动力学则是必然循环的。我们还通过玩具的例子描述了GD和OMD动力学之间巨大的质的差别，即使GD在最近的文献中提出了许多适应性修改，例如梯度惩罚或动量。我们将OMD WGAN训练应用于生成DNA序列的生物信息学问题。我们观察到，与使用GD变体训练的模型相比，使用OMD训练的模型可以实现始终较小的KL相对于真实潜在分布的分歧。最后，我们介绍一个新的算法，乐观亚当，这是一个乐观的亚当变体。我们将它应用到WGAN的CIFAR10培训中，并且与Adam相比，观察到启动得分方面的改进表现。

##### URL
[https://arxiv.org/abs/1711.00141](https://arxiv.org/abs/1711.00141)

##### PDF
[https://arxiv.org/pdf/1711.00141](https://arxiv.org/pdf/1711.00141)

