---
layout: post
title: "Collaborative Memory Network for Recommendation Systems"
date: 2018-06-21 00:02:12
categories: arXiv_CV
tags: arXiv_CV Attention Deep_Learning Relation Memory_Networks Recommendation
author: Travis Ebesu, Bin Shen, Yi Fang
mathjax: true
---

* content
{:toc}

##### Abstract
Recommendation systems play a vital role to keep users engaged with personalized content in modern online platforms. Deep learning has revolutionized many research fields and there is a recent surge of interest in applying it to collaborative filtering (CF). However, existing methods compose deep learning architectures with the latent factor model ignoring a major class of CF models, neighborhood or memory-based approaches. We propose Collaborative Memory Networks (CMN), a deep architecture to unify the two classes of CF models capitalizing on the strengths of the global structure of latent factor model and local neighborhood-based structure in a nonlinear fashion. Motivated by the success of Memory Networks, we fuse a memory component and neural attention mechanism as the neighborhood component. The associative addressing scheme with the user and item memories in the memory module encodes complex user-item relations coupled with the neural attention mechanism to learn a user-item specific neighborhood. Finally, the output module jointly exploits the neighborhood with the user and item memories to produce the ranking score. Stacking multiple memory modules together yield deeper architectures capturing increasingly complex user-item relations. Furthermore, we show strong connections between CMN components, memory networks and the three classes of CF models. Comprehensive experimental results demonstrate the effectiveness of CMN on three public datasets outperforming competitive baselines. Qualitative visualization of the attention weights provide insight into the model's recommendation process and suggest the presence of higher order interactions.

##### Abstract (translated by Google)
推荐系统在使用户在现代在线平台中使用个性化内容方面发挥着至关重要的作用。深度学习已经彻底改变了许多研究领域，并且最近对将其应用于协同过滤（CF）的兴趣激增。然而，现有方法构成深度学习架构，潜在因子模型忽略了主要的CF模型，邻域或基于存储器的方法。我们提出了协同存储网络（CMN），这是一种深度架构，用于统一两类CF模型，以非线性方式利用潜在因子模型和局部邻域结构的全局结构的优势。在Memory Networks的成功推动下，我们将存储器组件和神经注意机制融合为邻域组件。具有存储器模块中的用户和项目存储器的关联寻址方案编码与神经注意机制耦合的复杂用户 - 项目关系，以学习用户项目特定邻域。最后，输出模块共同利用邻域与用户和项目存储器来产生排名分数。将多个内存模块堆叠在一起可以产生更深层次的体系结构，从而捕获越来越复杂此外，我们展示了CMN组件，内存网络和三类CF模型之间的紧密联系。综合实验结果证明了CMN对三个公共数据集的有效性超过了竞争基线。注意力量的定性可视化提供了对模型推荐过程的洞察，并建议存在更高阶的交互。

##### URL
[https://arxiv.org/abs/1804.10862](https://arxiv.org/abs/1804.10862)

##### PDF
[https://arxiv.org/pdf/1804.10862](https://arxiv.org/pdf/1804.10862)

