---
layout: post
title: "Frequency-Aware Model Predictive Control"
date: 2018-09-12 16:08:06
categories: arXiv_RO
tags: arXiv_RO Tracking Optimization
author: Ruben Grandia, Farbod Farshidian, Alexey Dosovitskiy, René Ranftl, Marco Hutter
mathjax: true
---

* content
{:toc}

##### Abstract
Transferring solutions found by trajectory optimization to robotic hardware remains a challenging task. When the optimization fully exploits the provided model to perform dynamic tasks, the presence of unmodeled dynamics renders the motion infeasible on the real system. Model errors can be a result of model simplifications, but also naturally arise when deploying the robot in unstructured and nondeterministic environments. Predominantly, compliant contacts and actuator dynamics lead to bandwidth limitations. Bandwidth limits arising from compliant contacts and actuator dynamics tend to occur at high frequencies. While classical control methods provide tools to synthesize controllers that are robust to a class of model errors, such a notion is missing in modern trajectory optimization, which is solved in the time domain. We propose frequency-shaped cost functions to achieve robust solutions in the context of optimal control for legged robots. Through simulation and hardware experiments we show that motion plans can be made compatible with bandwidth limits set by actuators and contact dynamics. The smoothness of the model predictive solutions can be continuously tuned without compromising the feasibility of the problem. Experiments with the quadrupedal robot ANYmal, which is driven by high-compliant series elastic actuators, showed significantly better tracking performance of the planned motion, torque, and force trajectories and enabled the machine to walk robustly on ground with unmodeled compliance.

##### Abstract (translated by Google)
将轨迹优化发现的解决方案转移到机器人硬件仍然是一项具有挑战性的任务。当优化完全利用所提供的模型来执行动态任务时，未建模动态的存在使得该运动在实际系统上不可行。模型错误可能是模型简化的结果，但在非结构化和非确定性环境中部署机器人时也会自然产生。主要是，兼容的触点和执行器动态导致带宽限制。柔性触点和执行器动态产生的带宽限制往往发生在高频。虽然经典控制方法提供了合成对一类模型误差具有鲁棒性的控制器的工具，但现代轨迹优化中缺少这样的概念，这在时域中得到了解决。我们提出频率成本函数，以便在腿式机器人的最优控制环境中实现稳健的解决方案。通过仿真和硬件实验，我们表明运动计划可以与执行器和接触动力学设置的带宽限制兼容。可以连续调整模型预测解决方案的平滑度，而不会影响问题的可行性。由高顺应性系列弹性致动器驱动的四足机器人ANYmal的实验表明，计划的运动，扭矩和力轨迹的跟踪性能明显更好，并使机器能够在未经建模的合规性的情况下稳健地行走在地面上。

##### URL
[https://arxiv.org/abs/1809.04539](https://arxiv.org/abs/1809.04539)

##### PDF
[https://arxiv.org/pdf/1809.04539](https://arxiv.org/pdf/1809.04539)

