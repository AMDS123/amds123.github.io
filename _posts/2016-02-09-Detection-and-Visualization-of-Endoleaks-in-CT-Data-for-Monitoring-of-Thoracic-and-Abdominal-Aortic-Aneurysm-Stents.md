---
layout: post
title: "Detection and Visualization of Endoleaks in CT Data for Monitoring of Thoracic and Abdominal Aortic Aneurysm Stents"
date: 2016-02-09 07:42:05
categories: arXiv_CV
tags: arXiv_CV Segmentation Detection
author: Jing Lu, Jan Egger, Andreas Wimmer, Stefan Großkopf, Bernd Freisleben
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present an efficient algorithm for the segmentation of the inner and outer boundary of thoratic and abdominal aortic aneurysms (TAA & AAA) in computed tomography angiography (CTA) acquisitions. The aneurysm segmentation includes two steps: first, the inner boundary is segmented based on a grey level model with two thresholds; then, an adapted active contour model approach is applied to the more complicated outer boundary segmentation, with its initialization based on the available inner boundary segmentation. An opacity image, which aims at enhancing important features while reducing spurious structures, is calculated from the CTA images and employed to guide the deformation of the model. In addition, the active contour model is extended by a constraint force that prevents intersections of the inner and outer boundary and keeps the outer boundary at a distance, given by the thrombus thickness, to the inner boundary. Based upon the segmentation results, we can measure the aneurysm size at each centerline point on the centerline orthogonal multiplanar reformatting (MPR) plane. Furthermore, a 3D TAA or AAA model is reconstructed from the set of segmented contours, and the presence of endoleaks is detected and highlighted. The implemented method has been evaluated on nine clinical CTA data sets with variations in anatomy and location of the pathology and has shown promising results.

##### Abstract (translated by Google)
在本文中，我们提出了一个有效的算法分割的内部和外部的边界的胸腹主动脉瘤（TAA和AAA）的计算机断层扫描血管造影（CTA）收购。动脉瘤分割包括两个步骤：首先，根据具有两个阈值的灰度级模型对内边界进行分割;然后将适应的主动轮廓模型方法应用于更复杂的外边界分割，并基于可用的内边界分割进行初始化。一个不透明的图像，旨在增强重要特征，同时减少伪结构，计算从CTA图像，并用于指导模型的变形。此外，活动轮廓模型通过一个约束力来扩展，该约束力防止内部和外部边界的交叉，并且将外部边界保持在由血栓厚度给定的距离处到内部边界。根据分割结果，我们可以测量中心线正交多平面重组（MPR）平面上每个中心点的动脉瘤大小。此外，从一组分割的轮廓重建3D TAA或AAA模型，并检测并突出显示内漏的存在。所实施的方法已经在九个临床CTA数据集上进行了评估，这些数据集具有不同的解剖学和病理学位置，并且已经显示出有希望的结果。

##### URL
[https://arxiv.org/abs/1602.02881](https://arxiv.org/abs/1602.02881)

##### PDF
[https://arxiv.org/pdf/1602.02881](https://arxiv.org/pdf/1602.02881)

