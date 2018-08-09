---
layout: post
title: "A Semi-Supervised Data Augmentation Approach using 3D Graphical Engines"
date: 2018-08-08 01:48:38
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Tracking Deep_Learning
author: Shuangjun Liu, Sarah Ostadabbas
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning approaches have been rapidly adopted across a wide range of fields because of their accuracy and flexibility, but require large labeled training datasets. This presents a fundamental problem for applications with limited, expensive, or private data (i.e. small data), such as human pose and behavior estimation/tracking which could be highly personalized. In this paper, we present a semi-supervised data augmentation approach that can synthesize large scale labeled training datasets using 3D graphical engines based on a physically-valid low dimensional pose descriptor. To evaluate the performance of our synthesized datasets in training deep learning-based models, we generated a large synthetic human pose dataset, called ScanAva using 3D scans of only 7 individuals based on our proposed augmentation approach. A state-of-the-art human pose estimation deep learning model then was trained from scratch using our ScanAva dataset and could achieve the pose estimation accuracy of 91.2% at PCK0.5 criteria after applying an efficient domain adaptation on the synthetic images, in which its pose estimation accuracy was comparable to the same model trained on large scale pose data from real humans such as MPII dataset and much higher than the model trained on other synthetic human dataset such as SURREAL.

##### Abstract (translated by Google)
由于其准确性和灵活性，深度学习方法已在各个领域迅速采用，但需要大型标记的训练数据集。这为具有有限的，昂贵的或私人数据（即小数据）的应用提出了基本问题，例如人体姿势和行为估计/跟踪，其可以是高度个性化的。在本文中，我们提出了一种半监督数据增强方法，该方法可以使用基于物理上有效的低维度姿态描述符的3D图形引擎来合成大规模标记的训练数据集。为了评估我们的合成数据集在训练基于深度学习的模型中的表现，我们基于我们提出的增强方法，使用仅7个人的3D扫描生成了一个大型合成人体姿势数据集，称为ScanAva。然后使用我们的ScanAva数据集从头开始训练最先进的人体姿势估计深度学习模型，并且在对合成图像应用有效域自适应之后，可以在PCK0.5标准下实现91.2％的姿势估计精度。其姿势估计精度与来自真人（例如MPII数据集）的大规模姿势数据训练的相同模型相当，并且远高于在其他合成人类数据集（例如SURREAL）上训练的模型。

##### URL
[http://arxiv.org/abs/1808.02595](http://arxiv.org/abs/1808.02595)

##### PDF
[http://arxiv.org/pdf/1808.02595](http://arxiv.org/pdf/1808.02595)

