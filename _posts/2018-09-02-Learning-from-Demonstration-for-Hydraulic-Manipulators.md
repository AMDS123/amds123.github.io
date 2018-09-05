---
layout: post
title: "Learning from Demonstration for Hydraulic Manipulators"
date: 2018-09-02 19:13:47
categories: arXiv_RO
tags: arXiv_RO Face
author: Markku Suomalainen, Janne Koivum&#xe4;ki, Santeri Lampinen, Ville Kyrki, Jouni Mattila
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents, for the first time, a method for learning in-contact tasks from a teleoperated demonstration with a hydraulic manipulator. Due to the use of extremely powerful hydraulic manipulator, a force-reflected bilateral teleoperation is the most reasonable method of giving a human demonstration. An advanced subsystem-dynamic-based control design framework, virtual decomposition control (VDC), is used to design a stability-guaranteed controller for the teleoperation system, while taking into account the full nonlinear dynamics of the master and slave manipulators. The use of fragile force/ torque sensor at the tip of the hydraulic slave manipulator is avoided by estimating the contact forces from the manipulator actuators' chamber pressures. In the proposed learning method, it is observed that a surface-sliding tool has a friction-dependent range of directions (between the actual direction of motion and the contact force) from which the manipulator can apply force to produce the sliding motion. By this intuition, an intersection of these ranges can be taken over a motion to robustly find a desired direction for the motion from one or more demonstrations. The compliant axes required to reproduce the motion can be found by assuming that all motions outside the desired direction is caused by the environment, signalling the need for compliance. Finally, the learning method is incorporated to a novel VDC-based impedance control method to learn compliant behaviour from teleoperated human demonstrations. Experiments with 2-DOF hydraulic manipulator with a 475kg payload demonstrate the suitability and effectiveness of the proposed method to perform learning from demonstration (LfD) with heavy-duty hydraulic manipulators.

##### Abstract (translated by Google)
本文首次介绍了一种通过液压机械手进行远程操作演示来学习接触式任务的方法。由于使用了极其强大的液压操纵器，力反射的双边遥操作是进行人体演示的最合理方法。先进的基于子系统动态的控制设计框架，即虚拟分解控制（VDC），用于为遥操作系统设计稳定性保证控制器，同时考虑主从机械手的完整非线性动力学。通过估计来自操纵器致动器的腔室压力的接触力，避免在液压从动操纵器的尖端处使用易碎的力/扭矩传感器。在所提出的学习方法中，观察到表面滑动工具具有依赖于摩擦的方向范围（在实际运动方向和接触力之间），操纵器可以从该方向范围施加力以产生滑动运动。通过这种直觉，可以在运动上采用这些范围的交叉，以从一个或多个演示中稳健地找到所需的运动方向。通过假设所需方向之外的所有运动都是由环境引起，表明需要合规，可以找到再现运动所需的顺应轴。最后，将学习方法结合到基于VDC的新型阻抗控制方法中，以学习来自远程操作的人类演示的顺应行为。使用具有475kg有效载荷的2-DOF液压机械手进行的实验证明了所提出的方法对于使用重型液压操纵器进行演示（LfD）学习的适用性和有效性。

##### URL
[http://arxiv.org/abs/1809.00376](http://arxiv.org/abs/1809.00376)

##### PDF
[http://arxiv.org/pdf/1809.00376](http://arxiv.org/pdf/1809.00376)

