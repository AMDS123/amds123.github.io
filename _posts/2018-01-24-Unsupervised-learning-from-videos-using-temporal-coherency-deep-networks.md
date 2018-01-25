---
layout: post
title: "Unsupervised learning from videos using temporal coherency deep networks"
date: 2018-01-24 17:51:32
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Recognition
author: Carolina Redondo-Cabrera, Roberto J. L&#xf3;pez-Sastre
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we address the challenging problem of unsupervised learning from videos. Existing methods utilize the spatio-temporal continuity in contiguous video frames as regularization for the learning process. Typically, this temporal coherence of close frames is used as a free form of annotation, encouraging the learned representations to exhibit small differences between these frames. But this type of approach fails to capture the dissimilarity between videos with different content, hence learning less discriminative features. We here propose two Siamese architectures for Convolutional Neural Networks, and their corresponding novel loss functions, to learn from unlabeled videos, which jointly exploit the local temporal coherence between contiguous frames, and a global discriminative margin used to separate representations of different videos. An extensive experimental evaluation is presented, where we validate the proposed models on various tasks. First, we show how the learned features can be used to discover actions and scenes in video collections. Second, we show the benefits of such an unsupervised learning from just unlabeled videos, which can be directly used as a prior for the supervised recognition tasks of actions and objects in images, where our results further show that our features can even surpass a traditional and heavily supervised pre-training plus fine-tunning strategy.

##### Abstract (translated by Google)
在这项工作中，我们解决了视频无监督学习的挑战性问题。现有方法利用连续视频帧中的时空连续性作为学习过程的正则化。通常，关闭帧的时间相关性被用作注释的自由形式，鼓励学习表示在这些帧之间表现出小的差异。但是这种方法无法捕捉不同内容的视频之间的差异，因此学习的歧视性特征较少。我们在这里提出了两个卷积神经网络的连体体系结构及其相应的新损失函数，从联合利用连续帧之间的局部时间相干性的未标记视频学习，以及用于区分不同视频表示的全局判别式边缘。提出了一个广泛的实验评估，我们验证提出的各种任务模型。首先，我们展示如何使用学习的特征来发现视频集合中的动作和场景。其次，我们展示了这种无监督学习的好处，它可以直接用作图像中动作和对象的监督式识别任务的先验标记视频，我们的结果进一步表明，我们的特征甚至可以超越传统的严格监督的预训练加罚款策略。

##### URL
[http://arxiv.org/abs/1801.08100](http://arxiv.org/abs/1801.08100)

##### PDF
[http://arxiv.org/pdf/1801.08100](http://arxiv.org/pdf/1801.08100)

