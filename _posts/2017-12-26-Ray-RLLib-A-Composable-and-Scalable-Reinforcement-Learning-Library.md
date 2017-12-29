---
layout: post
title: "Ray RLLib: A Composable and Scalable Reinforcement Learning Library"
date: 2017-12-26 19:43:59
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Eric Liang, Richard Liaw, Robert Nishihara, Philipp Moritz, Roy Fox, Joseph Gonzalez, Ken Goldberg, Ion Stoica
mathjax: true
---

* content
{:toc}

##### Abstract
Reinforcement learning (RL) algorithms involve the deep nesting of distinct components, where each component typically exhibits opportunities for distributed computation. Current RL libraries offer parallelism at the level of the entire program, coupling all the components together and making existing implementations difficult to extend, combine, and reuse. We argue for building composable RL components by encapsulating parallelism and resource requirements within individual components, which can be achieved by building on top of a flexible task-based programming model. We demonstrate this principle by building Ray RLLib on top of Ray and show that we can implement a wide range of state-of-the-art algorithms by composing and reusing a handful of standard components. This composability does not come at the cost of performance --- in our experiments, RLLib matches or exceeds the performance of highly optimized reference implementations. Ray RLLib is available as part of Ray at https://github.com/ray-project/ray/.

##### Abstract (translated by Google)
强化学习（RL）算法涉及不同组件的深层嵌套，其中每个组件通常展现分布式计算的机会。当前的RL库在整个程序层面提供了并行性，将所有组件连接在一起，使现有的实现难以扩展，组合和重用。我们主张通过在单个组件中封装并行性和资源需求来构建可组合的RL组件，这可以通过基于灵活的基于任务的编程模型来实现。我们通过在Ray之上构建Ray RLLib来证明这一原理，并证明我们可以通过组合和重用少数标准组件来实现各种最先进的算法。这种可组合性不以性能为代价---在我们的实验中，RLLib匹配或超过高度优化的参考实现的性能。 Ray RLLib作为Ray的一部分在https://github.com/ray-project/ray/上提供。

##### URL
[http://arxiv.org/abs/1712.09381](http://arxiv.org/abs/1712.09381)

##### PDF
[http://arxiv.org/pdf/1712.09381](http://arxiv.org/pdf/1712.09381)

