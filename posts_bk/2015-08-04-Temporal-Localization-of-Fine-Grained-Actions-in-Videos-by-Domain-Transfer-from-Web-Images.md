---
layout: post
title: "Temporal Localization of Fine-Grained Actions in Videos by Domain Transfer from Web Images"
date: 2015-08-04 07:04:34
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Memory_Networks Recognition
author: Chen Sun, Sanketh Shetty, Rahul Sukthankar, Ram Nevatia
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of fine-grained action localization from temporally untrimmed web videos. We assume that only weak video-level annotations are available for training. The goal is to use these weak labels to identify temporal segments corresponding to the actions, and learn models that generalize to unconstrained web videos. We find that web images queried by action names serve as well-localized highlights for many actions, but are noisily labeled. To solve this problem, we propose a simple yet effective method that takes weak video labels and noisy image labels as input, and generates localized action frames as output. This is achieved by cross-domain transfer between video frames and web images, using pre-trained deep convolutional neural networks. We then use the localized action frames to train action recognition models with long short-term memory networks. We collect a fine-grained sports action data set FGA-240 of more than 130,000 YouTube videos. It has 240 fine-grained actions under 85 sports activities. Convincing results are shown on the FGA-240 data set, as well as the THUMOS 2014 localization data set with untrimmed training videos.

##### Abstract (translated by Google)
我们从时间上不受限制的网络视频中解决细粒度的动作本地化问题。我们假设只有弱视频级别的注释可用于培训。目标是使用这些弱标签来识别与动作相对应的时间片段，并学习推广到无约束网络视频的模型。我们发现，通过操作名称查询的网页图像可以作为许多操作的本地化亮点，但却被标注为不恰当的。为了解决这个问题，我们提出了一个简单而有效的方法，以弱视频标签和噪声图像标签为输入，生成本地化的动作帧作为输出。这是通过使用预先训练的深度卷积神经网络在视频帧和网络图像之间的跨域转移来实现的。然后，我们使用本地化动作帧来训练具有长期短期记忆网络的动作识别模型。我们收集了130,000多个YouTube视频的细粒度体育行动数据集FGA-240。在85项体育活动中，有240项细粒度的行动。令人信服的结果显示在FGA-240数据集上，以及带有未修改培训视频的THUMOS 2014本地化数据集。

##### URL
[https://arxiv.org/abs/1504.00983](https://arxiv.org/abs/1504.00983)

##### PDF
[https://arxiv.org/pdf/1504.00983](https://arxiv.org/pdf/1504.00983)

