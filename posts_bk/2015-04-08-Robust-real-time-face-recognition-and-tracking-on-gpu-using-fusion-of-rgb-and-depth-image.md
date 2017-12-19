---
layout: post
title: "Robust real time face recognition and tracking on gpu using fusion of rgb and depth image"
date: 2015-04-08 09:34:30
categories: arXiv_CV
tags: arXiv_CV Face Tracking Recognition Face_Recognition
author: Narmada Naik, G.N Rathna
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a real-time face recognition system using kinect sensor. The algorithm is implemented on GPU using opencl and significant speed improvements are observed. We use kinect depth image to increase the robustness and reduce computational cost of conventional LBP based face recognition. The main objective of this paper was to perform robust, high speed fusion based face recognition and tracking. The algorithm is mainly composed of three steps. First step is to detect all faces in the video using viola jones algorithm. The second step is online database generation using a tracking window on the face. A modified LBP feature vector is calculated using fusion information from depth and greyscale image on GPU. This feature vector is used to train a svm classifier. Third step involves recognition of multiple faces based on our modified feature vector.

##### Abstract (translated by Google)
本文提出了一个使用kinect传感器的实时人脸识别系统。该算法是使用opencl在GPU上实现的，并观察到显着的速度改进。我们使用kinect深度图像来提高传统的基于LBP的人脸识别的鲁棒性和降低计算成本。本文的主要目标是执行鲁棒的，高速融合的人脸识别和跟踪。该算法主要由三个步骤组成。第一步是使用viola jones算法检测视频中的所有人脸。第二步是使用脸上的跟踪窗口生成在线数据库。使用来自GPU上的深度和灰度图像的融合信息来计算修改的LBP特征向量。这个特征向量被用来训练一个svm分类器。第三步涉及基于修改后的特征向量识别多个人脸。

##### URL
[https://arxiv.org/abs/1504.01883](https://arxiv.org/abs/1504.01883)

##### PDF
[https://arxiv.org/pdf/1504.01883](https://arxiv.org/pdf/1504.01883)

