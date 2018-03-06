---
layout: post
title: "Less Is More: Picking Informative Frames for Video Captioning"
date: 2018-03-05 01:57:49
categories: arXiv_CV
tags: arXiv_CV Salient Video_Caption Attention Caption
author: Yangyu Chen, Shuhui Wang, Weigang Zhang, Qingming Huang
mathjax: true
---

* content
{:toc}

##### Abstract
In video captioning task, the best practice has been achieved by attention-based models which associate salient visual components with sentences in the video. However, existing study follows a common procedure which includes a frame-level appearance modeling and motion modeling on equal interval frame sampling, which may bring about redundant visual information, sensitivity to content noise and unnecessary computation cost. 
 We propose a plug-and-play PickNet to perform informative frame picking in video captioning. Based on a standard Encoder-Decoder framework, we develop a reinforcement-learning-based procedure to train the network sequentially, where the reward of each frame picking action is designed by maximizing visual diversity and minimizing textual discrepancy. If the candidate is rewarded, it will be selected and the corresponding latent representation of Encoder-Decoder will be updated for future trials. This procedure goes on until the end of the video sequence. Consequently, a compact frame subset can be selected to represent the visual information and perform video captioning without performance degradation. Experiment results shows that our model can use 6-8 frames to achieve competitive performance across popular benchmarks.

##### Abstract (translated by Google)
在视频字幕任务中，最佳实践已通过基于注意力的模型实现，该模型将视频中突出的视觉组件与句子相关联。然而，现有的研究遵循一个通用的程序，其包括在等间隔帧采样上的帧级外观建模和运动建模，这可能导致冗余的视觉信息，对内容噪声的敏感性和不必要的计算成本。
 我们建议即插即用PickNet在视频字幕中执行信息帧采摘。基于标准的编码器 - 解码器框架，我们开发了一个基于强化学习的过程来依次训练网络，每帧挑选动作的奖励是通过最大化视觉多样性和最小化文本差异来设计的。如果候选人被奖励，它将被选择并且编码器 - 解码器的相应潜在表示将被更新以用于将来的试验。此过程持续进行直到视频序列结束。因此，可以选择紧凑的帧子集来表示视觉信息并执行视频字幕而不会降低性能。实验结果表明，我们的模型可以使用6-8帧来在各种流行的基准测试中实现竞争性能。

##### URL
[http://arxiv.org/abs/1803.01457](http://arxiv.org/abs/1803.01457)

##### PDF
[http://arxiv.org/pdf/1803.01457](http://arxiv.org/pdf/1803.01457)

