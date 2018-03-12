---
layout: post
title: "Analysis of Hand Segmentation in the Wild"
date: 2018-03-08 21:45:07
categories: arXiv_CV
tags: arXiv_CV Segmentation Face Semantic_Segmentation Detection Recognition
author: Aisha Urooj Khan, Ali Borji
mathjax: true
---

* content
{:toc}

##### Abstract
A large number of works in egocentric vision have concentrated on action and object recognition. Detection and segmentation of hands in first person videos, however, has less been explored. For many applications in this domain, it is necessary to accurately segment not only hands of the camera wearer but also the hands of others with whom he is interacting. Here, we take an in-depth look at the hand segmentation problem. First, we evaluate the performance of the state of the art hand segmentation methods, off the shelf and finetuned, on existing datasets. Second, we finetune RefineNet, a leading semantic segmentation method, for hand segmentation and find that it does much better than best contenders. Third, we contribute by collecting two new datasets including a) EgoYouTubeHands dataset which includes egocentric videos containing hands in the wild, and b) HandOverFace dataset to analyze the performance of our models in presence of similar appearance occlusions. Fourth, we investigate whether conditional random fields can be helpful to refine hand segmentations produced by our model. Fifth, we train a CNN for hand-based activity recognition and achieve higher activity recognition accuracy when the trained CNN used hand maps produced by finetuned RefineNet model. Finally, we annotate a subset of the EgoHands dataset for fine-level activity recognition and show that just looking at a single hand pose, we can achieve 58.6% recognition accuracy where chance level is 12.5%.

##### Abstract (translated by Google)
大量的以自我为中心的作品都集中在动作和物体识别上。然而，第一人称视频中的手的检测和分割较少被探索。对于这个领域的许多应用，有必要精确地分割相机佩戴者的手，而且还要准确地分割他正在与之交互的其他人的手。在这里，我们深入研究手部分割问题。首先，我们评估现有数据集上现有技术的手部分割方法的性能，现成的和精细的。其次，我们对用于手部分割的领先的语义分割方法RefineNet进行了细调，并发现它比最好的竞争者要好得多。第三，我们通过收集两个新数据集做出贡献，包括a）EgoYouTubeHands数据集，其中包括在自然环境中包含双手的以自我为中心的视频，以及b）HandOverFace数据集，用于分析存在相似外观遮挡情况下我们模型的性能。第四，我们调查条件随机场是否有助于细化我们模型产生的手部分割。第五，当训练有素的CNN使用由微调的RefineNet模型生成的手图时，我们训练一个用于手动活动识别的CNN并获得更高的活动识别准确性。最后，我们对EgoHands数据集的一个子集进行了注释，以便进行精细级别的活动识别，并且只显示单手姿势，当机会级别为12.5％时，我们可以实现58.6％的识别准确性。

##### URL
[http://arxiv.org/abs/1803.03317](http://arxiv.org/abs/1803.03317)

##### PDF
[http://arxiv.org/pdf/1803.03317](http://arxiv.org/pdf/1803.03317)

