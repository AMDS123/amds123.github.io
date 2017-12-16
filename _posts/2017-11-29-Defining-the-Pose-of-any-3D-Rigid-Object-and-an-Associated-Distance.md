---
layout: post
title: "Defining the Pose of any 3D Rigid Object and an Associated Distance"
date: 2017-11-29 14:10:04
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation
author: Romain Brégier, Frédéric Devernay, Laetitia Leyrit, James Crowley
mathjax: true
---

* content
{:toc}

##### Abstract
The pose of a rigid object is usually regarded as a rigid transformation, described by a translation and a rotation. However, equating the pose space with the space of rigid transformations is in general abusive, as it does not account for objects with proper symmetries -- which are common among man-made objects.In this article, we define pose as a distinguishable static state of an object, and equate a pose with a set of rigid transformations. Based solely on geometric considerations, we propose a frame-invariant metric on the space of possible poses, valid for any physical rigid object, and requiring no arbitrary tuning. This distance can be evaluated efficiently using a representation of poses within an Euclidean space of at most 12 dimensions depending on the object's symmetries. This makes it possible to efficiently perform neighborhood queries such as radius searches or k-nearest neighbor searches within a large set of poses using off-the-shelf methods. Pose averaging considering this metric can similarly be performed easily, using a projection function from the Euclidean space onto the pose space. The practical value of those theoretical developments is illustrated with an application of pose estimation of instances of a 3D rigid object given an input depth map, via a Mean Shift procedure.

##### Abstract (translated by Google)
一个刚体的姿态通常被认为是一个刚性的转换，由一个平移和一个旋转来描述。然而，将姿态空间等同于刚性变换的空间一般是滥用的，因为它没有考虑具有适当对称性的物体 - 这在人造物体中是常见的。在本文中，我们将姿势定义为可区分的静态的一个对象，并将一个姿势与一组刚性变换等同起来。仅基于几何考虑，我们提出了一个框架不变的度量空间的可能姿态，有效的任何物理刚体，并且不需要任意的调整。这个距离可以根据对象的对称性使用在至多12维的欧几里德空间内的姿态表示来有效地评估。这使得使用现成的方法有效地执行诸如半径搜索或k个最近邻搜索的邻域查询成为可能。使用从欧几里德空间到姿态空间的投影函数，考虑到这个度量的姿态平均可以类似地容易地执行。这些理论发展的实际价值是通过应用通过Mean Shift程序给定输入深度图的3D刚体的实例的姿态估计来应用的。

##### URL
[https://arxiv.org/abs/1612.04631](https://arxiv.org/abs/1612.04631)

##### PDF
[https://arxiv.org/pdf/1612.04631](https://arxiv.org/pdf/1612.04631)

