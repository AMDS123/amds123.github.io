---
layout: post
title: "Pose-Selective Max Pooling for Measuring Similarity"
date: 2016-11-14 04:10:09
categories: arXiv_CV
tags: arXiv_CV Face Relation Recognition Face_Recognition
author: Xiang Xiang, Trac D. Tran
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we deal with two challenges for measuring the similarity of the subject identities in practical video-based face recognition - the variation of the head pose in uncontrolled environments and the computational expense of processing videos. Since the frame-wise feature mean is unable to characterize the pose diversity among frames, we define and preserve the overall pose diversity and closeness in a video. Then, identity will be the only source of variation across videos since the pose varies even within a single video. Instead of simply using all the frames, we select those faces whose pose point is closest to the centroid of the K-means cluster containing that pose point. Then, we represent a video as a bag of frame-wise deep face features while the number of features has been reduced from hundreds to K. Since the video representation can well represent the identity, now we measure the subject similarity between two videos as the max correlation among all possible pairs in the two bags of features. On the official 5,000 video-pairs of the YouTube Face dataset for face verification, our algorithm achieves a comparable performance with VGG-face that averages over deep features of all frames. Other vision tasks can also benefit from the generic idea of employing geometric cues to improve the descriptiveness of deep features.

##### Abstract (translated by Google)
在本文中，我们处理实际基于视频的人脸识别中测量主体身份的相似性的两个挑战 - 不受控制的环境中头部姿态的变化以及处理视频的计算开销。由于逐帧特征均值不能表征帧之间的姿态差异，因此我们定义并保持视频中的总体姿态差异和接近度。然后，身份将成为跨视频变化的唯一来源，因为即使在一个视频内，姿态也会变化。我们选择那些姿态点最接近含有该姿态点的K均值聚类的质心的面，而不是简单地使用所有的帧。然后，我们将视频表示为一系列逐帧深度特征，而特征的数量从数百个减少到了K个。由于视频表示可以很好地表示身份，因此现在我们测量两个视频之间的主题相似度两包特征中所有可能的配对之间的最大相关性。在用于脸部验证的YouTube脸部数据集的官方5,000视频对中，我们的算法实现了与VGG脸部相当的性能，其平均在所有帧的深度特征上。其他视觉任务也可以受益于使用几何线索来改善深度特征的描述性的一般想法。

##### URL
[https://arxiv.org/abs/1609.07042](https://arxiv.org/abs/1609.07042)

##### PDF
[https://arxiv.org/pdf/1609.07042](https://arxiv.org/pdf/1609.07042)

