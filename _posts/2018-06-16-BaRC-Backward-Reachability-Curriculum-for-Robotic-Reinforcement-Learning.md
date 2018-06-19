---
layout: post
title: "BaRC: Backward Reachability Curriculum for Robotic Reinforcement Learning"
date: 2018-06-16 00:59:11
categories: arXiv_RO
tags: arXiv_RO Sparse Reinforcement_Learning Optimization
author: Boris Ivanovic, James Harrison, Apoorva Sharma, Mo Chen, Marco Pavone
mathjax: true
---

* content
{:toc}

##### Abstract
Model-free Reinforcement Learning (RL) offers an attractive approach to learn control policies for high-dimensional systems, but its relatively poor sample complexity often forces training in simulated environments. Even in simulation, goal-directed tasks whose natural reward function is sparse remain intractable for state-of-the-art model-free algorithms for continuous control. The bottleneck in these tasks is the prohibitive amount of exploration required to obtain a learning signal from the initial state of the system. In this work, we leverage physical priors in the form of an approximate system dynamics model to design a curriculum scheme for a model-free policy optimization algorithm. Our Backward Reachability Curriculum (BaRC) begins policy training from states that require a small number of actions to accomplish the task, and expands the initial state distribution backwards in a dynamically-consistent manner once the policy optimization algorithm demonstrates sufficient performance. BaRC is general, in that it can accelerate training of any model-free RL algorithm on a broad class of goal-directed continuous control MDPs. Its curriculum strategy is physically intuitive, easy-to-tune, and allows incorporating physical priors to accelerate training without hindering the performance, flexibility, and applicability of the model-free RL algorithm. We evaluate our approach on two representative dynamic robotic learning problems and find substantial performance improvement relative to previous curriculum generation techniques and naive exploration strategies.

##### Abstract (translated by Google)
无模型强化学习（RL）提供了一种有吸引力的方法来学习高维系统的控制策略，但其相对较差的样本复杂性往往会在模拟环境中强制进行培训。即使在仿真中，自然回报函数稀疏的目标导向任务仍然难以用于连续控制的最先进的无模型算法。这些任务的瓶颈是从系统的初始状态获取学习信号所需的大量探索。在这项工作中，我们以近似系统动力学模型的形式利用物理先验来为无模型策略优化算法设计课程方案。我们的后向可达性课程（BaRC）从需要少量动作来完成任务的州开始进行政策培训，并且一旦策略优化算法表现出足够的性能，就会以动态一致的方式向后扩展初始状态分布。 BaRC是一般性的，因为它可以加速对广泛的目标导向连续控制MDPs上的任何无模型RL算法的训练。其课程策略具有直观，易于调整的特点，并且可以结合物理优先项目加速培训，而不会影响无模型RL算法的性能，灵活性和适用性。我们评估我们的方法在两个有代表性的动态机器人学习问题上，发现相对于以前的课程生成技术和天真的探索策略而言性能有了显着提高

##### URL
[http://arxiv.org/abs/1806.06161](http://arxiv.org/abs/1806.06161)

##### PDF
[http://arxiv.org/pdf/1806.06161](http://arxiv.org/pdf/1806.06161)

