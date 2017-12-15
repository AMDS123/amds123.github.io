---
layout: post
title: "End-to-end training of object class detectors for mean average precision"
date: 2017-03-16 13:55:07
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection Gradient_Descent
author: Paul Henderson, Vittorio Ferrari
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method for training CNN-based object class detectors directly using mean average precision (mAP) as the training loss, in a truly end-to-end fashion that includes non-maximum suppression (NMS) at training time. This contrasts with the traditional approach of training a CNN for a window classification loss, then applying NMS only at test time, when mAP is used as the evaluation metric in place of classification accuracy. However, mAP following NMS forms a piecewise-constant structured loss over thousands of windows, with gradients that do not convey useful information for gradient descent. Hence, we define new, general gradient-like quantities for piecewise constant functions, which have wide applicability. We describe how to calculate these efficiently for mAP following NMS, enabling to train a detector based on Fast R-CNN directly for mAP. This model achieves equivalent performance to the standard Fast R-CNN on the PASCAL VOC 2007 and 2012 datasets, while being conceptually more appealing as the very same model and loss are used at both training and test time.

##### Abstract (translated by Google)
我们提出了一种以平均精度（mAP）作为训练损失直接训练基于CNN的目标类别检测器的方法，以真正端到端的方式，包括训练时间的非最大抑制（NMS）。这与传统的针对窗口分类丢失的CNN训练方法形成了鲜明的对比，然后仅在测试时使用NMS作为评估度量来代替分类精度。然而，在NMS之后的mAP在数千个窗口中形成分段恒定的结构性损失，而梯度不能传递梯度下降的有用信息。因此，我们为分段常数函数定义了新的，一般梯度类的量，具有广泛的适用性。我们描述了如何在NMS之后为mAP有效地计算这些值，从而能够直接为基于快速R-CNN的mAP训练探测器。该模型在PASCAL VOC 2007和2012数据集上获得了与标准Fast R-CNN相当的性能，而在训练和测试时使用相同的模型和损耗，在概念上更具吸引力。

##### URL
[https://arxiv.org/abs/1607.03476](https://arxiv.org/abs/1607.03476)

##### PDF
[https://arxiv.org/pdf/1607.03476](https://arxiv.org/pdf/1607.03476)

