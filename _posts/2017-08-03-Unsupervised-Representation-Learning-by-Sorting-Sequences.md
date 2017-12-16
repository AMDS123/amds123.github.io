---
layout: post
title: "Unsupervised Representation Learning by Sorting Sequences"
date: 2017-08-03 17:51:38
categories: arXiv_CV
tags: arXiv_CV Object_Detection Action_Recognition CNN Image_Classification Represenation_Learning Classification Detection Recognition
author: Hsin-Ying Lee, Jia-Bin Huang, Maneesh Singh, Ming-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
We present an unsupervised representation learning approach using videos without semantic labels. We leverage the temporal coherence as a supervisory signal by formulating representation learning as a sequence sorting task. We take temporally shuffled frames (i.e., in non-chronological order) as inputs and train a convolutional neural network to sort the shuffled sequences. Similar to comparison-based sorting algorithms, we propose to extract features from all frame pairs and aggregate them to predict the correct order. As sorting shuffled image sequence requires an understanding of the statistical temporal structure of images, training with such a proxy task allows us to learn rich and generalizable visual representation. We validate the effectiveness of the learned representation using our method as pre-training on high-level recognition problems. The experimental results show that our method compares favorably against state-of-the-art methods on action recognition, image classification and object detection tasks.

##### Abstract (translated by Google)
我们提出了一个无监督的表示学习方法，使用没有语义标签的视频。将表示学习作为序列排序任务，利用时间相干性作为监督信号。我们采用时间上的混洗帧（即以非时间顺序）作为输入，并训练一个卷积神经网络来对混洗序列进行排序。与基于比较的排序算法类似，我们建议从所有帧对中提取特征并聚合它们以预测正确的顺序。由于排序混洗图像序列需要了解图像的统计时间结构，因此使用这种代理任务进行训练可以让我们学习丰富且可概括的视觉表示。我们使用我们的方法验证了学习表示的有效性，作为高级识别问题的预训练。实验结果表明，我们的方法在动作识别，图像分类和物体检测任务方面优于最先进的方法。

##### URL
[https://arxiv.org/abs/1708.01246](https://arxiv.org/abs/1708.01246)

##### PDF
[https://arxiv.org/pdf/1708.01246](https://arxiv.org/pdf/1708.01246)

