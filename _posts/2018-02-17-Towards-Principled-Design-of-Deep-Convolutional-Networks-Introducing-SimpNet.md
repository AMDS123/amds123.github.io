---
layout: post
title: "Towards Principled Design of Deep Convolutional Networks: Introducing SimpNet"
date: 2018-02-17 07:53:58
categories: arXiv_CV
tags: arXiv_CV CNN
author: Seyyed Hossein Hasanpour, Mohammad Rouhani, Mohsen Fayyaz, Mohammad Sabokrou, Ehsan Adeli
mathjax: true
---

* content
{:toc}

##### Abstract
Major winning Convolutional Neural Networks (CNNs), such as VGGNet, ResNet, DenseNet, \etc, include tens to hundreds of millions of parameters, which impose considerable computation and memory overheads. This limits their practical usage in training and optimizing for real-world applications. On the contrary, light-weight architectures, such as SqueezeNet, are being proposed to address this issue. However, they mainly suffer from low accuracy, as they have compromised between the processing power and efficiency. These inefficiencies mostly stem from following an ad-hoc designing procedure. In this work, we discuss and propose several crucial design principles for an efficient architecture design and elaborate intuitions concerning different aspects of the design procedure. Furthermore, we introduce a new layer called {\it SAF-pooling} to improve the generalization power of the network while keeping it simple by choosing best features. Based on such principles, we propose a simple architecture called {\it SimpNet}. We empirically show that SimpNet provides a good trade-off between the computation/memory efficiency and the accuracy solely based on these primitive but crucial principles. SimpNet outperforms the deeper and more complex architectures such as VGGNet, ResNet, WideResidualNet \etc, on several well-known benchmarks, while having 2 to 25 times fewer number of parameters and operations. We obtain state-of-the-art results (in terms of a balance between the accuracy and the number of involved parameters) on standard datasets, such as CIFAR10, CIFAR100, MNIST and SVHN. The implementations are available at \href{url}{https://github.com/Coderx7/SimpNet}.

##### Abstract (translated by Google)
诸如VGGNet，ResNet，DenseNet等的主要获奖卷积神经网络（CNN）包括几十到几亿的参数，这会带来相当大的计算和内存开销。这限制了他们在实际应用中的实际使用情况。相反，正在提出轻量级体系结构，如SqueezeNet来解决这个问题。但是，由于它们在处理能力和效率之间折衷，所以它们主要遭受低精度。这些低效率主要源于特殊设计程序。在这项工作中，我们讨论并提出了一些有效的架构设计的关键设计原则，并详细阐述了设计过程的不同方面。此外，我们引入一个名为{\ it SAF-pooling}的新层，通过选择最佳特性来提高网络的泛化能力，同时保持简单。基于这些原则，我们提出了一个名为{\ SimpNet}的简单架构。我们凭经验证明，SimpNet仅在这些原始但关键的原则基础上，在计算/内存效率和准确性之间提供了良好的折衷。 SimpNet的性能优于VGGNet，ResNet，WideResidualNet等更深更复杂的体系结构，并且在几个众所周知的基准测试中表现出色，同时参数和操作次数减少2到25次。我们获得标准数据集（如CIFAR10，CIFAR100，MNIST和SVHN）的最新结果（以精确度和涉及参数数量之间的平衡）。这些实现可在\ href {url} {https://github.com/Coderx7/SimpNet}上找到。

##### URL
[http://arxiv.org/abs/1802.06205](http://arxiv.org/abs/1802.06205)

##### PDF
[http://arxiv.org/pdf/1802.06205](http://arxiv.org/pdf/1802.06205)

