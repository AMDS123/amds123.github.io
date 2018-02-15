---
layout: post
title: "A General Safety Framework for Learning-Based Control in Uncertain Robotic Systems"
date: 2018-02-14 18:14:34
categories: arXiv_RO
tags: arXiv_RO Knowledge Reinforcement_Learning
author: Jaime F. Fisac, Anayo K. Akametalu, Melanie N. Zeilinger, Shahab Kaynama, Jeremy Gillula, Claire J. Tomlin
mathjax: true
---

* content
{:toc}

##### Abstract
The proven efficacy of learning-based control schemes strongly motivates their application to robotic systems operating in the physical world. However, guaranteeing correct operation during the learning process is currently an unresolved issue, which is of vital importance in safety-critical systems. We propose a general safety framework based on Hamilton-Jacobi reachability methods that can work in conjunction with an arbitrary learning algorithm. The method exploits approximate knowledge of the system dynamics to guarantee constraint satisfaction while minimally interfering with the learning process. We further introduce a Bayesian mechanism that refines the safety analysis as the system acquires new evidence, reducing initial conservativeness when appropriate while strengthening guarantees through real-time validation. The result is a least-restrictive, safety-preserving control law that intervenes only when (a) the computed safety guarantees require it, or (b) confidence in the computed guarantees decays in light of new observations. We prove theoretical safety guarantees combining probabilistic and worst-case analysis and demonstrate the proposed framework experimentally on a quadrotor vehicle. Even though safety analysis is based on a simple point-mass model, the quadrotor successfully arrives at a suitable controller by policy-gradient reinforcement learning without ever crashing, and safely retracts away from a strong external disturbance introduced during flight.

##### Abstract (translated by Google)
基于学习的控制方案的经过验证的功效强烈地推动了其在物理世界中运行的机器人系统的应用。但是，保证学习过程中的正确操作是目前尚未解决的问题，这在安全关键系统中至关重要。我们提出了一个基于Hamilton-Jacobi可达性方法的通用安全框架，可以与任意学习算法结合使用。该方法利用系统动力学的近似知识来保证约束满意度，同时最小程度地干扰学习过程。我们进一步引入贝叶斯机制，在系统获取新证据时优化安全性分析，适时降低初始保守性，同时通过实时验证加强保证。其结果是只有当（a）计算的安全保证要求它时，或（b）根据新的观察结果计算出的保证衰减的可信度，才进行干预的限制最少的安全保留控制法则。我们证明结合概率和最坏情况分析的理论安全保证，并在四旋翼飞行器上试验性地展示了所提出的框架。尽管安全分析是基于一个简单的点质量模型，但是四旋翼飞行器通过策略梯度强化学习成功地到达了一个合适的控制器，而不会崩溃，并且可以安全地从飞行过程中引入的强大外部干扰撤回。

##### URL
[http://arxiv.org/abs/1705.01292](http://arxiv.org/abs/1705.01292)

##### PDF
[http://arxiv.org/pdf/1705.01292](http://arxiv.org/pdf/1705.01292)

