---
layout: post
title: "Indoor Frame Recovery from Refined Line Segments"
date: 2017-04-30 07:16:10
categories: arXiv_CV
tags: arXiv_CV
author: Luanzheng Guo, Jun Chu
mathjax: true
---

* content
{:toc}

##### Abstract
An important yet challenging problem in understanding indoor scene is recovering indoor frame structure from a monocular image. It is more difficult when occlusions and illumination vary, and object boundaries are weak. To overcome these difficulties, a new approach based on line segment refinement with two constraints is proposed. First, the line segments are refined by four consecutive operations, i.e., reclassifying, connecting, fitting, and voting. Specifically, misclassified line segments are revised by the reclassifying operation, some short line segments are joined by the connecting operation, the undetected key line segments are recovered by the fitting operation with the help of the vanishing points, the line segments converging on the frame are selected by the voting operation. Second, we construct four frame models according to four classes of possible shooting angles of the monocular image, the natures of all frame models are introduced via enforcing the cross ratio and depth constraints. The indoor frame is then constructed by fitting those refined line segments with related frame model under the two constraints, which jointly advance the accuracy of the frame. Experimental results on a collection of over 300 indoor images indicate that our algorithm has the capability of recovering the frame from complex indoor scenes.

##### Abstract (translated by Google)
了解室内场景的一个重要而又具有挑战性的问题是从单眼图像恢复室内的帧结构。当遮挡和光照变化，物体边界较弱时更困难。为克服这些困难，提出了一种基于线段细化和两种约束的新方法。首先，线段被连续四次操作完成，即重新分类，连接，拟合和投票。具体而言，通过重新分类操作来修改错误分类的线段，通过连接操作来连接一些短线段，借助于消失点通过拟合操作来恢复未检测到的关键线段，会聚在框架上的线段是由投票操作选中。其次，根据单眼图像的四种可能拍摄角度，构建四种框架模型，通过实施交叉比例和深度约束，引入所有框架模型的性质。然后通过在两个约束条件下将这些细化的线段与相关的框架模型进行拟合来构建室内框架，共同提高了框架的精度。实验结果表明，该算法具有从复杂的室内场景中恢复帧的能力。

##### URL
[https://arxiv.org/abs/1705.00279](https://arxiv.org/abs/1705.00279)

##### PDF
[https://arxiv.org/pdf/1705.00279](https://arxiv.org/pdf/1705.00279)

