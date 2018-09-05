---
layout: post
title: "Deep Room Recognition Using Inaudible Echos"
date: 2018-09-03 10:17:14
categories: arXiv_SD
tags: arXiv_SD CNN Deep_Learning Recognition
author: Qun Song, Chaojie Gu, Rui Tan
mathjax: true
---

* content
{:toc}

##### Abstract
Recent years have seen the increasing need of location awareness by mobile applications. This paper presents a room-level indoor localization approach based on the measured room's echos in response to a two-millisecond single-tone inaudible chirp emitted by a smartphone's loudspeaker. Different from other acoustics-based room recognition systems that record full-spectrum audio for up to ten seconds, our approach records audio in a narrow inaudible band for 0.1 seconds only to preserve the user's privacy. However, the short-time and narrowband audio signal carries limited information about the room's characteristics, presenting challenges to accurate room recognition. This paper applies deep learning to effectively capture the subtle fingerprints in the rooms' acoustic responses. Our extensive experiments show that a two-layer convolutional neural network fed with the spectrogram of the inaudible echos achieve the best performance, compared with alternative designs using other raw data formats and deep models. Based on this result, we design a RoomRecognize cloud service and its mobile client library that enable the mobile application developers to readily implement the room recognition functionality without resorting to any existing infrastructures and add-on hardware. 
 Extensive evaluation shows that RoomRecognize achieves 99.7%, 97.7%, 99%, and 89% accuracy in differentiating 22 and 50 residential/office rooms, 19 spots in a quiet museum, and 15 spots in a crowded museum, respectively. Compared with the state-of-the-art approaches based on support vector machine, RoomRecognize significantly improves the Pareto frontier of recognition accuracy versus robustness against interfering sounds (e.g., ambient music).

##### Abstract (translated by Google)
近年来，移动应用程序对位置感知的需求日益增加。本文介绍了一种基于测量房间回声的房间级室内定位方法，以响应智能手机扬声器发出的2毫秒单音无声啁啾声。与其他基于声学的房间识别系统不同，我们的方法将录制的全频谱音频长达十秒，我们的方法将音频录制在一个狭窄的听不见的频段0.1秒，只是为了保护用户的隐私。然而，短时和窄带音频信号携带有关房间特征的有限信息，对准确的房间识别提出了挑战。本文采用深度学习有效捕捉房间声学反应中的细微指纹。我们的广泛实验表明，与使用其他原始数据格式和深度模型的替代设计相比，使用听不见回声谱图的双层卷积神经网络可实现最佳性能。基于此结果，我们设计了RoomRecognize云服务及其移动客户端库，使移动应用程序开发人员能够轻松实现房间识别功能，而无需借助任何现有的基础架构和附加硬件。
 广泛的评估表明，RoomRecognize分别在22和50个住宅/办公室，一个安静的博物馆中的19个景点和拥挤的博物馆中的15个景点分别达到99.7％，97.7％，99％和89％的准确度。与基于支持向量机的最先进方法相比，RoomRecognize显着改善了识别准确度的帕累托前沿与干扰声音（例如，环境音乐）的鲁棒性。

##### URL
[http://arxiv.org/abs/1809.00531](http://arxiv.org/abs/1809.00531)

##### PDF
[http://arxiv.org/pdf/1809.00531](http://arxiv.org/pdf/1809.00531)

