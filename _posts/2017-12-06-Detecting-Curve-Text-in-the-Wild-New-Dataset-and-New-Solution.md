---
layout: post
title: "Detecting Curve Text in the Wild: New Dataset and New Solution"
date: 2017-12-06 13:02:43
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Liu Yuliang, Jin Lianwen, Zhang Shuaitao, Zhang Sheng
mathjax: true
---

* content
{:toc}

##### Abstract
Scene text detection has been made great progress in recent years. The detection manners are evolving from axis-aligned rectangle to rotated rectangle and further to quadrangle. However, current datasets contain very little curve text, which can be widely observed in scene images such as signboard, product name and so on. To raise the concerns of reading curve text in the wild, in this paper, we construct a curve text dataset named CTW1500, which includes over 10k text annotations in 1,500 images (1000 for training and 500 for testing). Based on this dataset, we pioneering propose a polygon based curve text detector (CTD) which can directly detect curve text without empirical combination. Moreover, by seamlessly integrating the recurrent transverse and longitudinal offset connection (TLOC), the proposed method can be end-to-end trainable to learn the inherent connection among the position offsets. This allows the CTD to explore context information instead of predicting points independently, resulting in more smooth and accurate detection. We also propose two simple but effective post-processing methods named non-polygon suppress (NPS) and polygonal non-maximum suppression (PNMS) to further improve the detection accuracy. Furthermore, the proposed approach in this paper is designed in an universal manner, which can also be trained with rectangular or quadrilateral bounding boxes without extra efforts. Experimental results on CTW-1500 demonstrate our method with only a light backbone can outperform state-of-the-art methods with a large margin. By evaluating only in the curve or non-curve subset, the CTD + TLOC can still achieve the best results. Code is available at https://github.com/Yuliang-Liu/Curve-Text-Detector.

##### Abstract (translated by Google)
现场文本检测近年来取得了很大的进展。检测方式从轴对齐的矩形到旋转的矩形，再到四边形。然而，目前的数据集包含很少的曲线文本，可以在广告牌，产品名称等场景图像中广泛观察到。为了提高读者阅读曲线文本的关注度，本文构建了一个名为CTW1500的曲线文本数据集，其中包括1500幅图像（训练1000个，测试500个）中的超过10万个文本注释。基于这个数据集，我们开创性地提出了一个基于多边形的曲线文本检测器（CTD），它可以直接检测曲线文本而无需经验组合。此外，通过无缝集成横向和纵向偏移连接（TLOC），所提出的方法可以进行端到端的训练，以了解位置偏移之间的内在联系。这使得CTD能够探索上下文信息，而不是独立地预测点，从而导致更加平滑和准确的检测。我们还提出了两个简单而有效的后处理方法，称为非多边形抑制（NPS）和多边形非最大抑制（PNMS），以进一步提高检测精度。此外，本文提出的方法是以通用的方式进行设计的，也可以用矩形或四边形包围盒进行训练而不需要额外的努力。 CTW-1500的实验结果表明，我们的方法只有轻微的骨架，可以大幅超越最先进的方法。通过只评估曲线或非曲线子集，CTD + TLOC仍然可以达到最好的结果。代码可在https://github.com/Yuliang-Liu/Curve-Text-Detector获得。

##### URL
[http://arxiv.org/abs/1712.02170](http://arxiv.org/abs/1712.02170)

##### PDF
[http://arxiv.org/pdf/1712.02170](http://arxiv.org/pdf/1712.02170)

