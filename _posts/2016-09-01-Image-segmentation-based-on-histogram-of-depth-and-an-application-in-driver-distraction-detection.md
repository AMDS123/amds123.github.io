---
layout: post
title: "Image segmentation based on histogram of depth and an application in driver distraction detection"
date: 2016-09-01 03:19:43
categories: arXiv_CV
tags: arXiv_CV Segmentation Detection
author: Tran Hiep Dinh, Minh Trien Pham, Manh Duong Phung, Duc Manh Nguyen, Van Manh Hoang, Quang Vinh Tran
mathjax: true
---

* content
{:toc}

##### Abstract
This study proposes an approach to segment human object from a depth image based on histogram of depth values. The region of interest is first extracted based on a predefined threshold for histogram regions. A region growing process is then employed to separate multiple human bodies with the same depth interval. Our contribution is the identification of an adaptive growth threshold based on the detected histogram region. To demonstrate the effectiveness of the proposed method, an application in driver distraction detection was introduced. After successfully extracting the driver's position inside the car, we came up with a simple solution to track the driver motion. With the analysis of the difference between initial and current frame, a change of cluster position or depth value in the interested region, which cross the preset threshold, is considered as a distracted activity. The experiment results demonstrated the success of the algorithm in detecting typical distracted driving activities such as using phone for calling or texting, adjusting internal devices and drinking in real time.

##### Abstract (translated by Google)
本研究提出了一种基于深度值直方图的深度图像分割人体对象的方法。首先基于直方图区域的预定义阈值来提取感兴趣区域。然后采用区域生长过程来以相同的深度间隔分离多个人体。我们的贡献是基于检测到的直方图区域来识别适应性增长阈值。为了证明所提出的方法的有效性，引入了驾驶员分心检测中的应用。在成功提取驾驶员在车内的位置之后，我们想出了一个简单的解决方案来跟踪驾驶员的动作。通过分析初始帧和当前帧之间的差异，感兴趣区域中与预设阈值相交的聚类位置或深度值的变化被认为是分散的活动。实验结果证明了该算法在检测典型的分心驾驶活动中的成功，例如使用电话呼叫或发短信，调整内部设备和实时饮用。

##### URL
[https://arxiv.org/abs/1609.00096](https://arxiv.org/abs/1609.00096)

##### PDF
[https://arxiv.org/pdf/1609.00096](https://arxiv.org/pdf/1609.00096)

