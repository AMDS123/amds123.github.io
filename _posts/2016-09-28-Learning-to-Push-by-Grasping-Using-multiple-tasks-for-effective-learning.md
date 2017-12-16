---
layout: post
title: "Learning to Push by Grasping: Using multiple tasks for effective learning"
date: 2016-09-28 18:13:02
categories: arXiv_CV
tags: arXiv_CV
author: Lerrel Pinto, Abhinav Gupta
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, end-to-end learning frameworks are gaining prevalence in the field of robot control. These frameworks input states/images and directly predict the torques or the action parameters. However, these approaches are often critiqued due to their huge data requirements for learning a task. The argument of the difficulty in scalability to multiple tasks is well founded, since training these tasks often require hundreds or thousands of examples. But do end-to-end approaches need to learn a unique model for every task? Intuitively, it seems that sharing across tasks should help since all tasks require some common understanding of the environment. In this paper, we attempt to take the next step in data-driven end-to-end learning frameworks: move from the realm of task-specific models to joint learning of multiple robot tasks. In an astonishing result we show that models with multi-task learning tend to perform better than task-specific models trained with same amounts of data. For example, a deep-network learned with 2.5K grasp and 2.5K push examples performs better on grasping than a network trained on 5K grasp examples.

##### Abstract (translated by Google)
最近，端到端的学习框架在机器人控制领域越来越普遍。这些框架输入状态/图像并直接预测转矩或动作参数。然而，这些方法往往受到批评，因为他们需要大量的数据来学习任务。关于多任务可扩展性的困难的论据是有根据的，因为训练这些任务经常需要数百或数千个例子。但是，端到端方法需要为每个任务学习一个独特的模型吗？直观上看，跨任务共享应该有所帮助，因为所有任务都需要对环境有一些共同的理解。在本文中，我们试图采取数据驱动的端到端学习框架的下一步：从特定任务模型的领域转移到多个机器人任务的联合学习。令人惊讶的是，我们发现多任务学习模型往往比使用相同数据量训练的任务特定模型执行得更好。例如，一个以2.5K抓取和2.5K推例子学习的深度网络比抓住5K例子训练的网络掌握得更好。

##### URL
[https://arxiv.org/abs/1609.09025](https://arxiv.org/abs/1609.09025)

##### PDF
[https://arxiv.org/pdf/1609.09025](https://arxiv.org/pdf/1609.09025)

