---
layout: post
title: "A Novel Disparity Transformation Algorithm for Road Segmentation"
date: 2018-08-08 15:50:22
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Rui Fan, Mohammud Junaid Bocus, Naim Dahnoun
mathjax: true
---

* content
{:toc}

##### Abstract
The disparity information provided by stereo cameras has enabled advanced driver assistance systems to estimate road area more accurately and effectively. In this paper, a novel disparity transformation algorithm is proposed to extract road areas from dense disparity maps by making the disparity value of the road pixels become similar. The transformation is achieved using two parameters: roll angle and fitted disparity value with respect to each row. To achieve a better processing efficiency, golden section search and dynamic programming are utilised to estimate the roll angle and the fitted disparity value, respectively. By performing a rotation around the estimated roll angle, the disparity distribution of each row becomes very compact. This further improves the accuracy of the road model estimation, as demonstrated by the various experimental results in this paper. Finally, the Otsu's thresholding method is applied to the transformed disparity map and the roads can be accurately segmented at pixel level.

##### Abstract (translated by Google)
立体摄像机提供的视差信息使高级驾驶员辅助系统能够更准确和有效地估计道路区域。本文提出了一种新的视差变换算法，通过使道路像素的视差值相似，从密集视差图中提取道路区域。使用两个参数实现变换：相对于每行的滚动角和拟合视差值。为了获得更好的处理效率，利用黄金分割搜索和动态编程分别估计滚动角和拟合视差值。通过围绕估计的侧倾角执行旋转，每行的视差分布变得非常紧凑。这进一步提高了道路模型估计的准确性，正如本文中的各种实验结果所证明的那样。最后，将Otsu的阈值处理方法应用于变换后的视差图，并且可以在像素级精确地分割道路。

##### URL
[http://arxiv.org/abs/1808.02837](http://arxiv.org/abs/1808.02837)

##### PDF
[http://arxiv.org/pdf/1808.02837](http://arxiv.org/pdf/1808.02837)

