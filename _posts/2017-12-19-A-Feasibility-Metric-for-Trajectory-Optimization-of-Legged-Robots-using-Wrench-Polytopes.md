---
layout: post
title: "A Feasibility Metric for Trajectory Optimization of Legged Robots using Wrench Polytopes"
date: 2017-12-19 09:20:03
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Romeo Orsolino (1), Michele Focchi (1), Carlos Mastalli (1 and 2), Hongkai Dai (3), Darwin G. Caldwell (1), Claudio Semini (1) ((1) Department of Advanced Robotics, Istituto Italiano di Tecnologia (IIT), (2) CNRS, LAAS, University of Toulouse, (3) Toyota Research Institute (TRI))
mathjax: true
---

* content
{:toc}

##### Abstract
Motion planning in multi-contact scenarios has recently gathered interest within the legged robotics community, however actuator force/torque limits are rarely considered. We believe that these limits gain paramount importance when the complexity of the terrains to be traversed increases. For this reason we propose two new six-dimensional bounded polytopes named the Actuation Wrench Polytope (AWP) and the Feasible Wrench Polytope (FWP). We define the AWP as the set of all the wrenches that a robot can generate on its own Center of Mass (CoM) while considering its actuation limits. This considers the admissible contact forces that the robot can generate given its current configuration and actuation capabilities but does not include features of the environment such as the contact normal or the friction coefficient. These are considered by the Contact Wrench Cone (CWC); the AWP can therefore be seen as complementary with respect to the CWC. The intersection of the AWP and of the CWC results in a polytope, the FWP, which turns out to be more descriptive of the real robot capabilities, while maintaining the same compact representation. We explain how to efficiently compute the vertex-description of the FWP and we also introduce a new locomotion stability metric based on the FWP, that we call feasibility margin, which allows us to optimize for robustness to external disturbance wrenches. Based on this, we present an implementation of a motion planner for our quadruped robot HyQ that provides online CoM trajectories that are guaranteed to be stable and actuation-consistent.

##### Abstract (translated by Google)
多接触场景中的运动规划最近引起了人们对有腿机器人领域的兴趣，然而执行器的力/力矩限制却很少被考虑到。我们认为，当地形的复杂性增加时，这些限制是非常重要的。出于这个原因，我们提出了两个新的六维有界多面体命名扳手多面体（AWP）和可行扳手多面体（FWP）。我们将AWP定义为机器人可以在其自身的质量中心（CoM）上生成的所有扳手的集合，同时考虑其驱动限制。考虑到机器人在当前配置和驱动能力的情况下可以产生的容许接触力，但不包括接触法线或摩擦系数等环境特征。联系扳手锥（CWC）对此进行了考虑;因此AWP可以被看作是对CWC的补充。 AWP和CWC的交点产生了一个多面体FWP，这个多面体在保持相同的紧凑表示的同时，更能描述真实的机器人能力。我们解释了如何有效地计算FWP的顶点描述，并且还引入了基于FWP的新的运动稳定性度量，我们称之为可行性裕度，这使得我们可以优化对外部扰动扳手的鲁棒性。在此基础上，我们提出了四足机器人HyQ的运动计划器的实现，该机器人提供在线CoM轨迹，保证了稳定性和驱动一致性。

##### URL
[http://arxiv.org/abs/1712.06833](http://arxiv.org/abs/1712.06833)

##### PDF
[http://arxiv.org/pdf/1712.06833](http://arxiv.org/pdf/1712.06833)

