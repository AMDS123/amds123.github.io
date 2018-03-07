---
layout: post
title: "On Discrimination Discovery and Removal in Ranked Data using Causal Graph"
date: 2018-03-05 19:53:40
categories: arXiv_AI
tags: arXiv_AI GAN Classification Relation
author: Yongkai Wu, Lu Zhang, Xintao Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Predictive models learned from historical data are widely used to help companies and organizations make decisions. However, they may digitally unfairly treat unwanted groups, raising concerns about fairness and discrimination. In this paper, we study the fairness-aware ranking problem which aims to discover discrimination in ranked datasets and reconstruct the fair ranking. Existing methods in fairness-aware ranking are mainly based on statistical parity that cannot measure the true discriminatory effect since discrimination is causal. On the other hand, existing methods in causal-based anti-discrimination learning focus on classification problems and cannot be directly applied to handle the ranked data. To address these limitations, we propose to map the rank position to a continuous score variable that represents the qualification of the candidates. Then, we build a causal graph that consists of both the discrete profile attributes and the continuous score. The path-specific effect technique is extended to the mixed-variable causal graph to identify both direct and indirect discrimination. The relationship between the path-specific effects for the ranked data and those for the binary decision is theoretically analyzed. Finally, algorithms for discovering and removing discrimination from a ranked dataset are developed. Experiments using the real dataset show the effectiveness of our approaches.

##### Abstract (translated by Google)
从历史数据中学习的预测模型被广泛用于帮助公司和组织做出决策。然而，他们可能在数字上不公平地对待不想要的群体，引起对公平和歧视的担忧。在本文中，我们研究公平意识排名问题，旨在发现排名数据集中的歧视并重构公平排名。公平意识排名中的现有方法主要基于统计平价，因为歧视是因果关系，因此无法衡量真正的歧视性效应。另一方面，现有的基于因果的反歧视学习方法主要集中在分类问题上，不能直接用于处理排序数据。为了解决这些限制，我们建议将等级位置映射到代表候选人资格的连续得分变量。然后，我们建立由离散概要属性和连续得分组成的因果图。将路径特定效应技术扩展到混合因变量因果图，以识别直接和间接歧视。理论上分析了排名数据和二元决策的特定路径效应之间的关系。最后，开发了用于发现和消除排名数据集中歧视的算法。使用真实数据集的实验显示了我们方法的有效性。

##### URL
[http://arxiv.org/abs/1803.01901](http://arxiv.org/abs/1803.01901)

##### PDF
[http://arxiv.org/pdf/1803.01901](http://arxiv.org/pdf/1803.01901)

