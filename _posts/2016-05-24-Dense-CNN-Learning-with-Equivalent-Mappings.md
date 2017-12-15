---
layout: post
title: "Dense CNN Learning with Equivalent Mappings"
date: 2016-05-24 01:24:26
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Prediction
author: Jianxin Wu, Chen-Wei Xie, Jian-Hao Luo
mathjax: true
---

* content
{:toc}

##### Abstract
Large receptive field and dense prediction are both important for achieving high accuracy in pixel labeling tasks such as semantic segmentation. These two properties, however, contradict with each other. A pooling layer (with stride 2) quadruples the receptive field size but reduces the number of predictions to 25\%. Some existing methods lead to dense predictions using computations that are not equivalent to the original model. In this paper, we propose the equivalent convolution (eConv) and equivalent pooling (ePool) layers, leading to predictions that are both dense and equivalent to the baseline CNN model. Dense prediction models learned using eConv and ePool can transfer the baseline CNN's parameters as a starting point, and can inverse transfer the learned parameters in a dense model back to the original one, which has both fast testing speed and high accuracy. The proposed eConv and ePool layers have achieved higher accuracy than baseline CNN in various tasks, including semantic segmentation, object localization, image categorization and apparent age estimation, not only in those tasks requiring dense pixel labeling.

##### Abstract (translated by Google)
大的感受野和密集的预测对于在诸如语义分割的像素标记任务中实现高精度是重要的。然而这两个属性相互矛盾。池化层（步幅2）使感受野大小增加4倍，但将预测的数量减少到25％。一些现有的方法导致密集的预测使用不等于原始模型的计算。在本文中，我们提出了等价卷积（eConv）和等价池（ePool）层，导致预测密集且等同于基线CNN模型。使用eConv和ePool学习的密集预测模型可以将基线CNN的参数作为起始点，并且可以将密集模型中的学习参数反向传递到原始参数，这既具有快速的测试速度又具有高的准确性。所提出的eConv和ePool图层在各种任务（包括语义分割，对象定位，图像分类和明显的年龄估计）中比基线CNN具有更高的准确性，不仅在需要密集像素标记的任务中。

##### URL
[https://arxiv.org/abs/1605.07251](https://arxiv.org/abs/1605.07251)

##### PDF
[https://arxiv.org/pdf/1605.07251](https://arxiv.org/pdf/1605.07251)

