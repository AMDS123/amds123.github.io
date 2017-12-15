---
layout: post
title: "Image Classification of Grapevine Buds using Scale-Invariant Features Transform, Bag of Features and Support Vector Machines"
date: 2016-05-09 20:48:20
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification Detection
author: Diego Sebastián Pérez, Facundo Bromberg, Carlos Ariel Diaz
mathjax: true
---

* content
{:toc}

##### Abstract
In viticulture, there are several applications where bud detection in vineyard images is a necessary task, susceptible of being automated through the use of computer vision methods. A common and effective family of visual detection algorithms are the scanning-window type, that slide a (usually) fixed size window along the original image, classifying each resulting windowed-patch as containing or not containing the target object. The simplicity of these algorithms finds its most challenging aspect in the classification stage. Interested in grapevine buds detection in natural field conditions, this paper presents a classification method for images of grapevine buds ranging 100 to 1600 pixels in diameter, captured in outdoor, under natural field conditions, in winter (i.e., no grape bunches, very few leaves, and dormant buds), without artificial background, and with minimum equipment requirements. The proposed method uses well-known computer vision technologies: Scale-Invariant Feature Transform for calculating low-level features, Bag of Features for building an image descriptor, and Support Vector Machines for training a classifier. When evaluated over images containing buds of at least 100 pixels in diameter, the approach achieves a recall higher than 0.9 and a precision of 0.86 over all windowed-patches covering the whole bud and down to 60% of it, and scaled up to window patches containing a proportion of 20%-80% of bud versus background pixels. This robustness on the position and size of the window demonstrates its viability for use as the classification stage in a scanning-window detection algorithms.

##### Abstract (translated by Google)
在葡萄栽培方面，葡萄园图像中的芽检测是一项必要的任务，易于通过使用计算机视觉方法自动化。视觉检测算法的一个常见和有效的家庭是扫描窗口类型，它沿着原始图像滑动（通常）固定大小的窗口，将每个产生的窗口化补丁分类为包含或不包含目标对象。这些算法的简单性在分类阶段找到了最具挑战性的方面。对自然田间条件下的葡萄芽检测技术感兴趣，本文提出了一种在室外，自然条件下，在冬季捕获的直径在100至1600像素之间的葡萄芽图像的分类方法（即无葡萄串，极少数叶，休眠芽），没有人为背景，并且设备要求最低。所提出的方法使用众所周知的计算机视觉技术：用于计算低级特征的尺度不变特征变换，用于构建图像描述符的特征包和用于训练分类器的支持向量机。当对包含至少100个像素直径的芽的图像进行评估时，所述方法在覆盖整个芽的所有窗口片上达到高于0.9的回忆率和0.86的精确度，并且降低到60％，并且放大到窗口片含有芽的20％-80％比例与背景像素的比例。这种对窗口位置和大小的鲁棒性证明了其在扫描窗口检测算法中用作分类阶段的可行性。

##### URL
[https://arxiv.org/abs/1605.02775](https://arxiv.org/abs/1605.02775)

##### PDF
[https://arxiv.org/pdf/1605.02775](https://arxiv.org/pdf/1605.02775)

