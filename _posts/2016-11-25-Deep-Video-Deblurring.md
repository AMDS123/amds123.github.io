---
layout: post
title: "Deep Video Deblurring"
date: 2016-11-25 08:51:51
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Shuochen Su, Mauricio Delbracio, Jue Wang, Guillermo Sapiro, Wolfgang Heidrich, Oliver Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Motion blur from camera shake is a major problem in videos captured by hand-held devices. Unlike single-image deblurring, video-based approaches can take advantage of the abundant information that exists across neighboring frames. As a result the best performing methods rely on aligning nearby frames. However, aligning images is a computationally expensive and fragile procedure, and methods that aggregate information must therefore be able to identify which regions have been accurately aligned and which have not, a task which requires high level scene understanding. In this work, we introduce a deep learning solution to video deblurring, where a CNN is trained end-to-end to learn how to accumulate information across frames. To train this network, we collected a dataset of real videos recorded with a high framerate camera, which we use to generate synthetic motion blur for supervision. We show that the features learned from this dataset extend to deblurring motion blur that arises due to camera shake in a wide range of videos, and compare the quality of results to a number of other baselines.

##### Abstract (translated by Google)
来自相机抖动的运动模糊是手持设备捕捉的视频中的主要问题。与单幅图像去模糊不同，基于视频的方法可以利用相邻帧中存在的丰富信息。因此，最好的执行方法依靠对齐附近的帧。然而，对齐图像是一个计算昂贵和脆弱的过程，聚合信息的方法因此必须能够识别哪些区域已经被精确对准，哪些没有，哪些是需要高级别场景理解的任务。在这项工作中，我们引入了视频去模糊的深度学习解决方案，CNN是端到端培训，学习如何在帧之间积累信息。为了训练这个网络，我们收集了一个用高帧率摄像机记录的真实视频的数据集，我们使用这个数据集来产生用于监视的合成运动模糊。我们展示了从这个数据集中学习的特征可以扩展到去除由于相机抖动引起的运动模糊，并将结果的质量与许多其他基线进行比较。

##### URL
[https://arxiv.org/abs/1611.08387](https://arxiv.org/abs/1611.08387)

##### PDF
[https://arxiv.org/pdf/1611.08387](https://arxiv.org/pdf/1611.08387)

