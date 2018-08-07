---
layout: post
title: "Liquid Pouring Monitoring via Rich Sensory Inputs"
date: 2018-08-06 03:59:00
categories: arXiv_CV
tags: arXiv_CV Adversarial RNN
author: Tz-Ying Wu, Juan-Ting Lin, Tsun-Hsuang Wang, Chan-Wei Hu, Juan Carlos Niebles, Min Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Humans have the amazing ability to perform very subtle manipulation task using a closed-loop control system with imprecise mechanics (i.e., our body parts) but rich sensory information (e.g., vision, tactile, etc.). In the closed-loop system, the ability to monitor the state of the task via rich sensory information is important but often less studied. In this work, we take liquid pouring as a concrete example and aim at learning to continuously monitor whether liquid pouring is successful (e.g., no spilling) or not via rich sensory inputs. We mimic humans' rich sensories using synchronized observation from a chest-mounted camera and a wrist-mounted IMU sensor. Given many success and failure demonstrations of liquid pouring, we train a hierarchical LSTM with late fusion for monitoring. To improve the robustness of the system, we propose two auxiliary tasks during training: inferring (1) the initial state of containers and (2) forecasting the one-step future 3D trajectory of the hand with an adversarial training procedure. These tasks encourage our method to learn representation sensitive to container states and how objects are manipulated in 3D. With these novel components, our method achieves ~8% and ~11% better monitoring accuracy than the baseline method without auxiliary tasks on unseen containers and unseen users respectively.

##### Abstract (translated by Google)
人类具有使用具有不精确的力学（即，我们的身体部位）但具有丰富的感觉信息（例如，视觉，触觉等）的闭环控制系统来执行非常微妙的操纵任务的惊人能力。在闭环系统中，通过丰富的感官信息监控任务状态的能力很重要，但往往研究较少。在这项工作中，我们采用液体浇注作为一个具体的例子，旨在学习通过丰富的感官输入连续监测液体浇注是否成功（例如，没有溢出）。我们使用胸部安装的摄像头和安装在腕上的IMU传感器进行同步观察，模仿人类丰富的感官。鉴于液体浇注的许多成功和失败示范，我们培训了一个分层LSTM，后期融合监测。为了提高系统的稳健性，我们在训练期间提出了两个辅助任务：推断（1）容器的初始状态和（2）用对抗训练程序预测手的一步未来3D轨迹。这些任务鼓励我们的方法学习对容器状态敏感的表示以及如何在3D中操纵对象。使用这些新颖的组件，我们的方法比没有辅助任务的基线方法分别在看不见的容器和看不见的用户上实现了大约8％和大约11％的监视精度。

##### URL
[https://arxiv.org/abs/1808.01725](https://arxiv.org/abs/1808.01725)

##### PDF
[https://arxiv.org/pdf/1808.01725](https://arxiv.org/pdf/1808.01725)

