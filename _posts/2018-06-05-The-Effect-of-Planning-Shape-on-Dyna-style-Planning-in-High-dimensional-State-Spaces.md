---
layout: post
title: "The Effect of Planning Shape on Dyna-style Planning in High-dimensional State Spaces"
date: 2018-06-05 17:31:02
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: G. Zacharias Holland, Erik Talvitie, Michael Bowling
mathjax: true
---

* content
{:toc}

##### Abstract
Dyna is an architecture for reinforcement learning agents that interleaves planning, acting, and learning in an online setting. This architecture aims to make fuller use of limited experience to achieve better performance with fewer environmental interactions. Dyna has been well studied in problems with a tabular representation of states, and has also been extended to some settings with larger state spaces that require function approximation. However, little work has studied Dyna in environments with high-dimensional state spaces like images. In Dyna, the environment model is typically used to generate one-step transitions from selected start states. We applied one-step Dyna to several games from the Arcade Learning Environment and found that the model-based updates offered surprisingly little benefit, even with a perfect model. However, when the model was used to generate longer trajectories of simulated experience, performance improved dramatically. This observation also holds when using a model that is learned from experience; even though the learned model is flawed, it can still be used to accelerate learning.

##### Abstract (translated by Google)
Dyna是一个强化学习代理的体系结构，它在一个在线环境中交织计划，行为和学习。这种架构旨在更充分地利用有限的经验，以更少的环境相互作用实现更好的性能。 Dyna已经很好地研究了状态表格问题，并且已经扩展到一些需要函数逼近的更大状态空间的设置。然而，在像图像这样的高维度状态空间的环境中，很少有工作研究Dyna。在Dyna中，环境模型通常用于从选定的启动状态生成一步转换。我们从Arcade学习环境的几个游戏中应用了一步Dyna，发现基于模型的更新提供了惊人的小好处，即使是完美的模型。然而，当模型被用于产生更长的仿真体验轨迹时，性能显着提高。当使用从经验中学习的模型时，这种观察也是成立的。即使学习模型有缺陷，它仍然可以用来加速学习。

##### URL
[http://arxiv.org/abs/1806.01825](http://arxiv.org/abs/1806.01825)

##### PDF
[http://arxiv.org/pdf/1806.01825](http://arxiv.org/pdf/1806.01825)

