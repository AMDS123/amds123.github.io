---
layout: post
title: "Barrier-Certified Adaptive Reinforcement Learning with Applications to Brushbot Navigation"
date: 2018-09-12 06:20:30
categories: arXiv_RO
tags: arXiv_RO Sparse Reinforcement_Learning Optimization
author: Motoya Ohnishi, Li Wang, Gennaro Notomista, Magnus Egerstedt
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a safe learning framework that employs an adaptive model learning method together with barrier certificates for systems with possibly nonstationary agent dynamics. To extract the dynamic structure of the model, we use a sparse optimization technique, and the resulting model will be used in combination with control barrier certificates which constrain policies (feedback controllers) in order to maintain safety, which refers to avoiding certain regions of the state space. Under certain conditions, recovery of safety in the sense of Lyapunov stability after violations of safety due to the nonstationarity is guaranteed. In addition, we reformulate action-value function approximation to make any kernel-based nonlinear function estimation method applicable to our adaptive learning framework. Lastly, solutions to the barrier-certified policy optimization are guaranteed to be globally optimal, ensuring greedy policy updates under mild conditions. The resulting framework is validated via simulations of a quadrotor, which has been used in the safe learnings literature under {\em stationarity} assumption, and then tested on a real robot called {\em brushbot}, whose dynamics is unknown, highly complex, and most probably nonstationary.

##### Abstract (translated by Google)
本文提出了一个安全的学习框架，该框架采用自适应模型学习方法和障碍证书，用于可能具有非平稳代理动态的系统。为了提取模型的动态结构，我们使用稀疏优化技术，结果模型将与控制障碍证书结合使用，这些证书约束策略（反馈控制器）以保持安全性，这是指避免某些区域的国家空间。在一定条件下，由于非平稳性而违反安全性后，Lyapunov稳定性意义上的安全性恢复得到保证。此外，我们重新设计动作 - 值函数近似，使任何基于内核的非线性函数估计方法适用于我们的自适应学习框架。最后，屏障认证政策优化的解决方案保证全球最优，确保在温和条件下贪婪的政策更新。最终的框架通过模拟四旋翼进行验证，该模拟已经在{\ em stationarity}假设下的安全学习文献中使用，然后在名为{\ em brushbot}的真实机器人上进行测试，其动力学未知，高度复杂，而且很可能是非平稳的。

##### URL
[http://arxiv.org/abs/1801.09627](http://arxiv.org/abs/1801.09627)

##### PDF
[http://arxiv.org/pdf/1801.09627](http://arxiv.org/pdf/1801.09627)

