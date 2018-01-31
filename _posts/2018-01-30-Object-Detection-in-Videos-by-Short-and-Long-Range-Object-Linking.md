---
layout: post
title: "Object Detection in Videos by Short and Long Range Object Linking"
date: 2018-01-30 01:59:50
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection
author: Peng Tang, Chunyu Wang, Xinggang Wang, Wenyu Liu, Wenjun Zeng, Jingdong Wang
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of detecting objects in videos with the interest in exploring temporal contexts. Our core idea is to link objects in the short and long ranges for improving the classification quality. Our approach first proposes a set of candidate spatio-temporal cuboids, each of which serves as a container associating the object across short range frames, for a short video segment. It then regresses the precise box locations in each frame over each cuboid proposal, yielding a tubelet with a single classification score which is aggregated from the scores of the boxes in the tubelet. Third, we extend the non-maximum suppression algorithm to remove spatially-overlapping tubelets in the short segment, avoiding tubelets broken by the frame-wise NMS. Finally, we link the tubelets across temporally-overlapping short segments over the whole video, in order to boost the classification scores for positive detections by aggregating the scores in the linked tubelets. Experiments on the ImageNet VID dataset shows that our approach achieves the state-of-the-art performance.

##### Abstract (translated by Google)
我们解决了在视频中检测对象的问题，这些问题有助于探索时间背景。我们的核心思想是将短程和长程的物体连接起来，以提高分类质量。我们的方法首先提出了一组候选时空长方体，其中每个长方体用作跨短程帧相关联的容器，用于短视频片段。然后，在每个长方体建议的每个框架中回归精确的盒子位置，产生具有单一分类分数的管子，该分数从管盒中的盒子的分数聚合而成。第三，扩展非最大抑制算法，去除短段中空间重叠的小管，避免由逐帧网管破坏小管。最后，我们将整个视频中跨越时间重叠的短片段的小管连接起来，以便通过对连接的小管中的分数进行汇总来提高阳性检测的分类分数。 ImageNet VID数据集上的实验表明，我们的方法达到了最先进的性能。

##### URL
[http://arxiv.org/abs/1801.09823](http://arxiv.org/abs/1801.09823)

##### PDF
[http://arxiv.org/pdf/1801.09823](http://arxiv.org/pdf/1801.09823)

