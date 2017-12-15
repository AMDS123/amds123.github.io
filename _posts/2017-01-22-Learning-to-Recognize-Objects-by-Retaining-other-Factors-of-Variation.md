---
layout: post
title: "Learning to Recognize Objects by Retaining other Factors of Variation"
date: 2017-01-22 23:56:42
categories: arXiv_CV
tags: arXiv_CV Classification Recognition
author: Jiaping Zhao, Chin-kai Chang, Laurent Itti
mathjax: true
---

* content
{:toc}

##### Abstract
Natural images are generated under many factors, including shape, pose, illumination etc. Most existing ConvNets formulate object recognition from natural images as a single task classification problem, and attempt to learn features useful for object categories, but invariant to other factors of variation as much as possible. These architectures do not explicitly learn other factors, like pose and lighting, instead, they usually discard them by pooling and normalization. In this work, we take the opposite approach: we train ConvNets for object recognition by retaining other factors (pose in our case) and learn them jointly with object category. We design a new multi-task leaning (MTL) ConvNet, named disentangling CNN (disCNN), which explicitly enforces the disentangled representations of object identity and pose, and is trained to predict object categories and pose transformations. We show that disCNN achieves significantly better object recognition accuracies than AlexNet trained solely to predict object categories on the iLab-20M dataset, which is a large scale turntable dataset with detailed object pose and lighting information. We further show that the pretrained disCNN/AlexNet features on iLab- 20M generalize to object recognition on both Washington RGB-D and ImageNet datasets, and the pretrained disCNN features are significantly better than the pretrained AlexNet features for fine-tuning object recognition on the ImageNet dataset.

##### Abstract (translated by Google)
自然图像是在很多因素的作用下产生的，包括形状，姿态，照度等。大多数现有的ConvNets将自然图像中的物体识别作为一个单一的任务分类问题，试图学习对物体类别有用的特征，而不是其他因素的变化尽可能多。这些架构没有明确地学习其他因素，如姿势和照明，而是通常通过池化和规范化来抛弃它们。在这项工作中，我们采取相反的方法：我们通过保留其他因素（在我们的例子中构成）来训练ConvNets进行对象识别，并与对象类别一起学习。我们设计了一个新的多任务学习（Multi-Task Leaning，简称MTL）ConvNet，命名为CNN（disCNN），它明确地强化了对象身份和姿态的解构表示，并且训练了对象类别和姿态变换的预测。我们展示disCNN实现了显着更好的对象识别精度比AlexNet训练完全预测iLab-20M数据集，这是一个大型的转盘数据集与详细的对象的姿势和照明信息的对象类别。我们进一步表明，iLab-20M上的预训练的disCNN / AlexNet特性推广到华盛顿RGB-D和ImageNet数据集上的对象识别，并且预训练的disCNN特征明显优于用于在ImageNet上微调对象识别的预训练AlexNet特征数据集。

##### URL
[https://arxiv.org/abs/1607.05851](https://arxiv.org/abs/1607.05851)

##### PDF
[https://arxiv.org/pdf/1607.05851](https://arxiv.org/pdf/1607.05851)

