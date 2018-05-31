---
layout: post
title: "Deep Video Portraits"
date: 2018-05-29 21:31:14
categories: arXiv_AI
tags: arXiv_AI Adversarial Face
author: Hyeongwoo Kim, Pablo Garrido, Ayush Tewari, Weipeng Xu, Justus Thies, Matthias Nießner, Patrick Pérez, Christian Richardt, Michael Zollhöfer, Christian Theobalt
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel approach that enables photo-realistic re-animation of portrait videos using only an input video. In contrast to existing approaches that are restricted to manipulations of facial expressions only, we are the first to transfer the full 3D head position, head rotation, face expression, eye gaze, and eye blinking from a source actor to a portrait video of a target actor. The core of our approach is a generative neural network with a novel space-time architecture. The network takes as input synthetic renderings of a parametric face model, based on which it predicts photo-realistic video frames for a given target actor. The realism in this rendering-to-video transfer is achieved by careful adversarial training, and as a result, we can create modified target videos that mimic the behavior of the synthetically-created input. In order to enable source-to-target video re-animation, we render a synthetic target video with the reconstructed head animation parameters from a source video, and feed it into the trained network -- thus taking full control of the target. With the ability to freely recombine source and target parameters, we are able to demonstrate a large variety of video rewrite applications without explicitly modeling hair, body or background. For instance, we can reenact the full head using interactive user-controlled editing, and realize high-fidelity visual dubbing. To demonstrate the high quality of our output, we conduct an extensive series of experiments and evaluations, where for instance a user study shows that our video edits are hard to detect.

##### Abstract (translated by Google)
我们提出了一种新颖的方法，可以仅使用输入视频对照片逼真的肖像视频进行重新动画。与仅限于面部表情操作的现有方法相比，我们是第一个将来自源演员的全3D头部位置，头部旋转，脸部表情，眼睛注视和眨眼转移到目标的肖像视频演员。我们的方法的核心是具有新颖时空结构的生成神经网络。该网络将参数人脸模型的合成渲染作为输入，基于该模型预测给定目标演员的照片般逼真的视频帧。这种渲染到视频传输的真实性是通过仔细的对抗训练来实现的，因此我们可以创建修改后的目标视频，模仿合成创建输入的行为。为了实现源到目标视频的重新动画，我们使用源视频重建的头部动画参数渲染合成目标视频，并将其馈送到训练好的网络 - 从而完全控制目标。凭借自由组合源和目标参数的能力，我们能够演示各种各样的视频重写应用程序，而无需明确建模头发，身体或背景。例如，我们可以使用交互式用户控制编辑重新演绎完整的头部，并实现高保真视觉配音。为了证明我们的输出质量高，我们进行了一系列广泛的实验和评估，例如用户研究表明我们的视频编辑很难检测到。

##### URL
[https://arxiv.org/abs/1805.11714](https://arxiv.org/abs/1805.11714)

##### PDF
[https://arxiv.org/pdf/1805.11714](https://arxiv.org/pdf/1805.11714)

