---
layout: post
title: "Unsupervised Multi-Domain Image Translation with Domain-Specific Encoders/Decoders"
date: 2017-12-06 06:08:31
categories: arXiv_CV
tags: arXiv_CV Face
author: Le Hui, Xiang Li, Jiaxin Chen, Hongliang He, Chen gong, Jian Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised Image-to-Image Translation achieves spectacularly advanced developments nowadays. However, recent approaches mainly focus on one model with two domains, which may face heavy burdens with large cost of $O(n^2)$ training time and model parameters, under such a requirement that $n$ domains are freely transferred to each other in a general setting. To address this problem, we propose a novel and unified framework named Domain-Bank, which consists of a global shared auto-encoder and $n$ domain-specific encoders/decoders, assuming that a universal shared-latent sapce can be projected. Thus, we yield $O(n)$ complexity in model parameters along with a huge reduction of the time budgets. Besides the high efficiency, we show the comparable (or even better) image translation results over state-of-the-arts on various challenging unsupervised image translation tasks, including face image translation, fashion-clothes translation and painting style translation. We also apply the proposed framework to domain adaptation and achieve state-of-the-art performance on digit benchmark datasets. Further, thanks to the explicit representation of the domain-specific decoders as well as the universal shared-latent space, it also enables us to conduct incremental learning to add a new domain encoder/decoder. Linear combination of different domains' representations is also obtained by fusing the corresponding decoders.

##### Abstract (translated by Google)
无监督的图像到图像翻译如今取得了惊人的进展。然而，最近的研究方法主要集中在一个有两个领域的模型上，这个模型可能面临很高的成本和$ O（n ^ 2）$训练时间和模型参数，在$ n $域被自由地转移到每个领域其他在一般设置。为了解决这个问题，我们提出了一个名为Domain-Bank的新颖而统一的框架，假设可以投射一个通用的共享隐藏空间，该框架由一个全局共享自动编码器和$ n $域专用编码器/解码器组成。因此，我们在模型参数中产生了$ O（n）$复杂性，同时大大缩短了时间预算。除了高效率之外，我们还展示了在各种具有挑战性的无监督图像翻译任务（包括面部图像翻译，时尚服装翻译和绘画风格翻译）方面相比（甚至更好）的图像翻译结果。我们还将所提出的框架应用于域名适应，并在数字基准数据集上实现最先进的性能。此外，由于领域特定的解码器以及通用的共享潜在空间的明确表示，它也使得我们能够进行增量学习来添加新的领域编码器/解码器。不同领域的表示的线性组合也通过融合相应的解码器而获得。

##### URL
[http://arxiv.org/abs/1712.02050](http://arxiv.org/abs/1712.02050)

##### PDF
[http://arxiv.org/pdf/1712.02050](http://arxiv.org/pdf/1712.02050)

