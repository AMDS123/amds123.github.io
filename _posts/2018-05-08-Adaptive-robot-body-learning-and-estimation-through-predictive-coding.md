---
layout: post
title: "Adaptive robot body learning and estimation through predictive coding"
date: 2018-05-08 15:26:22
categories: arXiv_RO
tags: arXiv_RO Prediction
author: Pablo Lanillos, Gordon Cheng
mathjax: true
---

* content
{:toc}

##### Abstract
The predictive functions that permit humans to infer their body state by sensorimotor integration are critical to deploy safe interaction in complex environments. These functions are adaptive and robust to non-linear actuators and noisy sensory information. This paper presents a powerful and scalable computational perceptual model based on predictive processing that enables any multisensory robot to learn, infer and update its body configuration when using arbitrary sensors with Gaussian additive noise. The proposed method integrates different sources of information (tactile, visual and proprioceptive) to drive the robot belief to its current body configuration. The motivation is to enable robots with the embodied perception needed for self-calibration and safe physical human-robot interaction. 
 We formulate body learning obtaining the function that encodes the sensory consequences of the body configuration and its partial derivative with respect to body variables, and we solve it by Gaussian process regression. We model body estimation as minimizing the discrepancy between the robot body configuration belief and the observed posterior. We minimize the variational free energy using the sensory prediction errors (sensed vs expected). 
 In order to evaluate the model we test it on a real multisensory robotic arm. We show how different sensor modalities contributions, included as additive errors, improve the refinement of the body estimation and how the system adapts itself to provide the most plausible solution even when injecting strong sensory visuo-tactile perturbations. We further analyse the reliability of the model when different sensor modalities are disabled. This provides grounded evidence about the correctness of the perceptual model and shows how the robot estimates and adjusts its body configuration just by means of sensory information.

##### Abstract (translated by Google)
预测功能允许人类通过感觉运动集成来推断他们的身体状态，这对于在复杂环境中部署安全交互非常重要。这些功能对非线性执行器和嘈杂的传感信息具有自适应性和鲁棒性。本文提出了一种基于预测处理的强大且可扩展的计算感知模型，使任何多感官机器人能够在使用具有高斯加性噪声的任意传感器时学习，推断和更新其身体配置。所提出的方法集成了不同的信息来源（触觉，视觉和本体感受），以将机器人的信念驱动到其当前的身体配置。其动机是使机器人具有自我校准和安全的物理人机交互所需的体现感知。
 我们制定身体学习，获得编码身体构型的感觉结果及其偏差对身体变量的函数，并且我们通过高斯过程回归来解决它。我们将身体估计模型化为最小化机器人身体配置信念与观察后验之间的差异。我们使用感官预测误差（感觉vs预期）使变分自由能最小化。
 为了评估模型，我们在真正的多感官机器人手臂上测试它。我们展示了不同的传感器模态贡献（包括作为附加误差）如何改善身体估计的细化以及系统如何适应自身，即使在注入强感觉的视觉触觉干扰时也能提供最合理的解决方案。当不同的传感器模式被禁用时，我们进一步分析模型的可靠性。这提供了有关感知模型正确性的基础证据，并显示了机器人如何通过感官信息来估计和调整其身体构型。

##### URL
[http://arxiv.org/abs/1805.03104](http://arxiv.org/abs/1805.03104)

##### PDF
[http://arxiv.org/pdf/1805.03104](http://arxiv.org/pdf/1805.03104)

