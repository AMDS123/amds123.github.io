---
layout: post
title: "Curriculum Domain Adaptation for Semantic Segmentation of Urban Scenes"
date: 2018-06-05 20:21:52
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Prediction Relation
author: Yang Zhang, Philip David, Hassan Foroosh, Boqing Gong
mathjax: true
---

* content
{:toc}

##### Abstract
During the last half decade, convolutional neural networks (CNNs) have triumphed over semantic segmentation, which is one of the core tasks in many applications such as autonomous driving. However, to train CNNs requires a considerable amount of data, which is difficult to collect and laborious to annotate. Recent advances in computer graphics make it possible to train CNNs on photo-realistic synthetic imagery with computer-generated annotations. Despite this, the domain mismatch between the real images and the synthetic data cripples the models' performance. Hence, we propose a curriculum-style learning approach to minimize the domain gap in urban scenery semantic segmentation. The curriculum domain adaptation solves easy tasks first to infer necessary properties about the target domain; in particular, the first task is to learn global label distributions over images and local distributions over landmark superpixels. These are easy to estimate because images of urban scenes have strong idiosyncrasies (e.g., the size and spatial relations of buildings, streets, cars, etc.). We then train a segmentation network while regularizing its predictions in the target domain to follow those inferred properties. In experiments, our method outperforms the baselines on two datasets and two backbone networks. We also report extensive ablation studies about our approach.

##### Abstract (translated by Google)
在过去的五年中，卷积神经网络（CNN）取得了超过语义分割的胜利，这是许多应用程序（如自动驾驶）的核心任务之一。然而，为了培训CNN需要大量的数据，这些数据很难收集并且难以注释。计算机图形学的最新进展使得利用计算机生成的注释在照片般逼真的合成图像上训练CNN成为可能。尽管如此，真实图像和合成数据之间的域不匹配会削弱模型的性能。因此，我们提出了一种课程式的学习方法，以尽量减少城市景观语义分割领域的差距。课程领域适应首先解决简单的任务，以推断关于目标领域的必要属性;特别是，第一项任务是学习地标超像素上图像和本地分布的全局标签分布。由于城市场景的图像具有强烈的特质（例如，建筑物，街道，汽车等的大小和空间关系），因此这很容易估计。然后，我们训练一个分割网络，同时在目标领域中对其预测进行规范，以遵循那些推断的属性。在实验中，我们的方法胜过两个数据集和两个骨干网络的基线。我们还报告了我们的方法的广泛消融研究。

##### URL
[http://arxiv.org/abs/1707.09465](http://arxiv.org/abs/1707.09465)

##### PDF
[http://arxiv.org/pdf/1707.09465](http://arxiv.org/pdf/1707.09465)

