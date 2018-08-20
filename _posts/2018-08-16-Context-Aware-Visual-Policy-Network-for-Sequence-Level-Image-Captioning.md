---
layout: post
title: "Context-Aware Visual Policy Network for Sequence-Level Image Captioning"
date: 2018-08-16 11:45:45
categories: arXiv_CV
tags: arXiv_CV Image_Caption Attention Reinforcement_Learning Caption Prediction Relation
author: Daqing Liu, Zheng-Jun Zha, Hanwang Zhang, Yongdong Zhang, Feng Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Many vision-language tasks can be reduced to the problem of sequence prediction for natural language output. In particular, recent advances in image captioning use deep reinforcement learning (RL) to alleviate the "exposure bias" during training: ground-truth subsequence is exposed in every step prediction, which introduces bias in test when only predicted subsequence is seen. However, existing RL-based image captioning methods only focus on the language policy while not the visual policy (e.g., visual attention), and thus fail to capture the visual context that are crucial for compositional reasoning such as visual relationships (e.g., "man riding horse") and comparisons (e.g., "smaller cat"). To fill the gap, we propose a Context-Aware Visual Policy network (CAVP) for sequence-level image captioning. At every time step, CAVP explicitly accounts for the previous visual attentions as the context, and then decides whether the context is helpful for the current word generation given the current visual attention. Compared against traditional visual attention that only fixes a single image region at every step, CAVP can attend to complex visual compositions over time. The whole image captioning model --- CAVP and its subsequent language policy network --- can be efficiently optimized end-to-end by using an actor-critic policy gradient method with respect to any caption evaluation metric. We demonstrate the effectiveness of CAVP by state-of-the-art performances on MS-COCO offline split and online server, using various metrics and sensible visualizations of qualitative visual context. The code is available at https://github.com/daqingliu/CAVP

##### Abstract (translated by Google)
许多视觉语言任务可以简化为自然语言输出的序列预测问题。特别是，图像字幕的最新进展使用深度强化学习（RL）来减轻训练期间的“暴露偏差”：在每个步骤预测中暴露地面真实子序列，这在仅看到预测的子序列时在测试中引入偏差。然而，现有的基于RL的图像字幕方法仅关注语言策略而不关注视觉策略（例如，视觉注意），因此无法捕获对于诸如视觉关系之类的组合推理至关重要的视觉上下文（例如，“man”骑马“）和比较（例如，”小猫“）。为填补这一空白，我们提出了一个用于序列级图像字幕的上下文感知可视策略网络（CAVP）。在每个时间步，CAVP明确地将先前的视觉注意力作为上下文考虑，然后在给定当前视觉注意的情况下确定上下文是否对当前词生成有帮助。与仅在每一步都修复单个图像区域的传统视觉注意相比，CAVP可以随着时间的推移处理复杂的视觉合成。整个图像字幕模型--- CAVP及其后续的语言策略网络---可以通过使用关于任何字幕评估度量的演员 - 评论者策略梯度方法进行端到端的有效优化。我们通过MS-COCO离线分离和在线服务器上的最先进性能，使用各种度量和定性视觉上下文的合理可视化来证明CAVP的有效性。该代码可在https://github.com/daqingliu/CAVP获得

##### URL
[http://arxiv.org/abs/1808.05864](http://arxiv.org/abs/1808.05864)

##### PDF
[http://arxiv.org/pdf/1808.05864](http://arxiv.org/pdf/1808.05864)

