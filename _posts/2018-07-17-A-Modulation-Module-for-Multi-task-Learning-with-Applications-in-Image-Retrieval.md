---
layout: post
title: "A Modulation Module for Multi-task Learning with Applications in Image Retrieval"
date: 2018-07-17 23:33:24
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Face CNN Relation
author: Xiangyun Zhao, Haoxiang Li, Xiaohui Shen, Xiaodan Liang, Ying Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-task learning has been widely adopted in many computer vision tasks to improve overall computation efficiency or boost the performance of individual tasks, under the assumption that those tasks are correlated and complementary to each other. However, the relationships between the tasks are complicated in practice, especially when the number of involved tasks scales up. When two tasks are of weak relevance, they may compete or even distract each other during joint training of shared parameters, and as a consequence undermine the learning of all the tasks. This will raise destructive interference which decreases learning efficiency of shared parameters and lead to low quality loss local optimum w.r.t. shared parameters. To address the this problem, we propose a general modulation module, which can be inserted into any convolutional neural network architecture, to encourage the coupling and feature sharing of relevant tasks while disentangling the learning of irrelevant tasks with minor parameters addition. Equipped with this module, gradient directions from different tasks can be enforced to be consistent for those shared parameters, which benefits multi-task joint training. The module is end-to-end learnable without ad-hoc design for specific tasks, and can naturally handle many tasks at the same time. We apply our approach on two retrieval tasks, face retrieval on the CelebA dataset [1] and product retrieval on the UT-Zappos50K dataset [2, 3], and demonstrate its advantage over other multi-task learning methods in both accuracy and storage efficiency.

##### Abstract (translated by Google)
多任务学习已被广​​泛应用于许多计算机视觉任务中，以在这些任务相互关联和互补的假设下提高整体计算效率或提高单个任务的性能。但是，任务之间的关系在实践中是复杂的，特别是当涉及的任务数量增加时。当两个任务具有弱相关性时，它们可能在共享参数的联合训练期间相互竞争甚至分散注意力，并且因此破坏了对所有任务的学习。这将提高破坏性干扰，这降低了共享参数的学习效率并导致低质量损失局部最优w.r.t.共享参数。为了解决这个问题，我们提出了一个通用调制模块，它可以插入到任何卷积神经网络架构中，以鼓励相关任务的耦合和特征共享，同时通过添加少量参数解开无关任务的学习。配备此模块，可以强制执行来自不同任务的梯度方向，以使这些共享参数保持一致，从而有利于多任务联合培训。该模块是端到端可学习的，无需针对特定任务的临时设计，并且可以自然地同时处理许多任务。我们将方法应用于两个检索任务，即CelebA数据集上的面部检索[1]和UT-Zappos50K数据集上的产品检索[2,3]，并证明其在准确性和存储效率方面优于其他多任务学习方法。

##### URL
[https://arxiv.org/abs/1807.06708](https://arxiv.org/abs/1807.06708)

##### PDF
[https://arxiv.org/pdf/1807.06708](https://arxiv.org/pdf/1807.06708)

