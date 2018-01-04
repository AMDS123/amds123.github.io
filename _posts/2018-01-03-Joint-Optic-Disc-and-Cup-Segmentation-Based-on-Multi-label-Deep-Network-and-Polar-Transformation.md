---
layout: post
title: "Joint Optic Disc and Cup Segmentation Based on Multi-label Deep Network and Polar Transformation"
date: 2018-01-03 08:56:45
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning Prediction
author: Huazhu Fu, Jun Cheng, Yanwu Xu, Damon Wing Kee Wong, Jiang Liu, Xiaochun Cao
mathjax: true
---

* content
{:toc}

##### Abstract
Glaucoma is a chronic eye disease that leads to irreversible vision loss. The cup to disc ratio (CDR) plays an important role in the screening and diagnosis of glaucoma. Thus, the accurate and automatic segmentation of optic disc (OD) and optic cup (OC) from fundus images is a fundamental task. Most existing methods segment them separately, and rely on hand-crafted visual feature from fundus images. In this paper, we propose a deep learning architecture, named M-Net, which solves the OD and OC segmentation jointly in a one-stage multi-label system. The proposed M-Net mainly consists of multi-scale input layer, U-shape convolutional network, side-output layer, and multi-label loss function. The multi-scale input layer constructs an image pyramid to achieve multiple level receptive field sizes. The U-shape convolutional network is employed as the main body network structure to learn the rich hierarchical representation, while the side-output layer acts as an early classifier that produces a companion local prediction map for different scale layers. Finally, a multi-label loss function is proposed to generate the final segmentation map. For improving the segmentation performance further, we also introduce the polar transformation, which provides the representation of the original image in the polar coordinate system. The experiments show that our M-Net system achieves state-of-the-art OD and OC segmentation result on ORIGA dataset. Simultaneously, the proposed method also obtains the satisfactory glaucoma screening performances with calculated CDR value on both ORIGA and SCES datasets.

##### Abstract (translated by Google)
青光眼是导致不可逆转的视力丧失的慢性眼病。杯盘比（CDR）在青光眼的筛查和诊断中起着重要的作用。因此，从眼底图像准确自动地分割视盘（OD）和视杯（OC）是一项基本任务。大多数现有的方法将它们分开分开，并且依赖眼底图像的手工制作的视觉特征。在本文中，我们提出了一个名为M-Net的深度学习体系结构，它在一个一级多标签系统中共同解决了OD和OC分割问题。提出的M-Net主要由多尺度输入层，U形卷积网络，侧输出层和多标签丢失函数组成。多尺度输入层构建图像金字塔以实现多级接受字段大小。 U形卷积网络被用作主体网络结构来学习丰富的层次表示，而侧面输出层作为一个早期的分类器，为不同的尺度层产生伴随局部预测图。最后，提出了多标签损失函数来生成最终的分割图。为了进一步提高分割性能，我们还引入了极坐标变换，它提供了原始图像在极坐标系中的表示。实验表明，我们的M-Net系统在ORIGA数据集上实现了最新的OD和OC分割结果。同时，所提出的方法在ORIGA和SCES数据集上也获得令人满意的青光眼筛查性能，计算的CDR值。

##### URL
[http://arxiv.org/abs/1801.00926](http://arxiv.org/abs/1801.00926)

##### PDF
[http://arxiv.org/pdf/1801.00926](http://arxiv.org/pdf/1801.00926)

