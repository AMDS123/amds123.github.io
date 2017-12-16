---
layout: post
title: "Pose from Action: Unsupervised Learning of Pose Features based on Motion"
date: 2016-09-18 04:18:42
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Action_Recognition Recognition
author: Senthil Purushwalkam, Abhinav Gupta
mathjax: true
---

* content
{:toc}

##### Abstract
Human actions are comprised of a sequence of poses. This makes videos of humans a rich and dense source of human poses. We propose an unsupervised method to learn pose features from videos that exploits a signal which is complementary to appearance and can be used as supervision: motion. The key idea is that humans go through poses in a predictable manner while performing actions. Hence, given two poses, it should be possible to model the motion that caused the change between them. We represent each of the poses as a feature in a CNN (Appearance ConvNet) and generate a motion encoding from optical flow maps using a separate CNN (Motion ConvNet). The data for this task is automatically generated allowing us to train without human supervision. We demonstrate the strength of the learned representation by finetuning the trained model for Pose Estimation on the FLIC dataset, for static image action recognition on PASCAL and for action recognition in videos on UCF101 and HMDB51.

##### Abstract (translated by Google)
人的行为是由一系列的姿势组成的。这使人类的视频成为丰富而密集的人体姿态。我们提出了一种无监督的方法来从视频中学习姿态特征，这些视频利用了与外观互补的信号，并且可以用作监督：运​​动。关键的想法是人类在执行行动时以可预测的方式经历姿势。因此，给定两个姿势，应该可以模拟导致它们之间的变化的运动。我们将每个姿态表示为CNN（外观ConvNet）中的一个特征，并使用单独的CNN（Motion ConvNet）从光流映射生成运动编码。这个任务的数据是自动生成的，允许我们在没有人工监督的情况我们通过微调FLIC数据集上的姿态估计的训练模型，PASCAL上的静态图像动作识别以及UCF101和HMDB51上的视频中的动作识别来证明学习表示的强度。

##### URL
[https://arxiv.org/abs/1609.05420](https://arxiv.org/abs/1609.05420)

##### PDF
[https://arxiv.org/pdf/1609.05420](https://arxiv.org/pdf/1609.05420)

