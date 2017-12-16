---
layout: post
title: "Unsupervised object segmentation in video by efficient selection of highly probable positive features"
date: 2017-04-19 10:00:46
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Emanuela Haller, Marius Leordeanu
mathjax: true
---

* content
{:toc}

##### Abstract
We address an essential problem in computer vision, that of unsupervised object segmentation in video, where a main object of interest in a video sequence should be automatically separated from its background. An efficient solution to this task would enable large-scale video interpretation at a high semantic level in the absence of the costly manually labeled ground truth. We propose an efficient unsupervised method for generating foreground object soft-segmentation masks based on automatic selection and learning from highly probable positive features. We show that such features can be selected efficiently by taking into consideration the spatio-temporal, appearance and motion consistency of the object during the whole observed sequence. We also emphasize the role of the contrasting properties between the foreground object and its background. Our model is created in two stages: we start from pixel level analysis, on top of which we add a regression model trained on a descriptor that considers information over groups of pixels and is both discriminative and invariant to many changes that the object undergoes throughout the video. We also present theoretical properties of our unsupervised learning method, that under some mild constraints is guaranteed to learn a correct discriminative classifier even in the unsupervised case. Our method achieves competitive and even state of the art results on the challenging Youtube-Objects and SegTrack datasets, while being at least one order of magnitude faster than the competition. We believe that the competitive performance of our method in practice, along with its theoretical properties, constitute an important step towards solving unsupervised discovery in video.

##### Abstract (translated by Google)
我们解决计算机视觉中的一个基本问题，即视频中的无监督对象分割，其中视频序列中的主要对象应自动与其背景分离。如果没有昂贵的手动标记的基本事实，这个任务的高效解决方案将能够在高语义水平上进行大规模的视频解释。我们提出了一种基于自动选择和高可能性正特征学习的高效无监督方法来生成前景物体软分割蒙版。我们证明，在整个观察序列中，考虑到对象的时空，外观和运动一致性，可以有效地选择这些特征。我们也强调了前景对象与其背景之间的对比性的作用。我们的模型建立在两个阶段：我们从像素级分析开始，在这个分析的基础上，我们增加了一个回归模型，该模型在一个描述符上进行训练，该描述符考虑像素组上的信息，并且对于对象经历的许多变化都是有区别的和不变的视频。我们还介绍了我们的无监督学习方法的理论性质，即使在无监督的情况下，在一些温和的约束下也保证学习正确的判别式分类器。我们的方法在具有挑战性的Youtube-Objects和SegTrack数据集上实现了最具竞争力和最先进的成果，同时比竞争对手至少快了一个数量级。我们相信，我们的方法在实践中的竞争性表现及其理论性质，是解决视频无监督发现的重要一步。

##### URL
[https://arxiv.org/abs/1704.05674](https://arxiv.org/abs/1704.05674)

##### PDF
[https://arxiv.org/pdf/1704.05674](https://arxiv.org/pdf/1704.05674)

