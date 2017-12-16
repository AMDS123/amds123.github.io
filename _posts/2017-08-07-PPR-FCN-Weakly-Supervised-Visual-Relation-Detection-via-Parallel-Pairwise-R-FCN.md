---
layout: post
title: "PPR-FCN: Weakly Supervised Visual Relation Detection via Parallel Pairwise R-FCN"
date: 2017-08-07 01:07:20
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised CNN Classification Detection Relation
author: Hanwang Zhang, Zawlin Kyaw, Jinyang Yu, Shih-Fu Chang
mathjax: true
---

* content
{:toc}

##### Abstract
We aim to tackle a novel vision task called Weakly Supervised Visual Relation Detection (WSVRD) to detect "subject-predicate-object" relations in an image with object relation groundtruths available only at the image level. This is motivated by the fact that it is extremely expensive to label the combinatorial relations between objects at the instance level. Compared to the extensively studied problem, Weakly Supervised Object Detection (WSOD), WSVRD is more challenging as it needs to examine a large set of regions pairs, which is computationally prohibitive and more likely stuck in a local optimal solution such as those involving wrong spatial context. To this end, we present a Parallel, Pairwise Region-based, Fully Convolutional Network (PPR-FCN) for WSVRD. It uses a parallel FCN architecture that simultaneously performs pair selection and classification of single regions and region pairs for object and relation detection, while sharing almost all computation shared over the entire image. In particular, we propose a novel position-role-sensitive score map with pairwise RoI pooling to efficiently capture the crucial context associated with a pair of objects. We demonstrate the superiority of PPR-FCN over all baselines in solving the WSVRD challenge by using results of extensive experiments over two visual relation benchmarks.

##### Abstract (translated by Google)
我们的目标是解决一个称为弱监督的视觉关系检测（WSVRD）的新视觉任务，以检测图像中的“主谓关系”关系。这是因为在实例级别标注对象之间的组合关系是极其昂贵的。与广泛研究的问题 - 弱监督对象检测（WSOD）相比，WSVRD更具挑战性，因为它需要检查大量的区域对，这在计算上是禁止的，并且更可能卡在局部最优解中，例如涉及错误空间上下文。为此，我们提出了WSVRD的并行，成对区域，全卷积网络（PPR-FCN）。它使用并行FCN架构，同时执行单个区域和区域对的对选和分类以用于对象和关系检测，同时共享几乎所有在整个图像上共享的计算。特别是，我们提出了一个新的位置 - 角色敏感分数图与成对的RoI池，以有效地捕捉与一对对象相关的关键上下文。我们通过在两个视觉关系基准上使用广泛的实验结果来证明PPR-FCN在解决WSVRD挑战中的优势。

##### URL
[https://arxiv.org/abs/1708.01956](https://arxiv.org/abs/1708.01956)

##### PDF
[https://arxiv.org/pdf/1708.01956](https://arxiv.org/pdf/1708.01956)

