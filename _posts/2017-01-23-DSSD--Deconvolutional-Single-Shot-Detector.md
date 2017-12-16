---
layout: post
title: "DSSD : Deconvolutional Single Shot Detector"
date: 2017-01-23 22:33:35
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Cheng-Yang Fu, Wei Liu, Ananth Ranga, Ambrish Tyagi, Alexander C. Berg
mathjax: true
---

* content
{:toc}

##### Abstract
The main contribution of this paper is an approach for introducing additional context into state-of-the-art general object detection. To achieve this we first combine a state-of-the-art classifier (Residual-101[14]) with a fast detection framework (SSD[18]). We then augment SSD+Residual-101 with deconvolution layers to introduce additional large-scale context in object detection and improve accuracy, especially for small objects, calling our resulting system DSSD for deconvolutional single shot detector. While these two contributions are easily described at a high-level, a naive implementation does not succeed. Instead we show that carefully adding additional stages of learned transformations, specifically a module for feed-forward connections in deconvolution and a new output module, enables this new approach and forms a potential way forward for further detection research. Results are shown on both PASCAL VOC and COCO detection. Our DSSD with $513 \times 513$ input achieves 81.5% mAP on VOC2007 test, 80.0% mAP on VOC2012 test, and 33.2% mAP on COCO, outperforming a state-of-the-art method R-FCN[3] on each dataset.

##### Abstract (translated by Google)
本文的主要贡献是将附加上下文引入到最先进的通用对象检测中。为了实现这个目标，我们首先将一个最先进的分类器（Residual-101 [14]）与一个快速检测框架（SSD [18]）结合起来。然后，我们用解卷积层来增加SSD +残差-101，以便在物体检测中引入更多的大规模上下文，并提高精度，特别是对于小物体，称之为解卷积单探测器的结果系统DSSD。虽然这两个贡献很容易被高层描述，但天真的实现并不成功。相反，我们表明，仔细增加额外的学习转换阶段，特别是反卷积中的前馈连接模块和新的输出模块，使这种新的方法，并形成一个潜在的方式，进一步的检测研究。结果显示在PASCAL VOC和COCO检测上。我们的DSSD以513美元/次513美元的投入在VOC2007测试中达到了81.5％的mAP，在VOC2012测试中达到了80.0％的mAP，在COCO上达到了33.2％的mAP，在每个数据集上都超过了最先进的方法R-FCN [3] 。

##### URL
[https://arxiv.org/abs/1701.06659](https://arxiv.org/abs/1701.06659)

##### PDF
[https://arxiv.org/pdf/1701.06659](https://arxiv.org/pdf/1701.06659)

