---
layout: post
title: "Transitive Invariance for Self-supervised Visual Representation Learning"
date: 2017-08-15 02:34:50
categories: arXiv_CV
tags: arXiv_CV Object_Detection GAN Face Represenation_Learning Detection Recognition
author: Xiaolong Wang, Kaiming He, Abhinav Gupta
mathjax: true
---

* content
{:toc}

##### Abstract
Learning visual representations with self-supervised learning has become popular in computer vision. The idea is to design auxiliary tasks where labels are free to obtain. Most of these tasks end up providing data to learn specific kinds of invariance useful for recognition. In this paper, we propose to exploit different self-supervised approaches to learn representations invariant to (i) inter-instance variations (two objects in the same class should have similar features) and (ii) intra-instance variations (viewpoint, pose, deformations, illumination, etc). Instead of combining two approaches with multi-task learning, we argue to organize and reason the data with multiple variations. Specifically, we propose to generate a graph with millions of objects mined from hundreds of thousands of videos. The objects are connected by two types of edges which correspond to two types of invariance: "different instances but a similar viewpoint and category" and "different viewpoints of the same instance". By applying simple transitivity on the graph with these edges, we can obtain pairs of images exhibiting richer visual invariance. We use this data to train a Triplet-Siamese network with VGG16 as the base architecture and apply the learned representations to different recognition tasks. For object detection, we achieve 63.2% mAP on PASCAL VOC 2007 using Fast R-CNN (compare to 67.3% with ImageNet pre-training). For the challenging COCO dataset, our method is surprisingly close (23.5%) to the ImageNet-supervised counterpart (24.4%) using the Faster R-CNN framework. We also show that our network can perform significantly better than the ImageNet network in the surface normal estimation task.

##### Abstract (translated by Google)
学习视觉表现与自我监督学习已成为计算机视觉中的流行。这个想法是设计标签可以自由获得的辅助任务。大多数这些任务最终提供的数据来学习特定类型的不变性有用的识别。在本文中，我们提出利用不同的自我监督的方法来学习不变的（i）实例间的变化（同一类中的两个对象应该具有相似的特征）和（ii）实例内变化（视点，姿态，变形，照明等）。我们不是将两种方法与多任务学习相结合，而是将多种变化的数据进行组织和推理。具体来说，我们建议生成一个包含数百万个视频数百万个对象的图表。这些对象通过对应于两种不变性的两种类型的边缘连接：“不同的实例，但是相似的视点和类别”以及“同一实例的不同的视点”。通过在具有这些边的图上应用简单的传递性，我们可以获得具有更丰富的视觉不变性的图像对。我们使用这些数据来训练一个以VGG16为基础架构的Triplet-Siamese网络，并将学习的表示应用于不同的识别任务。对于物体检测，我们使用Fast R-CNN在PASCAL VOC 2007上获得63.2％的mAP（与ImageNet预训练相比，为67.3％）。对于具有挑战性的COCO数据集，我们的方法使用更快的R-CNN框架令人惊讶地接近ImageNet监督对象（24.4％）（23.5％）。我们还表明，我们的网络在表面正常估计任务中可以比ImageNet网络表现得更好。

##### URL
[https://arxiv.org/abs/1708.02901](https://arxiv.org/abs/1708.02901)

##### PDF
[https://arxiv.org/pdf/1708.02901](https://arxiv.org/pdf/1708.02901)

