---
layout: post
title: "MHTN: Modal-adversarial Hybrid Transfer Network for Cross-modal Retrieval"
date: 2017-08-08 07:50:52
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge Face Transfer_Learning Represenation_Learning
author: Xin Huang, Yuxin Peng, Mingkuan Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
Cross-modal retrieval has drawn wide interest for retrieval across different modalities of data. However, existing methods based on DNN face the challenge of insufficient cross-modal training data, which limits the training effectiveness and easily leads to overfitting. Transfer learning is for relieving the problem of insufficient training data, but it mainly focuses on knowledge transfer only from large-scale datasets as single-modal source domain to single-modal target domain. Such large-scale single-modal datasets also contain rich modal-independent semantic knowledge that can be shared across different modalities. Besides, large-scale cross-modal datasets are very labor-consuming to collect and label, so it is significant to fully exploit the knowledge in single-modal datasets for boosting cross-modal retrieval. This paper proposes modal-adversarial hybrid transfer network (MHTN), which to the best of our knowledge is the first work to realize knowledge transfer from single-modal source domain to cross-modal target domain, and learn cross-modal common representation. It is an end-to-end architecture with two subnetworks: (1) Modal-sharing knowledge transfer subnetwork is proposed to jointly transfer knowledge from a large-scale single-modal dataset in source domain to all modalities in target domain with a star network structure, which distills modal-independent supplementary knowledge for promoting cross-modal common representation learning. (2) Modal-adversarial semantic learning subnetwork is proposed to construct an adversarial training mechanism between common representation generator and modality discriminator, making the common representation discriminative for semantics but indiscriminative for modalities to enhance cross-modal semantic consistency during transfer process. Comprehensive experiments on 4 widely-used datasets show its effectiveness and generality.

##### Abstract (translated by Google)
跨模态检索已经引起了对不同数据模式的检索的广泛兴趣。然而，现有的基于DNN的方法面临着跨模态训练数据不足的问题，限制了训练的有效性，容易导致过拟合。转移学习是为了缓解训练数据不足的问题，但主要侧重于从单一模态源域到单一模态目标域的大规模数据集的知识转移。这种大规模的单一模态数据集还包含丰富的模态独立语义知识，可以在不同的模式之间共享。此外，大规模跨模态数据集的收集和标注是非常耗费人力的，因此充分利用单模态数据集中的知识来提高跨模态检索性能是非常重要的。本文提出了模态对抗混合传输网络（MHTN），据我们所知，这是第一个实现从单模源域到跨模态目标域的知识转移的工作，并且学习了跨模态的共同表示。它是一个具有两个子网络的端到端体系结构：（1）提出模式共享知识转移子网络，将知识从源域的大规模单一模式数据集联合转移到目标域中的所有模式，它为提升跨模式的共同表征学习提炼了与模态无关的补充知识。 （2）提出模态对抗语义学习子网络，在共同表征生成器和模态鉴别器之间构建对抗训练机制，使得共同表征具有语义辨别能力，但对于转移过程中增强跨模态语义一致性的模式不加区别。 4个广泛使用的数据集的综合实验显示其有效性和通用性。

##### URL
[https://arxiv.org/abs/1708.04308](https://arxiv.org/abs/1708.04308)

##### PDF
[https://arxiv.org/pdf/1708.04308](https://arxiv.org/pdf/1708.04308)

