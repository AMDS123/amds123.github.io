---
layout: post
title: "Deep 360 Pilot: Learning a Deep Agent for Piloting through 360° Sports Video"
date: 2017-05-04 09:26:58
categories: arXiv_CV
tags: arXiv_CV Knowledge Deep_Learning
author: Hou-Ning Hu, Yen-Chen Lin, Ming-Yu Liu, Hsien-Tzu Cheng, Yung-Ju Chang, Min Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Watching a 360{\deg} sports video requires a viewer to continuously select a viewing angle, either through a sequence of mouse clicks or head movements. To relieve the viewer from this "360 piloting" task, we propose "deep 360 pilot" -- a deep learning-based agent for piloting through 360{\deg} sports videos automatically. At each frame, the agent observes a panoramic image and has the knowledge of previously selected viewing angles. The task of the agent is to shift the current viewing angle (i.e. action) to the next preferred one (i.e., goal). We propose to directly learn an online policy of the agent from data. We use the policy gradient technique to jointly train our pipeline: by minimizing (1) a regression loss measuring the distance between the selected and ground truth viewing angles, (2) a smoothness loss encouraging smooth transition in viewing angle, and (3) maximizing an expected reward of focusing on a foreground object. To evaluate our method, we build a new 360-Sports video dataset consisting of five sports domains. We train domain-specific agents and achieve the best performance on viewing angle selection accuracy and transition smoothness compared to [51] and other baselines.

##### Abstract (translated by Google)
观看360度体育视频需要观看者连续选择观看角度，无论是通过一系列鼠标点击或头部动作。为了让观众摆脱这个“360度驾驶”的任务，我们提出了“深度360度飞行员” - 一个深度的学习型代理，自动通过360度体育视频试驾。在每一帧，代理观察全景图像，并具有先前选择的视角的知识。代理的任务是将当前的视角（即动作）转移到下一个优选的角度（即目标）。我们建议直接从数据中学习代理的在线策略。我们使用策略梯度技术来联合训练我们的流水线：通过最小化（1）回归损失来测量所选和地面真实视角之间的距离，（2）平滑损失，促使视角平滑过渡，以及（3）一个专注于前景对象的预期奖励。为了评估我们的方法，我们建立了一个由五个体育领域组成的新的360-体育视频数据集。与[51]和其他基线相比，我们训练领域特定的代理，并在视角选择精度和转换平滑度方面实现最佳性能。

##### URL
[https://arxiv.org/abs/1705.01759](https://arxiv.org/abs/1705.01759)

##### PDF
[https://arxiv.org/pdf/1705.01759](https://arxiv.org/pdf/1705.01759)

