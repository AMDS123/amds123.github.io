---
layout: post
title: "Temporal-Spatial Mapping for Action Recognition"
date: 2018-09-11 03:29:28
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention Action_Recognition CNN Image_Classification Classification Deep_Learning Detection Recognition
author: Xiaolin Song, Cuiling Lan, Wenjun Zeng, Junliang Xing, Jingyu Yang, Xiaoyan Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning models have enjoyed great success for image related computer vision tasks like image classification and object detection. For video related tasks like human action recognition, however, the advancements are not as significant yet. The main challenge is the lack of effective and efficient models in modeling the rich temporal spatial information in a video. We introduce a simple yet effective operation, termed Temporal-Spatial Mapping (TSM), for capturing the temporal evolution of the frames by jointly analyzing all the frames of a video. We propose a video level 2D feature representation by transforming the convolutional features of all frames to a 2D feature map, referred to as VideoMap. With each row being the vectorized feature representation of a frame, the temporal-spatial features are compactly represented, while the temporal dynamic evolution is also well embedded. Based on the VideoMap representation, we further propose a temporal attention model within a shallow convolutional neural network to efficiently exploit the temporal-spatial dynamics. The experiment results show that the proposed scheme achieves the state-of-the-art performance, with 4.2% accuracy gain over Temporal Segment Network (TSN), a competing baseline method, on the challenging human action benchmark dataset HMDB51.

##### Abstract (translated by Google)
深度学习模型在图像分类和对象检测等图像相关计算机视觉任务中取得了巨大成功。然而，对于像人类动作识别这样的视频相关任务，进步并不那么重要。主要的挑战是缺乏有效和高效的模型来模拟视频中丰富的时空信息。我们引入了一种简单而有效的操作，称为时空映射（TSM），用于通过联合分析视频的所有帧来捕获帧的时间演变。我们通过将所有帧的卷积特征变换为2D特征映射（称为VideoMap）来提出视频级2D特征表示。由于每一行是帧的矢量化特征表示，因此时空特征被紧凑地表示，而时间动态演化也被很好地嵌入。基于VideoMap表示，我们进一步提出浅层卷积神经网络中的时间关注模型，以有效地利用时空动态。实验结果表明，所提出的方案实现了最先进的性能，在具有挑战性的人类活动基准数据集HMDB51上，相对于时间段网络（TSN）（竞争基线方法）的准确度增益为4.2％。

##### URL
[http://arxiv.org/abs/1809.03669](http://arxiv.org/abs/1809.03669)

##### PDF
[http://arxiv.org/pdf/1809.03669](http://arxiv.org/pdf/1809.03669)

