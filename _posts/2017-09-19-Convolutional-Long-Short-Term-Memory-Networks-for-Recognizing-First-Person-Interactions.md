---
layout: post
title: "Convolutional Long Short-Term Memory Networks for Recognizing First Person Interactions"
date: 2017-09-19 15:58:28
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Classification Deep_Learning Memory_Networks Recognition
author: Swathikiran Sudhakaran, Oswald Lanz
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a novel deep learning based approach for addressing the problem of interaction recognition from a first person perspective. The proposed approach uses a pair of convolutional neural networks, whose parameters are shared, for extracting frame level features from successive frames of the video. The frame level features are then aggregated using a convolutional long short-term memory. The hidden state of the convolutional long short-term memory, after all the input video frames are processed, is used for classification in to the respective categories. The two branches of the convolutional neural network perform feature encoding on a short time interval whereas the convolutional long short term memory encodes the changes on a longer temporal duration. In our network the spatio-temporal structure of the input is preserved till the very final processing stage. Experimental results show that our method outperforms the state of the art on most recent first person interactions datasets that involve complex ego-motion. In particular, on UTKinect-FirstPerson it competes with methods that use depth image and skeletal joints information along with RGB images, while it surpasses all previous methods that use only RGB images by more than 20% in recognition accuracy.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的基于深度学习的方法来解决第一人称视角下的交互识别问题。所提出的方法使用一对卷积神经网络，其参数是共享的，用于从视频的连续帧中提取帧级特征。然后使用卷积长的短期内存来聚合帧级特征。在所有输入视频帧被处理之后，卷积长短期存储器的隐藏状态被用于分类到相应的类别中。卷积神经网络的两个分支在短时间间隔上执行特征编码，而卷积长期短期存储器在较长的时间间隔上编码变化。在我们的网络中，输入的时空结构被保存到最后的处理阶段。实验结果表明，我们的方法胜过了最新的第一人称相互作用数据集，涉及复杂的自我运动的艺术状态。特别是在UTKinect-FirstPerson上，它与使用深度图像和骨骼关节信息以及RGB图像的方法相竞争，同时它超越了所有以前只使用RGB图像的方法，其识别精度超过了20％。

##### URL
[https://arxiv.org/abs/1709.06495](https://arxiv.org/abs/1709.06495)

##### PDF
[https://arxiv.org/pdf/1709.06495](https://arxiv.org/pdf/1709.06495)

