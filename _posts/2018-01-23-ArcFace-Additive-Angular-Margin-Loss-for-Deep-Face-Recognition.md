---
layout: post
title: "ArcFace: Additive Angular Margin Loss for Deep Face Recognition"
date: 2018-01-23 18:39:19
categories: arXiv_CV
tags: arXiv_CV Face CNN Recognition Face_Recognition
author: Jiankang Deng, Jia Guo, Stefanos Zafeiriou
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks have significantly boosted the performance of face recognition in recent years due to its high capacity in learning discriminative features. To enhance the discriminative power of the Softmax loss, multiplicative angular margin and additive cosine margin incorporate angular margin and cosine margin into the loss functions, respectively. In this paper, we propose a novel supervisor signal, additive angular margin (ArcFace), which has a better geometrical interpretation than supervision signals proposed so far. Specifically, the proposed ArcFace $\cos(\theta + m)$ directly maximise decision boundary in angular (arc) space based on the L2 normalised weights and features. Compared to multiplicative angular margin $\cos(m\theta)$ and additive cosine margin $\cos\theta-m$, ArcFace can obtain more discriminative deep features. We also emphasise the importance of network settings and data refinement in the problem of deep face recognition. Extensive experiments on several relevant face recognition benchmarks, LFW, CFP and AgeDB, prove the effectiveness of the proposed ArcFace. Most importantly, we get state-of-art performance in the MegaFace Challenge in a totally reproducible way. We make data, models and training/test code public available~\footnote{https://github.com/deepinsight/insightface}.

##### Abstract (translated by Google)
卷积神经网络由于其在识别特征方面的高容量，近年来显着地提高了人脸识别的性能。为了提高Softmax损失的判别能力，乘法角​​边界和加性余弦边界分别包含角边界和余弦边界到损失函数中。在本文中，我们提出了一个新的监督信号，加角边缘（ArcFace），它具有比迄今为止提出的监督信号更好的几何解释。具体来说，基于L2归一化权重和特征，所提出的ArcFace $ \ cos（\ theta + m）$直接最大化角（弧）空间中的决策边界。与乘法角边界$ \ cos（m \θ）$和加余弦余量$ \ cos \ theta-m $相比，ArcFace可以获得更多的判别深度特征。我们也强调网络设置和数​​据精化在深度人脸识别问题上的重要性。在几个相关的人脸识别基准LFW，CFP和AgeDB上进行了大量的实验，证明了所提出的ArcFace的有效性。最重要的是，我们在MegaFace挑战赛中以完全可重复的方式获得了最先进的表现。我们将数据，模型和培训/测试代码公开发布到〜\ footnote {https://github.com/deepinsight/insightface}。

##### URL
[http://arxiv.org/abs/1801.07698](http://arxiv.org/abs/1801.07698)

##### PDF
[http://arxiv.org/pdf/1801.07698](http://arxiv.org/pdf/1801.07698)

