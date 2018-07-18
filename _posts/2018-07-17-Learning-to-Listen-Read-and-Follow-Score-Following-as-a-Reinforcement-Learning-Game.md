---
layout: post
title: "Learning to Listen, Read, and Follow: Score Following as a Reinforcement Learning Game"
date: 2018-07-17 12:49:18
categories: arXiv_AI
tags: arXiv_AI Tracking Reinforcement_Learning
author: Matthias Dorfer, Florian Henkel, Gerhard Widmer
mathjax: true
---

* content
{:toc}

##### Abstract
Score following is the process of tracking a musical performance (audio) with respect to a known symbolic representation (a score). We start this paper by formulating score following as a multimodal Markov Decision Process, the mathematical foundation for sequential decision making. Given this formal definition, we address the score following task with state-of-the-art deep reinforcement learning (RL) algorithms such as synchronous advantage actor critic (A2C). In particular, we design multimodal RL agents that simultaneously learn to listen to music, read the scores from images of sheet music, and follow the audio along in the sheet, in an end-to-end fashion. All this behavior is learned entirely from scratch, based on a weak and potentially delayed reward signal that indicates to the agent how close it is to the correct position in the score. Besides discussing the theoretical advantages of this learning paradigm, we show in experiments that it is in fact superior compared to previously proposed methods for score following in raw sheet music images.

##### Abstract (translated by Google)
分数跟随是关于已知符号表示（分数）跟踪音乐表现（音频）的过程。我们通过将得分跟随公式作为多模态马尔可夫决策过程来开始本文，这是顺序决策的数学基础。鉴于这种正式的定义，我们使用最先进的深度强化学习（RL）算法（如同步优势演员评论家（A2C））来解决任务后的得分。特别是，我们设计了多模式RL代理，它们同时学习听音乐，从乐谱图像中读取乐谱，并以端到端的方式跟随乐谱。所有这些行为都是从头开始学习的，基于一个微弱且可能延迟的奖励信号，该信号向代理人指示它与分数中的正确位置有多接近。除了讨论这种学习范式的理论优势之外，我们在实验中表明，与之前提出的原始乐谱图像中得分跟踪方法相比，它实际上更优越。

##### URL
[http://arxiv.org/abs/1807.06391](http://arxiv.org/abs/1807.06391)

##### PDF
[http://arxiv.org/pdf/1807.06391](http://arxiv.org/pdf/1807.06391)

