---
layout: post
title: "Reward Learning from Narrated Demonstrations"
date: 2018-04-27 21:26:08
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Hsiao-Yu Fish Tung, Adam W. Harley, Liang-Kang Huang, Katerina Fragkiadaki
mathjax: true
---

* content
{:toc}

##### Abstract
Humans effortlessly "program" one another by communicating goals and desires in natural language. In contrast, humans program robotic behaviours by indicating desired object locations and poses to be achieved, by providing RGB images of goal configurations, or supplying a demonstration to be imitated. None of these methods generalize across environment variations, and they convey the goal in awkward technical terms. This work proposes joint learning of natural language grounding and instructable behavioural policies reinforced by perceptual detectors of natural language expressions, grounded to the sensory inputs of the robotic agent. Our supervision is narrated visual demonstrations(NVD), which are visual demonstrations paired with verbal narration (as opposed to being silent). We introduce a dataset of NVD where teachers perform activities while describing them in detail. We map the teachers' descriptions to perceptual reward detectors, and use them to train corresponding behavioural policies in simulation.We empirically show that our instructable agents (i) learn visual reward detectors using a small number of examples by exploiting hard negative mined configurations from demonstration dynamics, (ii) develop pick-and place policies using learned visual reward detectors, (iii) benefit from object-factorized state representations that mimic the syntactic structure of natural language goal expressions, and (iv) can execute behaviours that involve novel objects in novel locations at test time, instructed by natural language.

##### Abstract (translated by Google)
人类通过以自然语言传达目标和欲望，毫不费力地“编程”彼此。相比之下，人类通过指示期望的物体位置和姿势来实现机器人行为，通过提供目标配置的RGB图像或者提供示范来模仿。这些方法都没有概括出各种环境变化，并且它们以尴尬的技术术语表达了目标。这项工作提出联合学习自然语言基础和指导性行为政策，这些政策基于自然语言表达的感知检测器，并基于机器人代理的感官输入。我们的监督是叙述视觉示范（NVD），这些视觉示范与口头叙述（而不是沉默）相配合。我们介绍一个NVD数据集，教师在进行活动的同时详细描述它们。我们将教师的描述映射到感知奖励检测器，并用它们来训练模拟中的相应行为策略。我们凭经验证明，我们的指导性代理人（i）通过利用示范中的硬性负面配置配置，通过少量例子学习视觉奖励检测器动态性，（ii）使用学习的视觉奖励探测器制定挑选和放置策略，（iii）受益于模仿自然语言目标表达式的语法结构的对象因子化状态表示，以及（iv）可以执行涉及新颖对象的行为在自然语言指导下的测试时间新地点。

##### URL
[https://arxiv.org/abs/1804.10692](https://arxiv.org/abs/1804.10692)

##### PDF
[https://arxiv.org/pdf/1804.10692](https://arxiv.org/pdf/1804.10692)

