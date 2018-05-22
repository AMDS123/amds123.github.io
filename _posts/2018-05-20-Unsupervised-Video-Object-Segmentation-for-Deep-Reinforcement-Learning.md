---
layout: post
title: "Unsupervised Video Object Segmentation for Deep Reinforcement Learning"
date: 2018-05-20 15:45:03
categories: arXiv_AI
tags: arXiv_AI Segmentation Reinforcement_Learning Detection
author: Vik Goel, Jameson Weng, Pascal Poupart
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new technique for deep reinforcement learning that automatically detects moving objects and uses the relevant information for action selection. The detection of moving objects is done in an unsupervised way by exploiting structure from motion. Instead of directly learning a policy from raw images, the agent first learns to detect and segment moving objects by exploiting flow information in video sequences. The learned representation is then used to focus the policy of the agent on the moving objects. Over time, the agent identifies which objects are critical for decision making and gradually builds a policy based on relevant moving objects. This approach, which we call Motion-Oriented REinforcement Learning (MOREL), is demonstrated on a suite of Atari games where the ability to detect moving objects reduces the amount of interaction needed with the environment to obtain a good policy. Furthermore, the resulting policy is more interpretable than policies that directly map images to actions or values with a black box neural network. We can gain insight into the policy by inspecting the segmentation and motion of each object detected by the agent. This allows practitioners to confirm whether a policy is making decisions based on sensible information.

##### Abstract (translated by Google)
我们提出了一种深度强化学习的新技术，可以自动检测移动物体并使用相关信息进行动作选择。移动物体的检测是通过利用运动结构以无监督的方式完成的。代理不是直接从原始图像学习策略，而是首先学习通过利用视频序列中的流信息来检测和分割移动对象。学习的表示然后用于将代理的策略集中在移动对象上。随着时间的推移，代理人将识别哪些对象对决策至关重要，并逐步建立基于相关移动对象的策略。我们称之为Motion-Oriented REinforcement Learning（MOREL）的这种方法在一套Atari游戏中得到了展示，其中检测移动物体的能力减少了与环境所需的交互量以获得良好的策略。此外，由此产生的策略比利用黑箱神经网络将图像直接映射到动作或值的策略更具可解释性。我们可以通过检查代理检测到的每个对象的分割和运动来了解该策略。这允许从业人员确认政策是否基于合理的信息做出决定。

##### URL
[https://arxiv.org/abs/1805.07780](https://arxiv.org/abs/1805.07780)

##### PDF
[https://arxiv.org/pdf/1805.07780](https://arxiv.org/pdf/1805.07780)

