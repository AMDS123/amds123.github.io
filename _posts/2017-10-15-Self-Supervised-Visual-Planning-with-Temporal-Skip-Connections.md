---
layout: post
title: "Self-Supervised Visual Planning with Temporal Skip Connections"
date: 2017-10-15 02:58:20
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Frederik Ebert, Chelsea Finn, Alex X. Lee, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
In order to autonomously learn wide repertoires of complex skills, robots must be able to learn from their own autonomously collected data, without human supervision. One learning signal that is always available for autonomously collected data is prediction: if a robot can learn to predict the future, it can use this predictive model to take actions to produce desired outcomes, such as moving an object to a particular location. However, in complex open-world scenarios, designing a representation for prediction is difficult. In this work, we instead aim to enable self-supervised robotic learning through direct video prediction: instead of attempting to design a good representation, we directly predict what the robot will see next, and then use this model to achieve desired goals. A key challenge in video prediction for robotic manipulation is handling complex spatial arrangements such as occlusions. To that end, we introduce a video prediction model that can keep track of objects through occlusion by incorporating temporal skip-connections. Together with a novel planning criterion and action space formulation, we demonstrate that this model substantially outperforms prior work on video prediction-based control. Our results show manipulation of objects not seen during training, handling multiple objects, and pushing objects around obstructions. These results represent a significant advance in the range and complexity of skills that can be performed entirely with self-supervised robotic learning.

##### Abstract (translated by Google)
为了自主学习复杂技能的丰富曲目，机器人必须能够从自己收集的数据中学习，而不需要人工监督。一个始终可用于自主收集的数据的学习信号是预测：如果机器人可以学习预测未来，则可以使用该预测模型来采取行动来产生期望的结果，例如将对象移动到特定位置。但是，在复杂的开放世界情景中，设计预测的表示是困难的。在这项工作中，我们的目标是通过直接视频预测实现自我监督的机器人学习：我们不直接设计一个好的表示，而是直接预测机器人接下来会看到什么，然后使用这个模型实现预期的目标。机器人操纵的视频预测中的关键挑战是处理诸如遮挡的复杂空间布置。为此，我们引入了一个视频预测模型，通过结合时间跳跃连接，可以通过遮挡来跟踪对象。再加上一个新的规划标准和行动空间的制定，我们证明这个模型大大优于以往的视频预测控制工作。我们的结果显示在训练期间看不见的物体的操纵，处理多个物体，以及推动障碍物周围的物体。这些结果代表了可以完全通过自我监督的机器人学习完成的技能范围和复杂性方面的重大进步。

##### URL
[https://arxiv.org/abs/1710.05268](https://arxiv.org/abs/1710.05268)

##### PDF
[https://arxiv.org/pdf/1710.05268](https://arxiv.org/pdf/1710.05268)

