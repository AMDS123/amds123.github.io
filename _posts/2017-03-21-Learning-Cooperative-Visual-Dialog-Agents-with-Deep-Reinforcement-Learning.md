---
layout: post
title: "Learning Cooperative Visual Dialog Agents with Deep Reinforcement Learning"
date: 2017-03-21 17:41:23
categories: arXiv_SD
tags: arXiv_SD Reinforcement_Learning VQA
author: Abhishek Das, Satwik Kottur, José M. F. Moura, Stefan Lee, Dhruv Batra
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce the first goal-driven training for visual question answering and dialog agents. Specifically, we pose a cooperative 'image guessing' game between two agents -- Qbot and Abot -- who communicate in natural language dialog so that Qbot can select an unseen image from a lineup of images. We use deep reinforcement learning (RL) to learn the policies of these agents end-to-end -- from pixels to multi-agent multi-round dialog to game reward. We demonstrate two experimental results. First, as a 'sanity check' demonstration of pure RL (from scratch), we show results on a synthetic world, where the agents communicate in ungrounded vocabulary, i.e., symbols with no pre-specified meanings (X, Y, Z). We find that two bots invent their own communication protocol and start using certain symbols to ask/answer about certain visual attributes (shape/color/style). Thus, we demonstrate the emergence of grounded language and communication among 'visual' dialog agents with no human supervision. Second, we conduct large-scale real-image experiments on the VisDial dataset, where we pretrain with supervised dialog data and show that the RL 'fine-tuned' agents significantly outperform SL agents. Interestingly, the RL Qbot learns to ask questions that Abot is good at, ultimately resulting in more informative dialog and a better team.

##### Abstract (translated by Google)
我们介绍了视觉问答和对话代理的第一个目标驱动培训。具体来说，我们在两个代理之间构建了一个合作的“图像猜测”游戏 -  Qbot和Abot--在自然语言对话中进行交流，这样Qbot可以从一系列图像中选择一个看不见的图像。我们使用深度强化学习（RL）来学习这些代理端对端的策略 - 从像素到多代理多轮对话到游戏奖励。我们展示了两个实验结果。首先，作为纯RL（从头开始）的“健全性检查”演示，我们在合成世界中展示结果，其中代理人以不具有预定义含义（X，Y，Z）的符号进行通信。我们发现两个机器人发明自己的通信协议，并开始使用某些符号来询问/回答某些视觉属性（形状/颜色/样式）。因此，我们展示了没有任何人力监督的“视觉”对话代理人之间的基础语言和交流的出现。其次，我们在VisDial数据集上进行了大规模的实时图像实验，在这里我们预先加入了监督对话数据，表明RL的“微调”代理显着优于SL代理。有趣的是，RL Qbot学习提出Abot擅长的问题，最终导致更多的信息对话和更好的团队。

##### URL
[https://arxiv.org/abs/1703.06585](https://arxiv.org/abs/1703.06585)

##### PDF
[https://arxiv.org/pdf/1703.06585](https://arxiv.org/pdf/1703.06585)

