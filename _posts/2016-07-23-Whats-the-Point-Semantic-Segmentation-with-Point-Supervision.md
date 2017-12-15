---
layout: post
title: "What's the Point: Semantic Segmentation with Point Supervision"
date: 2016-07-23 17:41:43
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Amy Bearman, Olga Russakovsky, Vittorio Ferrari, Li Fei-Fei
mathjax: true
---

* content
{:toc}

##### Abstract
The semantic image segmentation task presents a trade-off between test time accuracy and training-time annotation cost. Detailed per-pixel annotations enable training accurate models but are very time-consuming to obtain, image-level class labels are an order of magnitude cheaper but result in less accurate models. We take a natural step from image-level annotation towards stronger supervision: we ask annotators to point to an object if one exists. We incorporate this point supervision along with a novel objectness potential in the training loss function of a CNN model. Experimental results on the PASCAL VOC 2012 benchmark reveal that the combined effect of point-level supervision and objectness potential yields an improvement of 12.9% mIOU over image-level supervision. Further, we demonstrate that models trained with point-level supervision are more accurate than models trained with image-level, squiggle-level or full supervision given a fixed annotation budget.

##### Abstract (translated by Google)
语义图像分割任务在测试时间精度和训练时间注释成本之间进行权衡。详细的每像素注释使训练准确的模型，但是是非常耗时的获得，图像级的类标签是一个数量级便宜，但导致不太准确的模型。我们从图像级注释向更强大的监督迈出了自然的一步：我们要求注释者指出一个对象是否存在。在CNN模型的训练损失函数中，我们将这一点监督与新的对象潜力结合在一起。 PASCAL VOC 2012基准的实验结果显示，点层监督与目标潜力的综合效应比图像层面的监督提高了12.9％的mIOU。此外，我们证明，使用点级监督训练的模型比使用图像级别，波形级别或全面监督训练的模型更精确，只要给定固定注释预算。

##### URL
[https://arxiv.org/abs/1506.02106](https://arxiv.org/abs/1506.02106)

##### PDF
[https://arxiv.org/pdf/1506.02106](https://arxiv.org/pdf/1506.02106)

