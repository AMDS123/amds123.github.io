---
layout: post
title: "Self-Supervised Depth Learning for Urban Scene Understanding"
date: 2017-12-13 16:39:14
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Detection Relation
author: Huaizu Jiang, Erik Learned-Miller, Gustav Larsson, Michael Maire, Greg Shakhnarovich
mathjax: true
---

* content
{:toc}

##### Abstract
As an agent moves through the world, the apparent motion of scene elements is (usually) inversely proportional to their depth. It is natural for a learning agent to associate image patterns with the magnitude of their displacement over time: as the agent moves, far away mountains don't move much; nearby trees move a lot. This natural relationship between the appearance of objects and their motion is a rich source of information about the world. In this work, we train a deep network, using fully automatic supervision, to predict relative scene depth from single images. The depth training images are automatically derived from simple videos of cars moving through a scene, using classic depth from motion techniques, and no human provided labels. We show that this pretext task of predicting depth from a single image induces features in the network that result in large improvements in a set of downstream tasks including semantic segmentation, joint road segmentation and car detection, and monocular (absolute) depth estimation, over a network trained from scratch. In particular, our pre-trained model outperforms an ImageNet counterpart for the monocular depth estimation task. Unlike work that analyzes video paired with additional information about direction of motion, our agent learns from "raw egomotion" video recorded from cars moving through the world. Unlike methods that require videos of moving objects, we neither depend on, nor are disrupted by, moving objects in the video. Indeed, we can benefit from predicting depth in the videos associated with various downstream tasks, showing that we can adapt to new scenes in an unsupervised manner to improve performance. By doing so, we achieve consistently better results over several different urban scene understanding tasks, obtaining results that are competitive with state-of-the-art method for monocular depth estimation.

##### Abstract (translated by Google)
当代理人在世界中移动时，场景元素的明显运动（通常）与其深度成反比。学习代理人很自然会将图像模式与他们的位移幅度相关联：随着代理人的移动，远处的山脉不会移动太多;附近的树移动了很多。物体外观与运动之间的这种自然关系是关于世界的丰富信息来源。在这项工作中，我们训练一个深度网络，使用全自动监测，从单个图像预测相对场景深度。深度训练图像是从运动场景中的汽车的简单视频自动获得的，使用运动技术的经典深度，并且没有人为提供的标签。我们表明，这个从单个图像预测深度的借口任务诱导网络中的特征，导致包括语义分割，联合道路分割和汽车检测以及单目（绝对）深度估计的一组下游任务网络从零开始训练。特别是，我们的预先训练的模型胜过一个ImageNet对应单眼深度估计任务。与分析视频配合运动方向附加信息的工作不同，我们的代理人从通过世界移动的汽车记录的“原始自我”视频中学习。与需要移动对象视频的方法不同，我们既不依赖也不会破坏视频中的对象。事实上，我们可以通过预测与各种下游任务相关的视频的深度来获益，表明我们可以以无监督的方式适应新的场景来提高性能。通过这样做，我们在多个不同的城市场景理解任务上获得了一致的更好的结果，获得了与单眼深度估计的最先进方法相竞争的结果。

##### URL
[http://arxiv.org/abs/1712.04850](http://arxiv.org/abs/1712.04850)

##### PDF
[http://arxiv.org/pdf/1712.04850](http://arxiv.org/pdf/1712.04850)

