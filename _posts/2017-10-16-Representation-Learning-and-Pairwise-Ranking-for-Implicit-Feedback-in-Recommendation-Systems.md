---
layout: post
title: "Representation Learning and Pairwise Ranking for Implicit Feedback in Recommendation Systems"
date: 2017-10-16 09:47:02
categories: arXiv_CL
tags: arXiv_CL Embedding Represenation_Learning Relation Recommendation
author: Sumit Sidana, Mikhail Trofimov, Oleg Horodnitskii, Charlotte Laclau, Yury Maximov, Massih-Reza Amini
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel ranking framework for collaborative filtering with the overall aim of learning user preferences over items by minimizing a pairwise ranking loss. We show the minimization problem involves dependent random variables and provide a theoretical analysis by proving the consistency of the empirical risk minimization in the worst case where all users choose a minimal number of positive and negative items. We further derive a Neural-Network model that jointly learns a new representation of users and items in an embedded space as well as the preference relation of users over the pairs of items. The learning objective is based on three scenarios of ranking losses that control the ability of the model to maintain the ordering over the items induced from the users' preferences, as well as, the capacity of the dot-product defined in the learned embedded space to produce the ordering. The proposed model is by nature suitable for implicit feedback and involves the estimation of only very few parameters. Through extensive experiments on several real-world benchmarks on implicit data, we show the interest of learning the preference and the embedding simultaneously when compared to learning those separately. We also demonstrate that our approach is very competitive with the best state-of-the-art collaborative filtering techniques proposed for implicit feedback.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的协作过滤排名框架，其总体目标是通过最小化成对排名损失来学习用户对项目的偏好。我们展示了最小化问题涉及相关的随机变量，并提供了一个理论分析，证明了在所有用户选择最少数量的正面和负面项目的最坏情况下经验风险最小化的一致性。我们进一步推导出一个神经网络模型，联合学习嵌入式空间中用户和项目的新表示以及用户对项目对的偏好关系。学习目标是基于三种排名损失情景，这三种情景控制着模型维持由用户偏好引起的项目顺序的能力，以及在学习的嵌入式空间中定义的点积的能力产生排序。所提出的模型本质上适合于隐式反馈并且涉及仅仅很少参数的估计。通过对隐式数据的几个实际基准进行广泛的实验，与单独学习相比，我们展示了同时学习偏好和嵌入的兴趣。我们还证明，我们的方法是非常有竞争力的最好的最先进的协作过滤技术提出的隐式反馈。

##### URL
[https://arxiv.org/abs/1705.00105](https://arxiv.org/abs/1705.00105)

##### PDF
[https://arxiv.org/pdf/1705.00105](https://arxiv.org/pdf/1705.00105)

