---
layout: post
title: "One-Shot Learning of Multi-Step Tasks from Observation via Activity Localization in Auxiliary Video"
date: 2018-09-19 01:39:26
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning
author: Wonjoon Goo, Scott Niekum
mathjax: true
---

* content
{:toc}

##### Abstract
Due to burdensome data requirements, learning from demonstration often falls short of its promise to allow users to quickly and naturally program robots. Demonstrations are inherently ambiguous and incomplete, making correct generalization to unseen situations difficult without a large number of demonstrations in varying conditions. By contrast, humans are often able to learn complex tasks from a single demonstration (typically observations without action labels) by leveraging context learned over a lifetime. Inspired by this capability, our goal is to enable robots to perform one-shot learning of multi-step tasks from observation by leveraging auxiliary video data as context. Our primary contribution is a novel system that achieves this goal by: (1) using a single user-segmented demonstration to define the primitive actions that comprise a task, (2) localizing additional examples of these actions in unsegmented auxiliary videos via a metalearning-based approach, (3) using these additional examples to learn a reward function for each action, and (4) performing reinforcement learning on top of the inferred reward functions to learn action policies that can be combined to accomplish the task. We empirically demonstrate that a robot can learn multi-step tasks more effectively when provided auxiliary video, and that performance greatly improves when localizing individual actions, compared to learning from unsegmented videos.

##### Abstract (translated by Google)
由于繁琐的数据要求，从演示中学习往往达不到允许用户快速自然地编程机器人的承诺。示威本质上是模棱两可和不完整的，如果没有在不同条件下进行大量示威，就可以在看不见的情况下进行正确的推广。相比之下，人类通常能够通过利用一生中学到的背景，从单一演示（通常是没有动作标签的观察）中学习复杂的任务。受此功能的启发，我们的目标是通过利用辅助视频数据作为上下文，使机器人能够通过观察对多步骤任务进行一次性学习。我们的主要贡献是通过以下方式实现这一目标的新颖系统：（1）使用单个用户分段演示来定义构成任务的原始动作，（2）通过元学习在未分段的辅助视频中定位这些动作的其他示例 - 基于方法，（3）使用这些附加示例来学习每个动作的奖励函数，以及（4）在推断的奖励函数之上执行强化学习以学习可以组合以完成任务的动作策略。我们凭经验证明，机器人在提供辅助视频时可以更有效地学习多步骤任务，与从未分段视频中学习相比，在定位个人动作时性能会大大提高。

##### URL
[http://arxiv.org/abs/1806.11244](http://arxiv.org/abs/1806.11244)

##### PDF
[http://arxiv.org/pdf/1806.11244](http://arxiv.org/pdf/1806.11244)

