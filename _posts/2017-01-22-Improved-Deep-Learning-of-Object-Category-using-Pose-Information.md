---
layout: post
title: "Improved Deep Learning of Object Category using Pose Information"
date: 2017-01-22 23:53:15
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Deep_Learning Prediction Gradient_Descent Recognition
author: Jiaping Zhao, Laurent Itti
mathjax: true
---

* content
{:toc}

##### Abstract
Despite significant recent progress, the best available computer vision algorithms still lag far behind human capabilities, even for recognizing individual discrete objects under various poses, illuminations, and backgrounds. Here we present a new approach to using object pose information to improve deep network learning. While existing large-scale datasets, e.g. ImageNet, do not have pose information, we leverage the newly published turntable dataset, iLab-20M, which has ~22M images of 704 object instances shot under different lightings, camera viewpoints and turntable rotations, to do more controlled object recognition experiments. We introduce a new convolutional neural network architecture, what/where CNN (2W-CNN), built on a linear-chain feedforward CNN (e.g., AlexNet), augmented by hierarchical layers regularized by object poses. Pose information is only used as feedback signal during training, in addition to category information; during test, the feedforward network only predicts category. To validate the approach, we train both 2W-CNN and AlexNet using a fraction of the dataset, and 2W-CNN achieves 6% performance improvement in category prediction. We show mathematically that 2W-CNN has inherent advantages over AlexNet under the stochastic gradient descent (SGD) optimization procedure. Further more, we fine-tune object recognition on ImageNet by using the pretrained 2W-CNN and AlexNet features on iLab-20M, results show that significant improvements have been achieved, compared with training AlexNet from scratch. Moreover, fine-tuning 2W-CNN features performs even better than fine-tuning the pretrained AlexNet features. These results show pretrained features on iLab- 20M generalizes well to natural image datasets, and 2WCNN learns even better features for object recognition than AlexNet.

##### Abstract (translated by Google)
尽管取得了显着的进步，但最好的计算机视觉算法仍然远远落后于人类的能力，即使是在各种姿势，照明和背景下识别各个离散物体。在这里我们提出一种新的方法来使用对象姿态信息来改善深度网络学习。虽然现有的大规模数据集，例如ImageNet，没有姿态信息，我们利用新发布的转台数据集iLab-20M，它具有在不同光照，摄像机视点和转盘旋转下拍摄的704个物体实例的〜22M图像，以进行更多的受控对象识别实验。我们引入了一种新的卷积神经网络结构，其中CNN（2W-CNN）建立在线性链前馈CNN（例如AlexNet）上，由以对象姿势规则化的分层结构增强。除了类别信息之外，姿势信息仅在训练期间用作反馈信号;在测试期间，前馈网络仅预测类别。为了验证该方法，我们使用一小部分数据集对2W-CNN和AlexNet进行了训练，2W-CNN在类别预测中的性能提高了6％。我们在数学上显示2W-CNN在随机梯度下降（SGD）优化过程下比AlexNet具有固有优势。此外，我们利用iLab-20M上的预训练的2W-CNN和AlexNet特性对ImageNet上的对象进行了微调，结果显示与从头开始训练AlexNet相比，已经有了显着的改进。而且，微调2W-CNN特性的表现甚至比对预训练的AlexNet特性进行微调更好。这些结果显示iLab-20M上的预训练特征能很好地推广到自然图像数据集，而2WCNN比AlexNet学习更好的物体识别特征。

##### URL
[https://arxiv.org/abs/1607.05836](https://arxiv.org/abs/1607.05836)

##### PDF
[https://arxiv.org/pdf/1607.05836](https://arxiv.org/pdf/1607.05836)

