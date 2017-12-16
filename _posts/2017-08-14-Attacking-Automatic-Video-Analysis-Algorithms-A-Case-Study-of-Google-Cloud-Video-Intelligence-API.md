---
layout: post
title: "Attacking Automatic Video Analysis Algorithms: A Case Study of Google Cloud Video Intelligence API"
date: 2017-08-14 20:10:04
categories: arXiv_CV
tags: arXiv_CV Adversarial Attention Face Video_Classification Classification Detection
author: Hossein Hosseini, Baicen Xiao, Andrew Clark, Radha Poovendran
mathjax: true
---

* content
{:toc}

##### Abstract
Due to the growth of video data on Internet, automatic video analysis has gained a lot of attention from academia as well as companies such as Facebook, Twitter and Google. In this paper, we examine the robustness of video analysis algorithms in adversarial settings. Specifically, we propose targeted attacks on two fundamental classes of video analysis algorithms, namely video classification and shot detection. We show that an adversary can subtly manipulate a video in such a way that a human observer would perceive the content of the original video, but the video analysis algorithm will return the adversary's desired outputs. We then apply the attacks on the recently released Google Cloud Video Intelligence API. The API takes a video file and returns the video labels (objects within the video), shot changes (scene changes within the video) and shot labels (description of video events over time). Through experiments, we show that the API generates video and shot labels by processing only the first frame of every second of the video. Hence, an adversary can deceive the API to output only her desired video and shot labels by periodically inserting an image into the video at the rate of one frame per second. We also show that the pattern of shot changes returned by the API can be mostly recovered by an algorithm that compares the histograms of consecutive frames. Based on our equivalent model, we develop a method for slightly modifying the video frames, in order to deceive the API into generating our desired pattern of shot changes. We perform extensive experiments with different videos and show that our attacks are consistently successful across videos with different characteristics. At the end, we propose introducing randomness to video analysis algorithms as a countermeasure to our attacks.

##### Abstract (translated by Google)
由于互联网视频数据的增长，自动视频分析已经引起了学术界以及Facebook，Twitter，Google等公司的广泛关注。在本文中，我们研究对抗设置中的视频分析算法的鲁棒性。具体而言，我们提出针对性的视频分析算法，即视频分类和镜头检测。我们表明，对手可以巧妙地操纵一个视频，使得观察者可以感知原始视频的内容，但视频分析算法会返回对手所需的输出。然后，我们将这些攻击应用到最近发布的Google云端视频智能API上。 API接收视频文件并返回视频标签（视频内的对象），镜头更改（视频内的场景更改）和镜头标签（视频事件随时间的描述）。通过实验，我们显示API通过仅处理视频的每一秒的第一帧来生成视频和镜头标签。因此，敌手可以通过以每秒一帧的速率周期性地将图像插入到视频中来欺骗API以仅输出她期望的视频和镜头标签。我们还表明，API返回的镜头变化模式大部分可以通过比较连续帧的直方图的算法来恢复。基于我们的等效模型，我们开发了一种略微修改视频帧的方法，以欺骗API来生成我们所需的镜头变化模式。我们通过不同的视频进行大量实验，并显示我们的攻击在不同视频具有不同的特点的情况下始终如一最后，我们建议在视频分析算法中引入随机性作为我们攻击的一种对策。

##### URL
[https://arxiv.org/abs/1708.04301](https://arxiv.org/abs/1708.04301)

##### PDF
[https://arxiv.org/pdf/1708.04301](https://arxiv.org/pdf/1708.04301)

