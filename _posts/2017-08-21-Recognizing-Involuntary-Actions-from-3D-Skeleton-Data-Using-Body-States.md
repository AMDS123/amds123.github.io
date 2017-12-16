---
layout: post
title: "Recognizing Involuntary Actions from 3D Skeleton Data Using Body States"
date: 2017-08-21 13:59:53
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Classification Recognition
author: Mozhgan Mokari, Hoda Mohammadzade, Benyamin Ghojogh
mathjax: true
---

* content
{:toc}

##### Abstract
Human action recognition has been one of the most active fields of research in computer vision for last years. Two dimensional action recognition methods are facing serious challenges such as occlusion and missing the third dimension of data. Development of depth sensors has made it feasible to track positions of human body joints over time. This paper proposes a novel method of action recognition which uses temporal 3D skeletal Kinect data. This method introduces the definition of body states and then every action is modeled as a sequence of these states. The learning stage uses Fisher Linear Discriminant Analysis (LDA) to construct discriminant feature space for discriminating the body states. Moreover, this paper suggests the use of the Mahalonobis distance as an appropriate distance metric for the classification of the states of involuntary actions. Hidden Markov Model (HMM) is then used to model the temporal transition between the body states in each action. According to the results, this method significantly outperforms other popular methods, with recognition rate of 88.64% for eight different actions and up to 96.18% for classifying fall actions.

##### Abstract (translated by Google)
近年来，人类行为识别一直是计算机视觉领域最活跃的研究领域之一。二维动作识别方法面临严重的挑战，如遮挡和缺失数据的第三维。随着时间的推移，深度传感器的发展使得跟踪人体关节的位置成为可能。本文提出了一种使用时间三维骨骼Kinect数据的动作识别新方法。这种方法引入了身体状态的定义，然后将每个行为建模为这些状态的一个序列。学习阶段采用Fisher线性判别分析（LDA）构造区分身体状态的判别特征空间。此外，本文建议使用Mahalonobis距离作为非自愿行为状态分类的适当距离度量。然后使用隐马尔可夫模型（HMM）来模拟每个动作中身体状态之间的时间转换。结果显示，该方法明显优于其他流行的方法，对8种不同的行为的识别率为88.64％，对跌倒行为的分类识别率高达96.18％。

##### URL
[https://arxiv.org/abs/1708.06227](https://arxiv.org/abs/1708.06227)

##### PDF
[https://arxiv.org/pdf/1708.06227](https://arxiv.org/pdf/1708.06227)

