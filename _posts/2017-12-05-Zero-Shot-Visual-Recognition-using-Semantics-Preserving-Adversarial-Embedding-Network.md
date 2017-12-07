---
layout: post
title: "Zero-Shot Visual Recognition using Semantics-Preserving Adversarial Embedding Network"
date: 2017-12-05 21:16:52
categories: arXiv_CV
tags: arXiv_CV Adversarial Recognition
author: Long Chen, Hanwang Zhang, Jun Xiao, Wei Liu, Shih-Fu Chang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel framework called Semantics-Preserving Adversarial Embedding Network (SP-AEN) for zero-shot visual recognition (ZSL), where test images and their classes are both unseen during training. SP-AEN aims to tackle the inherent problem --- semantic loss --- in the prevailing family of embedding-based ZSL, where some semantics would be discarded during training if they are non-discriminative for training classes, but informative for test classes. Specifically, SP-AEN prevents the semantic loss by introducing an independent visual-to-semantic space embedder which disentangles the semantic space into two subspaces for the two arguably conflicting objectives: classification and reconstruction. Through adversarial learning of the two subspaces, SP-AEN can transfer the semantics from the reconstructive subspace to the discriminative one, accomplishing the improved zero-shot recognition of unseen classes. Compared to prior works, SP-AEN can not only improve classification but also generate photo-realistic images, demonstrating the effectiveness of semantic preservation. On four benchmarks: CUB, AWA, SUN and aPY, SP-AEN considerably outperforms other state-of-the-art methods by absolute 12.2\%, 9.3\%, 4.0\%, and 3.6\% in harmonic mean values.

##### Abstract (translated by Google)
我们提出了一种称为语义保持敌对嵌入网络（SP-AEN）的零框架视觉识别（ZSL）的新框架，其中测试图像和它们的类别在训练期间都是看不见的。 SP-AEN旨在解决固有的问题 - 语义损失 - 在基于嵌入的ZSL的普遍存在的家族中，如果对训练类不具有区别性，那么在训练期间将丢弃一些语义，但对测试类提供信息。具体而言，SP-AEN通过引入独立的视觉 - 语义空间嵌入器来防止语义损失，所述嵌入器将语义空间解开为两个可以相互矛盾的目标（分类和重建）的两个子空间。通过两个子空间的对抗学习，SP-AEN可以将语义从重构子空间转移到判别子空间，实现了对未知类的零点识别。与以前的作品相比，SP-AEN不仅可以提高分类效果，而且可以生成逼真的图像，显​​示语义保存的有效性。在CUB，AWA，SUN和aPY四个基准测试中，SP-AEN在谐波平均值上的绝对值为12.2％，9.3％，4.0％和3.6％，明显优于其他最先进的方法。

##### URL
[http://arxiv.org/abs/1712.01928](http://arxiv.org/abs/1712.01928)

##### PDF
[http://arxiv.org/pdf/1712.01928](http://arxiv.org/pdf/1712.01928)

