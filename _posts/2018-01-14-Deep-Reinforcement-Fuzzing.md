---
layout: post
title: "Deep Reinforcement Fuzzing"
date: 2018-01-14 17:46:17
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Konstantin Böttinger, Patrice Godefroid, Rishabh Singh
mathjax: true
---

* content
{:toc}

##### Abstract
Fuzzing is the process of finding security vulnerabilities in input-processing code by repeatedly testing the code with modified inputs. In this paper, we formalize fuzzing as a reinforcement learning problem using the concept of Markov decision processes. This in turn allows us to apply state-of-the-art deep Q-learning algorithms that optimize rewards, which we define from runtime properties of the program under test. By observing the rewards caused by mutating with a specific set of actions performed on an initial program input, the fuzzing agent learns a policy that can next generate new higher-reward inputs. We have implemented this new approach, and preliminary empirical evidence shows that reinforcement fuzzing can outperform baseline random fuzzing.

##### Abstract (translated by Google)
模糊化是通过使用修改的输入重复测试代码来查找输入处理代码中的安全漏洞的过程。在本文中，我们使用马尔可夫决策过程的概念将模糊化形式化为强化学习问题。这反过来使我们能够应用最先进的深度Q学习算法来优化奖励，这是我们根据被测试程序的运行时属性定义的。通过观察由初始程序输入执行的一组特定行为而引起的变化所带来的回报，模糊代理学习一个策略，该策略可以接下来产生新的较高回报的输入。我们已经实施了这种新的方法，初步的经验证据表明，强化模糊可以超越基线随机模糊。

##### URL
[https://arxiv.org/abs/1801.04589](https://arxiv.org/abs/1801.04589)

##### PDF
[https://arxiv.org/pdf/1801.04589](https://arxiv.org/pdf/1801.04589)

