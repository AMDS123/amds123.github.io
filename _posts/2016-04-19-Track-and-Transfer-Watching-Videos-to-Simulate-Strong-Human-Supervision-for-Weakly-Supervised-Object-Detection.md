---
layout: post
title: "Track and Transfer: Watching Videos to Simulate Strong Human Supervision for Weakly-Supervised Object Detection"
date: 2016-04-19 22:23:29
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Krishna Kumar Singh, Fanyi Xiao, Yong Jae Lee
mathjax: true
---

* content
{:toc}

##### Abstract
The status quo approach to training object detectors requires expensive bounding box annotations. Our framework takes a markedly different direction: we transfer tracked object boxes from weakly-labeled videos to weakly-labeled images to automatically generate pseudo ground-truth boxes, which replace manually annotated bounding boxes. We first mine discriminative regions in the weakly-labeled image collection that frequently/rarely appear in the positive/negative images. We then match those regions to videos and retrieve the corresponding tracked object boxes. Finally, we design a hough transform algorithm to vote for the best box to serve as the pseudo GT for each image, and use them to train an object detector. Together, these lead to state-of-the-art weakly-supervised detection results on the PASCAL 2007 and 2010 datasets.

##### Abstract (translated by Google)
训练对象检测器的现状方法需要昂贵的边界框注释。我们的框架采取了明显不同的方向：我们将跟踪对象框从弱标记的视频转移到弱标记的图像，自动生成伪地面真值框，取代手动标注的边界框。我们首先在弱/标记的图像集合中挖掘区别性区域，其经常/很少出现在正面/负面图像中。然后，我们将这些区域与视频进行匹配，并检索相应的跟踪对象框。最后，我们设计了一个hough变换算法来投票选出最好的盒子作为每个图像的伪GT，并用它们来训练一个物体检测器。这些结果一起导致了2007年和2010年的PASCAL数据集上的最先进的弱监督检测结果。

##### URL
[https://arxiv.org/abs/1604.05766](https://arxiv.org/abs/1604.05766)

