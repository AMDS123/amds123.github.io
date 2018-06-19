---
layout: post
title: "Application of Wrench based Feasibility Analysis to the Online Trajectory Optimization of Legged Robots"
date: 2018-06-18 17:44:38
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Romeo Orsolino (1), Michele Focchi (1), Carlos Mastalli (1 and 2), Hongkai Dai (3), Darwin G. Caldwell (1), Claudio Semini (1) ((1) Department of Advanced Robotics, Istituto Italiano di Tecnologia (IIT), (2) CNRS, LAAS, University of Toulouse, (3) Toyota Research Institute (TRI))
mathjax: true
---

* content
{:toc}

##### Abstract
Motion planning in multi-contact scenarios has recently gathered interest within the legged robotics community, however actuator force/torque limits are rarely considered. We believe that these limits gain paramount importance when the complexity of the terrains to be traversed increases. We build on previous research from the field of robotic grasping to propose two new six-dimensional bounded polytopes named the Actuation Wrench Polytope (AWP) and the Feasible Wrench Polytope (FWP). We define the AWP as the set of all the wrenches that a robot can generate while considering its actuation limits. This considers the admissible contact forces that the robot can generate given its current configuration and actuation capabilities. The Contact Wrench Cone (CWC), instead, includes features of the environment such as the contact normal or the friction coefficient. The intersection of the AWP and of the CWC results in a convex polytope, the FWP, which turns out to be more descriptive of the real robot capabilities than existing simplified models, while maintaining the same compact representation. We explain how to efficiently compute the vertex-description of the FWP that is then used to evaluate a feasibility factor that we adapted from the field of robotic grasping. This allows us to optimize for robustness to external disturbance wrenches. Based on this, we present an implementation of a motion planner for our quadruped robot HyQ that provides online Center of Mass (CoM) trajectories that are guaranteed to be statically stable and actuation consistent.

##### Abstract (translated by Google)
近来，多接触场景中的运动规划已经引起了有腿机器人界的兴趣，但是很少考虑执行器力/扭矩限制。我们认为，当要穿越的地形的复杂性增加时，这些限制变得极为重要。我们在机器人抓取领域的先前研究的基础上提出了两种新的六维有界多面体，称为驱动扳手多面体（AWP）和可行扳手多面体（FWP）。我们将AWP定义为机器人在考虑驱动极限时可以产生的所有扳手的集合。考虑到机器人在当前的配置和驱动能力下可以产生的容许接触力。相反，接触扳手锥（CWC）包括环境特征，例如接触法向或摩擦系数。 AWP和CWC的交点产生了一个凸多面体FWP，它比现有简化模型更能描述真实的机器人能力，同时保持相同的紧凑表示。我们解释了如何有效地计算FWP的顶点描述，然后用它来评估我们从机器人抓取领域改编的可行性因素。这使我们能够优化外部干扰扳手的坚固性。基于此，我们为四足机器人HyQ提供了一个运动规划器的实现，它提供了在线质心中心（CoM）轨迹，这些轨迹保证了静态稳定性和驱动一致性。

##### URL
[http://arxiv.org/abs/1712.06833](http://arxiv.org/abs/1712.06833)

##### PDF
[http://arxiv.org/pdf/1712.06833](http://arxiv.org/pdf/1712.06833)

