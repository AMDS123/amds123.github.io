---
layout: post
title: "Real-Time Dense Stereo Matching With ELAS on FPGA Accelerated Embedded Devices"
date: 2018-02-20 17:24:28
categories: arXiv_CV
tags: arXiv_CV
author: Oscar Rahnama, Duncan Frost, Ondrej Miksik, Philip H.S. Torr
mathjax: true
---

* content
{:toc}

##### Abstract
For many applications in low-power real-time robotics, stereo cameras are the sensors of choice for depth perception as they are typically cheaper and more versatile than their active counterparts. Their biggest drawback, however, is that they do not directly sense depth maps; instead, these must be estimated through data-intensive processes. Therefore, appropriate algorithm selection plays an important role in achieving the desired performance characteristics. 
 Motivated by applications in space and mobile robotics, we implement and evaluate a FPGA-accelerated adaptation of the ELAS algorithm. Despite offering one of the best trade-offs between efficiency and accuracy, ELAS has only been shown to run at 1.5-3 fps on a high-end CPU. Our system preserves all intriguing properties of the original algorithm, such as the slanted plane priors, but can achieve a frame rate of 47fps whilst consuming under 4W of power. Unlike previous FPGA based designs, we take advantage of both components on the CPU/FPGA System-on-Chip to showcase the strategy necessary to accelerate more complex and computationally diverse algorithms for such low power, real-time systems.

##### Abstract (translated by Google)
对于低功耗实时机器人中的许多应用来说，立体相机是深度感知的首选传感器，因为它们通常比其活动对象更便宜且更通用。然而，它们最大的缺点是它们不直接感知深度图。相反，这些必须通过数据密集型流程进行估算。因此，适当的算法选择在实现所需的性能特征方面起着重要的作用。
 受空间和移动机器人应用的驱动，我们实施并评估了ELAS算法的FPGA加速适应。尽管在效率和准确性之间提供了最好的折衷之一，但ELAS仅在高端CPU上以1.5-3 fps运行。我们的系统保留了原始算法的所有吸引人的特性，例如倾斜的平面先验，但是在4W功率下消耗时可以达到47fps的帧速率。与以前的基于FPGA的设计不同，我们利用CPU / FPGA片上系统的两个组件来展示加速这种低功耗实时系统的更复杂和计算多样化算法所需的策略。

##### URL
[http://arxiv.org/abs/1802.07210](http://arxiv.org/abs/1802.07210)

##### PDF
[http://arxiv.org/pdf/1802.07210](http://arxiv.org/pdf/1802.07210)

