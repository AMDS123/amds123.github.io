---
layout: post
title: "Object Detection in Videos by High Quality Object Linking"
date: 2018-06-10 23:46:22
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection
author: Peng Tang, Chunyu Wang, Xinggang Wang, Wenyu Liu, Wenjun Zeng, Jingdong Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Compared with object detection in static images, object detection in videos is more challenging due to degraded image qualities. An effective way to address this problem is to exploit temporal contexts by linking the same object across video to form tubelets and aggregating classification scores in the tubelets. In this paper, we focus on obtaining high quality object linking results for better classification. Unlike previous methods that link objects by checking boxes between neighboring frames, we propose to link in the same frame. To achieve this goal, we extend prior methods in following aspects: (1) a cuboid proposal network that extracts spatio-temporal candidate cuboids which bound the movement of objects; (2) a short tubelet detection network that detects short tubelets in short video segments; (3) a short tubelet linking algorithm that links temporally-overlapping short tubelets to form long tubelets. Experiments on the ImageNet VID dataset show that our method outperforms both the static image detector and the previous state of the art. In particular, our method improves results by 8.8% over the static image detector for fast moving objects.

##### Abstract (translated by Google)
与静态图像中的对象检测相比，由于图像质量下降，视频中的对象检测更具挑战性。解决这个问题的一个有效方法是利用时间上下文，将视频中的同一对象链接起来形成小管，并在小管中聚集分类分数。在本文中，我们专注于获得高质量的对象链接结果以实现更好的分类。与之前通过检查相邻帧之间的框链接对象的方法不同，我们建议链接在同一帧中。为了实现这一目标，我们在以下几个方面扩展了先前的方法：（1）提取时空候选立方体的立方体提议网络，该立方体限制了对象的移动; （2）短视频检测网络，其检测短视频片段中的短小管; （3）连接暂时重叠的短小管以形成长小管的短小管连接算法。 ImageNet VID数据集上的实验表明，我们的方法优于静态图像检测器和先前的技术状态。特别是，我们的方法比快速移动物体的静态图像检测器的结果提高了8.8％。

##### URL
[http://arxiv.org/abs/1801.09823](http://arxiv.org/abs/1801.09823)

##### PDF
[http://arxiv.org/pdf/1801.09823](http://arxiv.org/pdf/1801.09823)

