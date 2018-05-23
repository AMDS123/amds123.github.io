---
layout: post
title: "OFF-ApexNet on Micro-expression Recognition System"
date: 2018-05-10 02:22:47
categories: arXiv_CV
tags: arXiv_CV CNN Classification Recognition
author: Sze-Teng Liong, Y.S. Gan, Wei-Chuen Yau, Yen-Chang Huang, Tan Lit Ken
mathjax: true
---

* content
{:toc}

##### Abstract
When a person attempts to conceal an emotion, the genuine emotion is manifest as a micro-expression. Exploration of automatic facial micro-expression recognition systems is relatively new in the computer vision domain. This is due to the difficulty in implementing optimal feature extraction methods to cope with the subtlety and brief motion characteristics of the expression. Most of the existing approaches extract the subtle facial movements based on hand-crafted features. In this paper, we address the micro-expression recognition task with a convolutional neural network (CNN) architecture, which well integrates the features extracted from each video. A new feature descriptor, Optical Flow Features from Apex frame Network (OFF-ApexNet) is introduced. This feature descriptor combines the optical ow guided context with the CNN. Firstly, we obtain the location of the apex frame from each video sequence as it portrays the highest intensity of facial motion among all frames. Then, the optical ow information are attained from the apex frame and a reference frame (i.e., onset frame). Finally, the optical flow features are fed into a pre-designed CNN model for further feature enhancement as well as to carry out the expression classification. To evaluate the effectiveness of OFF-ApexNet, comprehensive evaluations are conducted on three public spontaneous micro-expression datasets (i.e., SMIC, CASME II and SAMM). The promising recognition result suggests that the proposed method can optimally describe the significant micro-expression details. In particular, we report that, in a multi-database with leave-one-subject-out cross-validation experimental protocol, the recognition performance reaches 74.60% of recognition accuracy and F-measure of 71.04%. We also note that this is the first work that performs cross-dataset validation on three databases in this domain.

##### Abstract (translated by Google)
当一个人试图隐藏一种情感时，真正的情感就表现为一种微观表现。自动面部微型表情识别系统在计算机视觉领域的研究相对较新。这是因为难以实现最佳特征提取方法来处理表达的微妙和简短的运动特征。现有的大多数方法都是基于手工制作的特征提取微妙的面部运动。在本文中，我们用卷积神经网络（CNN）体系结构解决了微表达式识别任务，该任务将从每个视频中提取的特征很好地集成在一起。介绍一种新的特征描述符，即Apex帧网络（OFF-ApexNet）的光流特征。该特征描述符将光学引导上下文与CNN结合。首先，我们从每个视频序列中获取顶点帧的位置，因为它描绘了所有帧中面部运动的最高强度。然后，从顶点帧和参考帧（即起始帧）获得光学信息。最后，光流特征被馈送到预先设计的CNN模型中以进一步特征增强以及执行表达分类。为了评估OFF-ApexNet的有效性，对三个公共自发微表达数据集（即SMIC，CASME II和SAMM）进行了综合评估。有希望的识别结果表明所提出的方法可以最优地描述重要的微表达细节。具体来说，我们报告说，在一个带有假一主题交叉验证实验协议的多数据库中，识别性能达到识别准确度的74.60％，F-71.04％。我们还注意到，这是第一个对此域中的三个数据库执行跨数据集验证的工作。

##### URL
[https://arxiv.org/abs/1805.08699](https://arxiv.org/abs/1805.08699)

##### PDF
[https://arxiv.org/pdf/1805.08699](https://arxiv.org/pdf/1805.08699)

