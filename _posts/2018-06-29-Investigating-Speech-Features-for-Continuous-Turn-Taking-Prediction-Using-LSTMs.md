---
layout: post
title: "Investigating Speech Features for Continuous Turn-Taking Prediction Using LSTMs"
date: 2018-06-29 15:07:17
categories: arXiv_CL
tags: arXiv_CL RNN Prediction Detection
author: Matthew Roddy, Gabriel Skantze, Naomi Harte
mathjax: true
---

* content
{:toc}

##### Abstract
For spoken dialog systems to conduct fluid conversational interactions with users, the systems must be sensitive to turn-taking cues produced by a user. Models should be designed so that effective decisions can be made as to when it is appropriate, or not, for the system to speak. Traditional end-of-turn models, where decisions are made at utterance end-points, are limited in their ability to model fast turn-switches and overlap. A more flexible approach is to model turn-taking in a continuous manner using RNNs, where the system predicts speech probability scores for discrete frames within a future window. The continuous predictions represent generalized turn-taking behaviors observed in the training data and can be applied to make decisions that are not just limited to end-of-turn detection. In this paper, we investigate optimal speech-related feature sets for making predictions at pauses and overlaps in conversation. We find that while traditional acoustic features perform well, part-of-speech features generally perform worse than word features. We show that our current models outperform previously reported baselines.

##### Abstract (translated by Google)
对于口头对话系统与用户进行流畅的对话交互，系统必须对用户产生的转向提示敏感。模型的设计应该能够在适当的时候作出有效的决定，以便系统发言。传统的转弯模型，在话语端点进行决策时，模型快速转换开关和重叠的能力有限。更灵活的方法是使用RNN以连续方式建模转弯，其中系统预测未来窗口内离散帧的语音概率分数。连续预测表示在训练数据中观察到的广义轮转行为，并且可以应用于做出不仅局限于转弯结束检测的决策。在本文中，我们调查最佳的语音相关特征集，用于在对话中暂停和重叠进行预测。我们发现虽然传统声学特征表现良好，但词性特征通常比字特征表现更差。我们表明，我们目前的模型优于以前报告的基线。

##### URL
[http://arxiv.org/abs/1806.11461](http://arxiv.org/abs/1806.11461)

##### PDF
[http://arxiv.org/pdf/1806.11461](http://arxiv.org/pdf/1806.11461)

