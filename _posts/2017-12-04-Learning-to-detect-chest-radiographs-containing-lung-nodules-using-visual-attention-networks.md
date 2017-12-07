---
layout: post
title: "Learning to detect chest radiographs containing lung nodules using visual attention networks"
date: 2017-12-04 10:44:32
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning CNN Detection
author: Emanuele Pesce, Petros-Pavlos Ypsilantis, Samuel Withey, Robert Bakewell, Vicky Goh, Giovanni Montana
mathjax: true
---

* content
{:toc}

##### Abstract
Machine learning approaches hold great potential for the automated detection of lung nodules in chest radiographs, but training the algorithms requires vary large amounts of manually annotated images, which are difficult to obtain. Weak labels indicating whether a radiograph is likely to contain pulmonary nodules are typically easier to obtain at scale by parsing historical free-text radiological reports associated to the radiographs. Using a repositotory of over 700,000 chest radiographs, in this study we demonstrate that promising nodule detection performance can be achieved using weak labels through convolutional neural networks for radiograph classification. We propose two network architectures for the classification of images likely to contain pulmonary nodules using both weak labels and manually-delineated bounding boxes, when these are available. Annotated nodules are used at training time to deliver a visual attention mechanism informing the model about its localisation performance. The first architecture extracts saliency maps from high-level convolutional layers and compares the estimated position of a nodule against the ground truth, when this is available. A corresponding localisation error is then back-propagated along with the softmax classification error. The second approach consists of a recurrent attention model that learns to observe a short sequence of smaller image portions through reinforcement learning. When a nodule annotation is available at training time, the reward function is modified accordingly so that exploring portions of the radiographs away from a nodule incurs a larger penalty. Our empirical results demonstrate the potential advantages of these architectures in comparison to competing methodologies.

##### Abstract (translated by Google)
机器学习方法对于胸部X光片中的肺结节的自动检测具有很大的潜力，但是训练算法需要大量的手动注释的图像，这很难获得。指示X光片是否可能包含肺结节的弱标记通常通过解析与X光片相关的历史自由文本放射学报告来更容易地获得。在这项研究中，我们使用超过700,000张胸部X光片的储存库，证明使用弱标签通过用于X光照片分类的卷积神经网络可以实现有希望的结节检测性能。我们提出了两种网络体系结构，用于可能包含肺部结节的图像的分类，使用弱标签和手动划定的边界框。在训练时使用注释结节来提供视觉注意机制，以通知模型关于其定位性能。第一种体系结构从高级卷积层中提取显着图，并在可用时比较结核的估计位置与地面实况。相应的定位误差随后与softmax分类错误一起反向传播。第二种方法包括反复注意模式，通过强化学习学习观察较短的图像部分序列。当在训练时可获得结节注释时，奖励函数会相应地进行修改，以便探查远离结节的射线照片部分将受到较大的惩罚。我们的实证结果表明，与竞争方法相比，这些体系结构的潜在优势。

##### URL
[http://arxiv.org/abs/1712.00996](http://arxiv.org/abs/1712.00996)

##### PDF
[http://arxiv.org/pdf/1712.00996](http://arxiv.org/pdf/1712.00996)

