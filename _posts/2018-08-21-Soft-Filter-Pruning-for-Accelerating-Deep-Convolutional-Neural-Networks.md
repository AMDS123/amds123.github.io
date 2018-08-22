---
layout: post
title: "Soft Filter Pruning for Accelerating Deep Convolutional Neural Networks"
date: 2018-08-21 12:22:38
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Inference
author: Yang He, Guoliang Kang, Xuanyi Dong, Yanwei Fu, Yi Yang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposed a Soft Filter Pruning (SFP) method to accelerate the inference procedure of deep Convolutional Neural Networks (CNNs). Specifically, the proposed SFP enables the pruned filters to be updated when training the model after pruning. SFP has two advantages over previous works: (1) Larger model capacity. Updating previously pruned filters provides our approach with larger optimization space than fixing the filters to zero. Therefore, the network trained by our method has a larger model capacity to learn from the training data. (2) Less dependence on the pre-trained model. Large capacity enables SFP to train from scratch and prune the model simultaneously. In contrast, previous filter pruning methods should be conducted on the basis of the pre-trained model to guarantee their performance. Empirically, SFP from scratch outperforms the previous filter pruning methods. Moreover, our approach has been demonstrated effective for many advanced CNN architectures. Notably, on ILSCRC-2012, SFP reduces more than 42% FLOPs on ResNet-101 with even 0.2% top-5 accuracy improvement, which has advanced the state-of-the-art. Code is publicly available on GitHub: https://github.com/he-y/soft-filter-pruning

##### Abstract (translated by Google)
本文提出了一种软滤波修剪（SFP）方法来加速深度卷积神经网络（CNNs）的推理过程。具体而言，所提出的SFP使得在修剪后训练模型时能够更新修剪的滤波器。 SFP比以前的工作有两个优点：（1）更大的模型容量。更新先前已修剪的过滤器为我们的方法提供了比将过滤器固定为零更大的优化空间。因此，通过我们的方法训练的网络具有更大的模型能力来从训练数据中学习。 （2）减少对预训练模型的依赖。大容量使SFP能够从头开始训练并同时修剪模型。相反，先前的过滤器修剪方法应该在预先训练的模型的基础上进行，以保证其性能。根据经验，从头开始的SFP优于以前的过滤器修剪方法。此外，我们的方法已被证明对许多先进的CNN架构有效。值得注意的是，在ILSCRC-2012上，SFP降低了ResNet-101上超过42％的FLOP，甚至提高了0.2％的前5精度，这提升了最新技术水平。代码在GitHub上公开：https：//github.com/he-y/soft-filter-pruning

##### URL
[http://arxiv.org/abs/1808.06866](http://arxiv.org/abs/1808.06866)

##### PDF
[http://arxiv.org/pdf/1808.06866](http://arxiv.org/pdf/1808.06866)

