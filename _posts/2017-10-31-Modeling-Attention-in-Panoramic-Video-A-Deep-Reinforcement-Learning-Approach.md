---
layout: post
title: "Modeling Attention in Panoramic Video: A Deep Reinforcement Learning Approach"
date: 2017-10-31 09:39:17
categories: arXiv_CV
tags: arXiv_CV Attention Reinforcement_Learning Prediction
author: Yuhang Song, Mai Xu, Minglang Qiao, Jianyi Wang, Liangyu Huo, Zulin Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Panoramic video provides immersive and interactive experience by enabling humans to control the field of view (FoV) through head movement (HM). Thus, HM plays a key role in modeling human attention on panoramic video. This paper establishes a database collecting subjects' HM positions on panoramic video sequences. From this database, we find that the HM data are highly consistent across subjects. Furthermore, we find that deep reinforcement learning (DRL) can be applied to predict HM positions, via maximizing the reward of imitating human HM scanpaths through the agent's actions. Based on our findings, we propose a DRL based HM prediction (DHP) approach with offline and online versions, called offline-DHP and online-DHP. In offline-DHP, multiple DRL workflows are run to determine potential HM positions at each panoramic frame. Then, a heat map of the potential HM positions, named the HM map, is generated as the output of offline-DHP. In online-DHP, the next HM position of one subject is estimated given the currently observed HM position, which is achieved by developing a DRL algorithm upon the learned offline-DHP model. Finally, the experimental results validate that our approach is effective in offline and online prediction of HM positions for panoramic video, and that the learned offline-DHP model can improve the performance of online-DHP.

##### Abstract (translated by Google)
全景视频提供身临其境的互动体验，使人类能够通过头部移动（HM）控制视野（FoV）。因此，HM在全景视频建模方面扮演着重要的角色。本文建立了一个收集全景视频序列中被摄体HM位置的数据库。从这个数据库中，我们发现HM数据在各个科目间高度一致。此外，我们发现深度强化学习（DRL）可以用于预测HM位置，通过最大化模仿人类HM扫描路径通过代理行为的奖励。基于我们的研究结果，我们提出了一种基于DRL的HM预测（DHP）方法，具有离线和在线版本，称为离线DHP和在线DHP。在离线DHP中，运行多个DRL工作流程以确定每个全景帧的潜在HM位置。然后，生成称为HM映射的潜在HM位置的热图作为离线DHP的输出。在在线DHP中，根据当前观测到的HM位置估计一个主题的下一个HM位置，这是通过在学习的离线DHP模型上开发DRL算法来实现的。最后，实验结果验证了我们的方法在离线和在线预测全景视频的HM位置方面是有效的，学习的离线DHP模型可以提高在线DHP的性能。

##### URL
[https://arxiv.org/abs/1710.10755](https://arxiv.org/abs/1710.10755)

##### PDF
[https://arxiv.org/pdf/1710.10755](https://arxiv.org/pdf/1710.10755)

