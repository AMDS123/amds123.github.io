---
layout: post
title: "Automatically tracking neurons in a moving and deforming brain"
date: 2016-10-14 18:51:30
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN Tracking
author: Jeffrey P. Nguyen, Ashley N. Linder, George S. Plummer, Joshua W. Shaevitz, Andrew M. Leifer
mathjax: true
---

* content
{:toc}

##### Abstract
Advances in optical neuroimaging techniques now allow neural activity to be recorded with cellular resolution in awake and behaving animals. Brain motion in these recordings pose a unique challenge. The location of individual neurons must be tracked in 3D over time to accurately extract single neuron activity traces. Recordings from small invertebrates like C. elegans are especially challenging because they undergo very large brain motion and deformation during animal movement. Here we present an automated computer vision pipeline to reliably track populations of neurons with single neuron resolution in the brain of a freely moving C. elegans undergoing large motion and deformation. 3D volumetric fluorescent images of the animal's brain are straightened, aligned and registered, and the locations of neurons in the images are found via segmentation. Each neuron is then assigned an identity using a new time-independent machine-learning approach we call Neuron Registration Vector Encoding. In this approach, non-rigid point-set registration is used to match each segmented neuron in each volume with a set of reference volumes taken from throughout the recording. The way each neuron matches with the references defines a feature vector which is clustered to assign an identity to each neuron in each volume. Finally, thin-plate spline interpolation is used to correct errors in segmentation and check consistency of assigned identities. The Neuron Registration Vector Encoding approach proposed here is uniquely well suited for tracking neurons in brains undergoing large deformations. When applied to whole-brain calcium imaging recordings in freely moving C. elegans, this analysis pipeline located 150 neurons for the duration of an 8 minute recording and consistently found more neurons more quickly than manual or semi-automated approaches.

##### Abstract (translated by Google)
光学神经成像技术的进步现在允许神经活动记录在清醒和行为动物的细胞分辨率。这些录音中的大脑运动构成了独特的挑战。每个神经元的位置必须随着时间的推移以三维方式进行追踪，以准确提取单个神经元活动的轨迹。像线虫这样的小型无脊椎动物的记录尤其具有挑战性，因为它们在动物运动期间经历非常大的大脑运动和变形。在这里，我们提出了一个自动化的计算机视觉管道，以可靠地跟踪在自由移动的线虫经历大的运动和变形的大脑中的单个神经元的分辨率的神经元的人口。对动物大脑的三维体积荧光图像进行校正，对齐和记录，并通过分割找到图像中神经元的位置。然后使用新的时间独立的机器学习方法为每个神经元分配身份，我们称之为神经元注册向量编码。在这种方法中，使用非刚性点集注册将每个体积中的每个分段神经元与从整个记录中获取的一组参考体积进行匹配。每个神经元与参考相匹配的方式定义了一个特征向量，这个特征向量被聚类来为每个体积中的每个神经元分配一个标识。最后，使用薄板样条插值来纠正分割中的错误并检查分配的身份的一致性。这里提出的神经元配准矢量编码方法非常适合跟踪大脑变形的神经元。当应用于自由移动的线虫中的全脑钙成像记录时，该分析管线在8分钟的记录期间定位150个神经元，并且一直比人工或半自动方法更快地发现更多的神经元。

##### URL
[https://arxiv.org/abs/1610.04579](https://arxiv.org/abs/1610.04579)

##### PDF
[https://arxiv.org/pdf/1610.04579](https://arxiv.org/pdf/1610.04579)

