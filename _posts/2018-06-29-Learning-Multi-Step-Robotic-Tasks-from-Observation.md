---
layout: post
title: "Learning Multi-Step Robotic Tasks from Observation"
date: 2018-06-29 01:11:56
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning
author: Wonjoon Goo, Scott Niekum
mathjax: true
---

* content
{:toc}

##### Abstract
Due to burdensome data requirements, learning from demonstration often falls short of its promise to allow users to quickly and naturally program robots. Demonstrations are inherently ambiguous and incomplete, making a correct generalization to unseen situations difficult without a large number of demonstrations in varying conditions. By contrast, humans are often able to learn complex tasks from a single demonstration (typically observations without action labels) by leveraging context learned over a lifetime. Inspired by this capability, we aim to enable robots to perform one-shot learning of multi-step tasks from observation by leveraging auxiliary video data as context. Our primary contribution is a novel action localization algorithm that identifies clips of activities in auxiliary videos that match the activities in a user-segmented demonstration, providing additional examples of each. While this auxiliary video data could be used in multiple ways for learning, we focus on an inverse reinforcement learning setting. We empirically show that across several tasks, robots can learn multi-step tasks more effectively from videos with localized actions, compared to unsegmented videos.

##### Abstract (translated by Google)
由于数据需求繁重，从示范学习经常没有达到允许用户快速自然地编程机器人的承诺。示威本质上是含糊不清和不完整的，如果没有在各种条件下进行大量示威，就会对难以理解的情况做出正确的概括。相比之下，人类通常能够通过利用一生中学到的背景，从单一演示（通常是没有动作标签的观察）中学习复杂的任务。受此启发，我们旨在通过利用辅助视频数据作为背景，使机器人能够从观察中对多步骤任务进行一次性学习。我们的主要贡献是一种新颖的动作定位算法，可识别与用户分段演示中的活动相匹配的辅助视频中的活动剪辑，并提供每个演示的附加示例。虽然这种辅助视频数据可以多种方式用于学习，但我们专注于反强化学习设置。我们凭经验证明，与未分段的视频相比，在多个任务中，机器人可以从具有本地化操作的视频中更有效地学习多步任务。

##### URL
[http://arxiv.org/abs/1806.11244](http://arxiv.org/abs/1806.11244)

##### PDF
[http://arxiv.org/pdf/1806.11244](http://arxiv.org/pdf/1806.11244)

