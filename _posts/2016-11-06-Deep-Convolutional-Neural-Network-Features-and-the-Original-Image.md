---
layout: post
title: "Deep Convolutional Neural Network Features and the Original Image"
date: 2016-11-06 10:32:37
categories: arXiv_CV
tags: arXiv_CV Face CNN Recognition Face_Recognition
author: Connor J. Parde, Carlos Castillo, Matthew Q. Hill, Y. Ivette Colon, Swami Sankaranarayanan, Jun-Cheng Chen, Alice J. O'Toole
mathjax: true
---

* content
{:toc}

##### Abstract
Face recognition algorithms based on deep convolutional neural networks (DCNNs) have made progress on the task of recognizing faces in unconstrained viewing conditions. These networks operate with compact feature-based face representations derived from learning a very large number of face images. While the learned features produced by DCNNs can be highly robust to changes in viewpoint, illumination, and appearance, little is known about the nature of the face code that emerges at the top level of such networks. We analyzed the DCNN features produced by two face recognition algorithms. In the first set of experiments we used the top-level features from the DCNNs as input into linear classifiers aimed at predicting metadata about the images. The results show that the DCNN features contain surprisingly accurate information about the yaw and pitch of a face, and about whether the face came from a still image or a video frame. In the second set of experiments, we measured the extent to which individual DCNN features operated in a view-dependent or view-invariant manner. We found that view-dependent coding was a characteristic of the identities rather than the DCNN features - with some identities coded consistently in a view-dependent way and others in a view-independent way. In our third analysis, we visualized the DCNN feature space for over 24,000 images of 500 identities. Images in the center of the space were uniformly of low quality (e.g., extreme views, face occlusion, low resolution). Image quality increased monotonically as a function of distance from the origin. This result suggests that image quality information is available in the DCNN features, such that consistently average feature values reflect coding failures that reliably indicate poor or unusable images. Combined, the results offer insight into the coding mechanisms that support robust representation of faces in DCNNs.

##### Abstract (translated by Google)
基于深度卷积神经网络（DCNN）的人脸识别算法在无约束条件下的人脸识别任务方面取得了长足的进步。这些网络使用基于紧凑特征的人脸表示进行操作，该人脸表示是从学习大量的人脸图像中获得的。尽管由DCNN产生的学习特征对于视点，照明和外观的变化具有高度的稳健性，但是对于在这种网络的顶层出现的人脸代码的性质知之甚少。我们分析了两种人脸识别算法产生的DCNN特征。在第一组实验中，我们使用DCNN中的顶级特征作为线性分类器的输入，用于预测关于图像的元数据。结果显示，DCNN特征含有令人惊讶的关于面部的偏航和俯仰的准确信息，以及面部是来自静止图像还是视频帧。在第二组实验中，我们测量了单个DCNN特征以视图相关或视图不变的方式运行的程度。我们发现，依赖于视图的编码是身份的一个特征，而不是DCNN的特征 - 一些身份以依赖视图的方式一致地编码，而另一些以独立于视图的方式编码。在第三个分析中，我们将DCNN特征空间可视化为超过24000个500个身份的图像。空间中心的图像质量一致（例如，极端视图，面部遮挡，低分辨率）。图像质量随距离原点的距离而单调递增。这个结果表明图像质量信息在DCNN特征中是可用的，使得一致的平均特征值反映编码失败，其可靠地指示差的或不可用的图像。综合起来，这些结果提供了对支持DCNN中人脸健壮表示的编码机制的深入了解。

##### URL
[https://arxiv.org/abs/1611.01751](https://arxiv.org/abs/1611.01751)

##### PDF
[https://arxiv.org/pdf/1611.01751](https://arxiv.org/pdf/1611.01751)

