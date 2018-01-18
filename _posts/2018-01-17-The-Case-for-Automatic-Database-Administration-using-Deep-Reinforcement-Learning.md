---
layout: post
title: "The Case for Automatic Database Administration using Deep Reinforcement Learning"
date: 2018-01-17 12:51:01
categories: arXiv_AI
tags: arXiv_AI GAN Reinforcement_Learning Recommendation
author: Ankur Sharma, Felix Martin Schuhknecht, Jens Dittrich
mathjax: true
---

* content
{:toc}

##### Abstract
Like any large software system, a full-fledged DBMS offers an overwhelming amount of configuration knobs. These range from static initialisation parameters like buffer sizes, degree of concurrency, or level of replication to complex runtime decisions like creating a secondary index on a particular column or reorganising the physical layout of the store. To simplify the configuration, industry grade DBMSs are usually shipped with various advisory tools, that provide recommendations for given workloads and machines. However, reality shows that the actual configuration, tuning, and maintenance is usually still done by a human administrator, relying on intuition and experience. Recent work on deep reinforcement learning has shown very promising results in solving problems, that require such a sense of intuition. For instance, it has been applied very successfully in learning how to play complicated games with enormous search spaces. Motivated by these achievements, in this work we explore how deep reinforcement learning can be used to administer a DBMS. First, we will describe how deep reinforcement learning can be used to automatically tune an arbitrary software system like a DBMS by defining a problem environment. Second, we showcase our concept of NoDBA at the concrete example of index selection and evaluate how well it recommends indexes for given workloads.

##### Abstract (translated by Google)
像任何大型软件系统一样，一个成熟的DBMS提供了大量的配置旋钮。这些范围从静态初始化参数（如缓冲区大小，并发度或复制级别）到复杂运行时决策（如在特定列上创建二级索引或重新组织物理布局）。为了简化配置，工业级DBMS通常随附各种咨询工具，为给定的工作负载和机器提供建议。然而，现实表明，实际的配置，调整和维护通常依靠直觉和经验依然由管理员完成。最近深入强化学习的工作已经显示出解决问题的非常有希望的结果，需要这种直觉。例如，在学习如何在庞大的搜索空间下玩复杂的游戏方面已经非常成功。受到这些成就的启发，在这项工作中，我们探讨了如何使用强化学习来管理数据库管理系统。首先，我们将通过定义问题环境来描述如何使用深度强化学习来自动调整像DBMS这样的任意软件系统。其次，我们在索引选择的具体例子中展示了我们的NoDBA概念，并评估它对给定工作负载推荐索引的好坏。

##### URL
[http://arxiv.org/abs/1801.05643](http://arxiv.org/abs/1801.05643)

##### PDF
[http://arxiv.org/pdf/1801.05643](http://arxiv.org/pdf/1801.05643)

