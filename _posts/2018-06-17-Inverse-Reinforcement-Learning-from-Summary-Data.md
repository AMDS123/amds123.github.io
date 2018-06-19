---
layout: post
title: "Inverse Reinforcement Learning from Summary Data"
date: 2018-06-17 06:46:22
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Inference
author: Antti Kangasr&#xe4;&#xe4;si&#xf6;, Samuel Kaski
mathjax: true
---

* content
{:toc}

##### Abstract
Inverse reinforcement learning (IRL) aims to explain observed strategic behavior by fitting reinforcement learning models to behavioral data. However, traditional IRL methods are only applicable when the observations are in the form of state-action paths. This assumption may not hold in many real-world modeling settings, where only partial or summarized observations are available. In general, we may assume that there is a summarizing function $\sigma$, which acts as a filter between us and the true state-action paths that constitute the demonstration. Some initial approaches to extending IRL to such situations have been presented, but with very specific assumptions about the structure of $\sigma$, such as that only certain state observations are missing. This paper instead focuses on the most general case of the problem, where no assumptions are made about the summarizing function, except that it can be evaluated. We demonstrate that inference is still possible. The paper presents exact and approximate inference algorithms that allow full posterior inference, which is particularly important for assessing parameter uncertainty in this challenging inference situation. Empirical scalability is demonstrated to reasonably sized problems, and practical applicability is demonstrated by estimating the posterior for a cognitive science RL model based on an observed user's task completion time only.

##### Abstract (translated by Google)
逆强化学习（IRL）旨在通过将强化学习模型拟合到行为数据来解释观察到的战略行为。然而，传统的IRL方法只适用于观察结果为国家行动路径的形式。这种假设可能不适用于许多现实世界的建模设置，其中只有部分或概括的观察结果可用。总的来说，我们可以假设有一个总结函数$ \ sigma $，它作为我们与构成演示的真实状态行为路径之间的过滤器。已经提出了将IRL扩展到这种情况的一些初始方法，但是对$ \ sigma $的结构进行了非常具体的假设，例如仅缺少某些状态观察值。本文将重点放在最常见的问题上，除了可以对其进行评估之外，不对总结函数作出任何假设。我们证明推论仍然是可能的。本文提出了确切的和近似的推理算法，可以进行完全后验推理，这对于评估这种具有挑战性的推理情况下的参数不确定性尤为重要。经验可伸缩性被证明为合理大小的问题，并且仅基于观察到的用户的任务完成时间通过估计认知科学RL模型的后验来证明实际适用性。

##### URL
[http://arxiv.org/abs/1703.09700](http://arxiv.org/abs/1703.09700)

##### PDF
[http://arxiv.org/pdf/1703.09700](http://arxiv.org/pdf/1703.09700)

