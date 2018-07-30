---
layout: post
title: "Accuracy to Throughput Trade-offs for Reduced Precision Neural Networks on Reconfigurable Logic"
date: 2018-07-17 08:44:00
categories: arXiv_CV
tags: arXiv_CV Inference Quantitative Relation
author: Jiang Su, Nicholas J. Fraser, Giulio Gambardella, Michaela Blott, Gianluca Durelli, David B. Thomas, Philip Leong, Peter Y. K. Cheung
mathjax: true
---

* content
{:toc}

##### Abstract
Modern CNN are typically based on floating point linear algebra based implementations. Recently, reduced precision NN have been gaining popularity as they require significantly less memory and computational resources compared to floating point. This is particularly important in power constrained compute environments. However, in many cases a reduction in precision comes at a small cost to the accuracy of the resultant network. In this work, we investigate the accuracy-throughput trade-off for various parameter precision applied to different types of NN models. We firstly propose a quantization training strategy that allows reduced precision NN inference with a lower memory footprint and competitive model accuracy. Then, we quantitatively formulate the relationship between data representation and hardware efficiency. Our experiments finally provide insightful observation. For example, one of our tests show 32-bit floating point is more hardware efficient than 1-bit parameters to achieve 99% MNIST accuracy. In general, 2-bit and 4-bit fixed point parameters show better hardware trade-off on small-scale datasets like MNIST and CIFAR-10 while 4-bit provide the best trade-off in large-scale tasks like AlexNet on ImageNet dataset within our tested problem domain.

##### Abstract (translated by Google)
现代CNN通常基于基于浮点线性代数的实现。最近，降低的精度NN越来越受欢迎，因为与浮点相比，它们需要显着更少的存储器和计算资源。这在功率受限的计算环境中尤为重要。然而，在许多情况下，精确度的降低对于所得网络的准确性来说成本很小。在这项工作中，我们研究了应用于不同类型的NN模型的各种参数精度的精度 - 吞吐量权衡。我们首先提出了一种量化训练策略，该策略允许降低精度NN推断，具有较低的存储器占用空间和竞争模型精度。然后，我们定量地表达数据表示和硬件效率之间的关系。我们的实验最终提供了深刻的观察。例如，我们的一项测试表明，32位浮点比1位参数更具硬件效率，可实现99％的MNIST精度。通常，2位和4位定点参数显示在MNIST和CIFAR-10等小规模数据集上的更好硬件折衷，而4位在ImageNet数据集上的AlexNet等大型任务中提供了最佳权衡。在我们测试的问题域内。

##### URL
[http://arxiv.org/abs/1807.10577](http://arxiv.org/abs/1807.10577)

##### PDF
[http://arxiv.org/pdf/1807.10577](http://arxiv.org/pdf/1807.10577)

