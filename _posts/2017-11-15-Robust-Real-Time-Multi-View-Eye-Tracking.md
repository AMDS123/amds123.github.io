---
layout: post
title: "Robust Real-Time Multi-View Eye Tracking"
date: 2017-11-15 08:23:06
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Nuri Murat Arar, Jean-Philippe Thiran
mathjax: true
---

* content
{:toc}

##### Abstract
Despite significant advances in improving the gaze estimation accuracy under controlled conditions, the tracking robustness under real-world conditions, such as large head pose and movements, use of eye glasses, illumination and eye type variations, remains a major challenge in eye tracking. In this paper, we revisit this challenge and introduce a real-time multi-camera eye tracking framework to improve the estimation robustness. First, differently from previous work, we design a multi-view tracking setup that allows for acquiring multiple eye appearances simultaneously. Leveraging multi-view appearances enables to more reliably detect gaze features under challenging conditions, particularly when they are obstructed due to large head movements and glasses effects in conventional single-view appearance. The features extracted on various appearances are then used for estimating multiple gaze outputs. Second, we propose to combine the gaze outputs through an adaptive fusion mechanism in order to compute user's overall point of regard. The proposed mechanism firstly determines the estimation reliability of each gaze output according to user's momentary head pose and general gazing behavior, and then performs a reliability-based weighted fusion. We demonstrate the efficacy of our framework with extensive simulations and user experiments on a collected dataset featuring 20 subjects. Our results show that in comparison with state-of-the-art eye trackers, the proposed framework provides not only a significant enhancement in accuracy but also a notable robustness. Our prototype system runs at 30 frames-per-second (fps) and achieves 1{\deg} accuracy under challenging experimental scenarios, which makes it suitable for various high-precision demanding applications.

##### Abstract (translated by Google)
尽管在受控条件下提高注视估计精度方面取得了重大进展，但在实际情况下（例如大头部姿态和运动，使用眼镜，照明和眼睛类型变化）的跟踪鲁棒性仍然是眼动跟踪中的主要挑战。在本文中，我们重新审视这个挑战，并引入一个实时多摄像机眼动追踪框架来提高估计的鲁棒性。首先，与以前的工作不同，我们设计了一个多视图跟踪设置，允许同时获取多个眼睛的外观。利用多视角外观，可以在困难条件下更可靠地检测凝视特征，特别是在传统的单视图外观中由于头部大的移动和眼镜效应而被阻挡时。然后使用在各种外观上提取的特征来估计多个注视输出。其次，我们建议通过自适应融合机制来结合注视输出，以计算用户的整体观点。所提出的机制首先根据用户的瞬间头部姿态和一般注视行为来确定每个注视输出的估计可靠性，然后进行基于可靠性的加权融合。我们展示了我们的框架的功效与广泛的模拟和用户实验在收集的数据集20个科目。我们的研究结果表明，与最先进的眼动仪相比，所提出的框架不仅提高了精度，而且显着的鲁棒性。我们的原型系统以每秒30帧（fps）的速度运行，并在具有挑战性的实验场景下达到1％的精度，因此适用于各种高精度要求苛刻的应用。

##### URL
[http://arxiv.org/abs/1711.05444](http://arxiv.org/abs/1711.05444)

##### PDF
[http://arxiv.org/pdf/1711.05444](http://arxiv.org/pdf/1711.05444)

