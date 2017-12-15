---
layout: post
title: "Deep Networks with Stochastic Depth"
date: 2016-07-28 23:24:16
categories: arXiv_CV
tags: arXiv_CV CNN
author: Gao Huang, Yu Sun, Zhuang Liu, Daniel Sedra, Kilian Weinberger
mathjax: true
---

* content
{:toc}

##### Abstract
Very deep convolutional networks with hundreds of layers have led to significant reductions in error on competitive benchmarks. Although the unmatched expressiveness of the many layers can be highly desirable at test time, training very deep networks comes with its own set of challenges. The gradients can vanish, the forward flow often diminishes, and the training time can be painfully slow. To address these problems, we propose stochastic depth, a training procedure that enables the seemingly contradictory setup to train short networks and use deep networks at test time. We start with very deep networks but during training, for each mini-batch, randomly drop a subset of layers and bypass them with the identity function. This simple approach complements the recent success of residual networks. It reduces training time substantially and improves the test error significantly on almost all data sets that we used for evaluation. With stochastic depth we can increase the depth of residual networks even beyond 1200 layers and still yield meaningful improvements in test error (4.91% on CIFAR-10).

##### Abstract (translated by Google)
具有数百个层次的非常深的卷积网络导致竞争性基准测试中错误的显着减少。尽管在测试时间内多层的无可比拟的表现力是非常可取的，但是训练非常深的网络却带来了一系列的挑战。渐变可以消失，向前的流动往往会减少，训练时间可以痛苦地缓慢。为了解决这些问题，我们提出了随机深度，一个训练过程，使看似矛盾的设置在测试时间训练短网络和使用深度网络。我们从非常深的网络开始，但在训练期间，对于每个小批量，随机删除一部分图层，并使用身份函数绕过它们。这个简单的方法补充了最近残留网络的成功。它大大减少了训练时间，并显着改善了我们用于评估的几乎所有数据集的测试错误。通过随机深度，我们可以将残余网络的深度增加到超过1200层，仍然可以在测试误差（CIFAR-10的4.91％）上产生有意义的改进。

##### URL
[https://arxiv.org/abs/1603.09382](https://arxiv.org/abs/1603.09382)

##### PDF
[https://arxiv.org/pdf/1603.09382](https://arxiv.org/pdf/1603.09382)

