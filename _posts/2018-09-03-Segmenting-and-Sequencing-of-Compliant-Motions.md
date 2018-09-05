---
layout: post
title: "Segmenting and Sequencing of Compliant Motions"
date: 2018-09-03 18:35:56
categories: arXiv_RO
tags: arXiv_RO
author: Tesfamichael Marikos Hagos, Markku Suomalainen, Ville Kyrki
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes an approach for segmenting a task consisting of compliant motions into phases, learning a primitive for each segmented phase of the task, and reproducing the task by sequencing primitives online based on the learned model. As compliant motions can "probe" the environment, using the interaction between the robot and the environment to detect phase transitions can make the transitions less prone to positional errors. This intuition leads us to model a task with a non-homogeneous Hidden Markov Model (HMM), wherein hidden phase transition probabilities depend on the interaction with the environment (wrench measured by an F/T sensor). Expectation-maximization algorithm is employed in estimating the parameters of the HMM model. During reproduction, the phase changes of a task are detected online using the forward algorithm, with the parameters learned from demonstrations. Cartesian impedance controller parameters are learned from the demonstrations to reproduce each phase of the task. The proposed approach is studied with a KUKA LWR4+ arm in two setups. Experiments show that the method can successfully segment and reproduce a task consisting of compliant motions with one or more demonstrations, even when demonstrations do not have the same starting position and external forces occur from different directions. Finally, we demonstrate that the method can also handle rotational motions.

##### Abstract (translated by Google)
本文提出了一种方法，用于将包括顺应运动的任务分段为阶段，为任务的每个分段阶段学习原语，以及通过基于所学习的模型在线对原语进行排序来再现任务。由于顺应运动可以“探测”环境，使用机器人和环境之间的相互作用来检测相变可以使转换不易发生位置误差。这种直觉使我们用非均匀隐马尔可夫模型（HMM）对任务进行建模，其中隐藏的相变概率取决于与环境的相互作用（由F / T传感器测量的扳手）。期望最大化算法用于估计HMM模型的参数。在再现期间，使用前向算法在线检测任务的相位变化，并从演示中学习参数。从演示中学习笛卡尔阻抗控制器参数以再现任务的每个阶段。在两种设置中使用KUKA LWR4 +臂研究了所提出的方法。实验表明，该方法可以成功地分割和再现由具有一个或多个演示的柔顺运动组成的任务，即使演示不具有相同的起始位置并且外力从不同方向发生。最后，我们证明该方法还可以处理旋转运动。

##### URL
[http://arxiv.org/abs/1809.00686](http://arxiv.org/abs/1809.00686)

##### PDF
[http://arxiv.org/pdf/1809.00686](http://arxiv.org/pdf/1809.00686)

