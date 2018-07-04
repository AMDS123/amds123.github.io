---
layout: post
title: "Tackling Occlusions & Limited Sensor Range with Set-based Safety Verification"
date: 2018-07-03 16:15:18
categories: arXiv_RO
tags: arXiv_RO Knowledge Face Prediction
author: Piotr Franciszek Orzechowski, Annika Meyer, Martin Lauer
mathjax: true
---

* content
{:toc}

##### Abstract
Provable safety is one of the most critical challenges in automated driving. The behavior of numerous traffic participants in a scene cannot be predicted reliably due to complex interdependencies and indiscriminate behavior of humans. Additionally we face high uncertainties and only incomplete environment knowledge. Recent approaches minimize risk with probabilistic and machine learning methods -- even under occlusions. These generate comfortable behavior with good traffic flow, but cannot guarantee safety of their maneuvers. Therefore we contribute a safety verification method for trajectories under occlusions. The field-of-view of the ego vehicle and a map are used to identify critical sensing field edges, each representing a potentially hidden obstacle. The state of occluded obstacles is unknown, but can be over-approximated by intervals over all possible states. Then set-based methods are extended to provide occupancy predictions for obstacles with state intervals. The proposed method can verify the safety of given trajectories (e.g. if they ensure collision-free fail-safe maneuver options) w.r.t. arbitrary safe-state formulations. The potential for provably safe trajectory planning is shown in three evaluative scenarios.

##### Abstract (translated by Google)
可证明的安全性是自动驾驶中最关键的挑战之一。由于复杂的相互依赖性和人类的不加选择的行为，无法可靠地预测场景中众多交通参与者的行为。此外，我们面临很高的不确定性和只有不完整的环境知最近的方法通过概率和机器学习方法将风险降至最低 - 即使在遮挡下也是如此。这些产生了良好的交通流量的舒适行为，但不能保证其机动的安全性。因此，我们为遮挡下的轨迹提供安全验证方法。自我车辆的视野和地图用于识别关键的感测场边缘，每个边缘代表潜在的隐藏障碍物。被遮挡障碍物的状态是未知的，但可以通过所有可能状态的间隔过度近似。然后扩展基于集合的方法以提供具有状态间隔的障碍物的占用预测。所提出的方法可以验证给定轨迹的安全性（例如，如果它们确保无碰撞的故障安全机动选项）w.r.t.任意安全状态配方。三种评估方案显示了可证明安全的轨迹规划的可能性。

##### URL
[https://arxiv.org/abs/1807.01262](https://arxiv.org/abs/1807.01262)

##### PDF
[https://arxiv.org/pdf/1807.01262](https://arxiv.org/pdf/1807.01262)

