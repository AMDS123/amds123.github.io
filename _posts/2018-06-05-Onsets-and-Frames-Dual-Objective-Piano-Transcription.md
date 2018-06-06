---
layout: post
title: "Onsets and Frames: Dual-Objective Piano Transcription"
date: 2018-06-05 04:20:28
categories: arXiv_SD
tags: arXiv_SD Object_Detection CNN Inference Prediction Detection
author: Curtis Hawthorne, Erich Elsen, Jialin Song, Adam Roberts, Ian Simon, Colin Raffel, Jesse Engel, Sageev Oore, Douglas Eck
mathjax: true
---

* content
{:toc}

##### Abstract
We advance the state of the art in polyphonic piano music transcription by using a deep convolutional and recurrent neural network which is trained to jointly predict onsets and frames. Our model predicts pitch onset events and then uses those predictions to condition framewise pitch predictions. During inference, we restrict the predictions from the framewise detector by not allowing a new note to start unless the onset detector also agrees that an onset for that pitch is present in the frame. We focus on improving onsets and offsets together instead of either in isolation as we believe this correlates better with human musical perception. Our approach results in over a 100% relative improvement in note F1 score (with offsets) on the MAPS dataset. Furthermore, we extend the model to predict relative velocities of normalized audio which results in more natural-sounding transcriptions.

##### Abstract (translated by Google)
我们通过使用经过训练以联合预测起始帧和帧的深层卷积和递归神经网络来提高复调钢琴音乐转录的艺术水平。我们的模型预测音调起始事件，然后使用这些预测来调节帧间音调预测。在推断过程中，我们通过不允许开始新的音符来限制来自帧检测器的预测，除非开始检测器也同意帧中出现该音调的开始。我们专注于改善起音和偏移，而不是孤立地进行，因为我们认为这与人类音乐感知更好地相关。我们的方法可以使MAPS数据集中的音符F1分数（带有偏移量）的相对改进超过100％。此外，我们扩展模型以预测归一化音频的相对速度，从而导致更加自然的转录。

##### URL
[http://arxiv.org/abs/1710.11153](http://arxiv.org/abs/1710.11153)

##### PDF
[http://arxiv.org/pdf/1710.11153](http://arxiv.org/pdf/1710.11153)

