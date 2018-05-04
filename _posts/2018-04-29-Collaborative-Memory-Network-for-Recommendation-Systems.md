---
layout: post
title: "Collaborative Memory Network for Recommendation Systems"
date: 2018-04-29 03:17:36
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
推荐系统对于保持用户在现代在线平台中使用个性化内容起着至关重要的作用。深度学习已经使许多研究领域发生了革命性的变化，最近将其应用于协同过滤（CF）的兴趣日益激增。然而，现有的方法构成了深度学习架构，潜在因素模型忽略了一大类CF模型，邻域或基于记忆的方法。我们提出协作内存网络（CMN），这是一种深层次的体系结构，以非线性方式利用潜在因子模型的全局结构和局部邻域结构的优势来统一两类CF模型。受到Memory Networks成功的启发，我们将存储器组件和神经关注机制融合为邻域组件。与存储器模块中的用户和物品存储器相关联的寻址方案编码复杂的用户项目关系以及神经关注机制以学习用户物品特定邻域。最后，输出模块共同利用用户和物品存储的邻域来产生排名分数。将多个内存模块堆叠在一起可产生更深层次的体系结构，以捕捉日益复杂的用户项目关系此外，我们还展示了CMN组件，内存网络和三类CF模型之间的强大连接。综合实验结果证明了CMN对三个公共数据集胜过竞争基线的有效性。关注权重的定性可视化提供了对模型推荐过程的深入了解，并提出了更高阶的相互作用的存在。

##### URL
[https://arxiv.org/abs/1804.10862](https://arxiv.org/abs/1804.10862)

##### PDF
[https://arxiv.org/pdf/1804.10862](https://arxiv.org/pdf/1804.10862)

