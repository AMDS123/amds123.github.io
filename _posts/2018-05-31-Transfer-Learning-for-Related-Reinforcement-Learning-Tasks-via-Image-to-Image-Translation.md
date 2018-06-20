---
layout: post
title: "Transfer Learning for Related Reinforcement Learning Tasks via Image-to-Image Translation"
date: 2018-05-31 09:25:29
categories: arXiv_AI
tags: arXiv_AI Adversarial Knowledge GAN Reinforcement_Learning Transfer_Learning
author: Shani Gamrian, Yoav Goldberg
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Reinforcement Learning has managed to achieve state-of-the-art results in learning control policies directly from raw pixels. However, despite its remarkable success, it fails to generalize, a fundamental component required in a stable Artificial Intelligence system. Using the Atari game Breakout, we demonstrate the difficulty of a trained agent in adjusting to simple modifications in the raw image, ones that a human could adapt to trivially. In transfer learning, the goal is to use the knowledge gained from the source task to make the training of the target task faster and better. We show that using various forms of fine-tuning, a common method for transfer learning, is not effective for adapting to such small visual changes. In fact, it is often easier to re-train the agent from scratch than to fine-tune a trained agent. We suggest that in some cases transfer learning can be improved by adding a dedicated component whose goal is to learn to visually map between the known domain and the new one. Concretely, we use Generative Adversarial Networks (GANs) to create a mapping function to translate images in the target task to corresponding images in the source task, allowing us to transform between the different tasks. We show that learning this mapping is substantially more efficient than re-training.

##### Abstract (translated by Google)
Deep Reinforcement Learning已经成功实现了直接从原始像素学习控制策略的最新成果。然而，尽管它取得了显着的成功，但它没有概括出一个稳定的人工智能系统所需的基本组件。使用Atari游戏突破，我们证明了训练有素的代理人在调整原始图像中的简单修改方面的困难，这是人类可以轻易适应的。在转移学习中，目标是利用源任务获得的知识更快更好地完成目标任务的训练。我们表明，使用各种形式的微调，一种常用的转移学习方法，对于适应这种小的视觉变化无效。事实上，从头开始重新训练代理人比调整训练有素的代理人要容易得多。我们建议在某些情况下，转移学习可以通过添加一个专门的组件来改进，其目标是学习在已知域和新域之间进行可视化映射。具体来说，我们使用生成敌对​​网络（GAN）来创建一个映射函数，将目标任务中的图像转换为源任务中的相应图像，从而允许我们在不同任务之间进行转换。我们表明，学习这种映射比再培训更有效。

##### URL
[http://arxiv.org/abs/1806.07377](http://arxiv.org/abs/1806.07377)

##### PDF
[http://arxiv.org/pdf/1806.07377](http://arxiv.org/pdf/1806.07377)

