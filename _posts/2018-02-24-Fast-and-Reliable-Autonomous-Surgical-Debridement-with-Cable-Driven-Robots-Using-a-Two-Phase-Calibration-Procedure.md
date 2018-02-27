---
layout: post
title: "Fast and Reliable Autonomous Surgical Debridement with Cable-Driven Robots Using a Two-Phase Calibration Procedure"
date: 2018-02-24 08:34:58
categories: arXiv_RO
tags: arXiv_RO Detection
author: Daniel Seita, Sanjay Krishnan, Roy Fox, Stephen McKinley, John Canny, Ken Goldberg
mathjax: true
---

* content
{:toc}

##### Abstract
Automating precision subtasks such as debridement (removing dead or diseased tissue fragments) with Robotic Surgical Assistants (RSAs) such as the da Vinci Research Kit (dVRK) is challenging due to inherent non-linearities in cable-driven systems. We propose and evaluate a novel two-phase coarse-to-fine calibration method. In Phase I (coarse), we place a red calibration marker on the end effector and let it randomly move through a set of open-loop trajectories to obtain a large sample set of camera pixels and internal robot end-effector configurations. This coarse data is then used to train a Deep Neural Network (DNN) to learn the coarse transformation bias. In Phase II (fine), the bias from Phase I is applied to move the end-effector toward a small set of specific target points on a printed sheet. For each target, a human operator manually adjusts the end-effector position by direct contact (not through teleoperation) and the residual compensation bias is recorded. This fine data is then used to train a Random Forest (RF) to learn the fine transformation bias. Subsequent experiments suggest that without calibration, position errors average 4.55mm. Phase I can reduce average error to 2.14mm and the combination of Phase I and Phase II can reduces average error to 1.08mm. We apply these results to debridement of raisins and pumpkin seeds as fragment phantoms. Using an endoscopic stereo camera with standard edge detection, experiments with 120 trials achieved average success rates of 94.5%, exceeding prior results with much larger fragments (89.4%) and achieving a speedup of 2.1x, decreasing time per fragment from 15.8 seconds to 7.3 seconds. Source code, data, and videos are available at https://sites.google.com/view/calib-icra/.

##### Abstract (translated by Google)
由于电缆驱动系统固有的非线性，使用机器人手术助手（RSA）（如达芬奇研究工具包（dVRK））自动执行精确子任务，如清创术（清除死亡或患病组织碎片）具有挑战性。我们提出并评估了一种新颖的两阶段从粗到精的校准方法。在阶段I（粗略）中，我们在末端执行器上放置一个红色校准标记，让它随机移动通过一组开环轨迹，以获得一大组相机像素和内部机器人末端效应器配置。这个粗糙的数据然后用于训练深度神经网络（DNN）以学习粗略的变换偏差。在阶段II（罚款）中，阶段I的偏差被用于将末端执行器移向印张上的一小组特定目标点。对于每个目标，操作人员通过直接接触（不通过遥控操作）手动调整末端执行器位置，并记录剩余补偿偏差。然后使用这些精细的数据来训练随机森林（RF）来学习精细的转换偏差。随后的实验表明，没有校准，位置误差平均为4.55毫米。第一阶段可将平均误差降至2.14毫米，第一阶段和第二阶段的组合可将平均误差降至1.08毫米。我们将这些结果应用于葡萄干和南瓜子作为片段模型的清创。使用具有标准边缘检测的内窥镜立体相机，120次试验的实验平均成功率达到94.5％，超过以前的结果，更大的碎片（89.4％），实现2.1倍的加速，每个碎片的时间从15.8秒减少到7.3秒。源代码，数据和视频可通过https://sites.google.com/view/calib-icra/获取。

##### URL
[http://arxiv.org/abs/1709.06668](http://arxiv.org/abs/1709.06668)

##### PDF
[http://arxiv.org/pdf/1709.06668](http://arxiv.org/pdf/1709.06668)

