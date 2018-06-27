---
layout: post
title: "Adversarial Exploration Strategy for Self-Supervised Imitation Learning"
date: 2018-06-26 14:33:22
categories: arXiv_AI
tags: arXiv_AI Adversarial Reinforcement_Learning
author: Zhang-Wei Hong, Tsu-Jui Fu, Tzu-Yun Shann, Yi-Hsiang Chang, Chun-Yi Lee
mathjax: true
---

* content
{:toc}

##### Abstract
We present an adversarial exploration strategy, a simple yet effective imitation learning scheme that incentivizes exploration of an environment without any extrinsic reward or human demonstration. Our framework consists of a deep reinforcement learning (DRL) agent and an inverse dynamics model contesting with each other. The former collects training samples for the latter, and its objective is to maximize the error of the latter. The latter is trained with samples collected by the former, and generates rewards for the former when it fails to predict the actual action taken by the former. In such a competitive setting, the DRL agent learns to generate samples that the inverse dynamics model fails to predict correctly, and the inverse dynamics model learns to adapt to the challenging samples. We further propose a reward structure that ensures the DRL agent collects only moderately hard samples and not overly hard ones that prevent the inverse model from imitating effectively. We evaluate the effectiveness of our method on several OpenAI gym robotic arm and hand manipulation tasks against a number of baseline models. Experimental results show that our method is comparable to that directly trained with expert demonstrations, and superior to the other baselines even without any human priors.

##### Abstract (translated by Google)
我们提出了一种对抗性的探索策略，一种简单而有效的模仿学习方案，该方案可以激励对环境的探索，而无需任何外部奖励或人类示范。我们的框架由一个深度强化学习（DRL）代理和一个互相竞争的逆动力学模型组成。前者为后者收集训练样本，其目标是最大化后者的误差。后者通过前者收集的样本进行训练，当前者未能预测前者采取的实际行动时，前者会获得奖励。在这样的竞争环境中，DRL代理学习生成逆动力学模型无法正确预测的样本，而逆动力学模型学习适应具有挑战性的样本。我们进一步提出了一种奖励结构，以确保DRL代理只收集中等硬度的样本，而不是过硬的样本，以防止反向模型有效地模仿。我们评估了我们的方法在几种OpenAI体操机器人手臂和手操作任务中对多种基准模型的有效性。实验结果表明，我们的方法与直接受专业演示培训的方法相媲美，甚至在没有任何人为先验的情况下优于其他基线。

##### URL
[http://arxiv.org/abs/1806.10019](http://arxiv.org/abs/1806.10019)

##### PDF
[http://arxiv.org/pdf/1806.10019](http://arxiv.org/pdf/1806.10019)

