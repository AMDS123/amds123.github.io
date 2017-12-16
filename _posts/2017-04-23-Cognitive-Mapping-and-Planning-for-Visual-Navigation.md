---
layout: post
title: "Cognitive Mapping and Planning for Visual Navigation"
date: 2017-04-23 01:59:30
categories: arXiv_CV
tags: arXiv_CV
author: Saurabh Gupta, James Davidson, Sergey Levine, Rahul Sukthankar, Jitendra Malik
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a neural architecture for navigation in novel environments. Our proposed architecture learns to map from first-person views and plans a sequence of actions towards goals in the environment. The Cognitive Mapper and Planner (CMP) is based on two key ideas: a) a unified joint architecture for mapping and planning, such that the mapping is driven by the needs of the planner, and b) a spatial memory with the ability to plan given an incomplete set of observations about the world. CMP constructs a top-down belief map of the world and applies a differentiable neural net planner to produce the next action at each time step. The accumulated belief of the world enables the agent to track visited regions of the environment. Our experiments demonstrate that CMP outperforms both reactive strategies and standard memory-based architectures and performs well in novel environments. Furthermore, we show that CMP can also achieve semantically specified goals, such as "go to a chair".

##### Abstract (translated by Google)
我们在新环境中引入了一种导航的神经架构。我们提出的建筑学习从第一人称视角进行映射，并计划在环境中实现目标的一系列行动。认知映射器和规划器（CMP）基于两个关键思想：a）映射和规划的统一联合架构，使映射受计划者的需求驱动; b）具有计划能力的空间记忆给出了关于这个世界的一系列不完整的观察。 CMP构建了一个自上而下的世界信仰地图，并应用一个可微的神经网络规划器在每个时间步骤产生下一个动作。世界积累的信念使代理人能够跟踪访问过的环境区域。我们的实验证明，CMP性能优于反应式策略和基于标准内存的体系结构，并在新颖的环境中表现良好。此外，我们还表明，CMP还可以实现语义上指定的目标，例如“去主席”。

##### URL
[https://arxiv.org/abs/1702.03920](https://arxiv.org/abs/1702.03920)

##### PDF
[https://arxiv.org/pdf/1702.03920](https://arxiv.org/pdf/1702.03920)

