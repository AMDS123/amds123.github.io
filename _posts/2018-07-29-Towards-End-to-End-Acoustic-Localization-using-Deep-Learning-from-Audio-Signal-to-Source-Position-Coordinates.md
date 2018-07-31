---
layout: post
title: "Towards End-to-End Acoustic Localization using Deep Learning: from Audio Signal to Source Position Coordinates"
date: 2018-07-29 18:22:38
categories: arXiv_SD
tags: arXiv_SD Knowledge CNN Deep_Learning
author: Juan Manuel Vera-Diaz, Daniel Pizarro, Javier Macias-Guarasa
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel approach for indoor acoustic source localization using microphone arrays and based on a Convolutional Neural Network (CNN). The proposed solution is, to the best of our knowledge, the first published work in which the CNN is designed to directly estimate the three dimensional position of an acoustic source, using the raw audio signal as the input information avoiding the use of hand crafted audio features. Given the limited amount of available localization data, we propose in this paper a training strategy based on two steps. We first train our network using semi-synthetic data, generated from close talk speech recordings, and where we simulate the time delays and distortion suffered in the signal that propagates from the source to the array of microphones. We then fine tune this network using a small amount of real data. Our experimental results show that this strategy is able to produce networks that significantly improve existing localization methods based on \textit{SRP-PHAT} strategies. In addition, our experiments show that our CNN method exhibits better resistance against varying gender of the speaker and different window sizes compared with the other methods.

##### Abstract (translated by Google)
本文提出了一种基于卷积神经网络（CNN）的麦克风阵列室内声源定位的新方法。据我们所知，所提出的解决方案是首次发布的工作，其中CNN被设计为直接估计声源的三维位置，使用原始音频信号作为输入信息，避免使用手工制作的音频特征。鉴于可用的本地化数据量有限，我们在本文中提出了基于两个步骤的培训策略。我们首先使用半合成数据训练我们的网络，这些数据是通过密切语音记录产生的，我们模拟从信号源传播到麦克风阵列的信号所遭受的时间延迟和失真。然后，我们使用少量实际数据对该网络进行微调。我们的实验结果表明，该策略能够生成基于\ textit {SRP-PHAT}策略显着改进现有定位方法的网络。此外，我们的实验表明，与其他方法相比，我们的CNN方法对扬声器的不同性别和不同的窗口尺寸表现出更好的抵抗力。

##### URL
[http://arxiv.org/abs/1807.11094](http://arxiv.org/abs/1807.11094)

##### PDF
[http://arxiv.org/pdf/1807.11094](http://arxiv.org/pdf/1807.11094)

