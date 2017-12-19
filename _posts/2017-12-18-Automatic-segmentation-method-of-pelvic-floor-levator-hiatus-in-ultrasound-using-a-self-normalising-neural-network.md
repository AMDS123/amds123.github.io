---
layout: post
title: "Automatic segmentation method of pelvic floor levator hiatus in ultrasound using a self-normalising neural network"
date: 2017-12-18 15:04:21
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Ester Bonmati, Yipeng Hu, Nikhil Sindhwani, Hans Peter Dietz, Jan D&#x27;hooge, Dean Barratt, Jan Deprest, Tom Vercauteren
mathjax: true
---

* content
{:toc}

##### Abstract
Segmentation of the levator hiatus in ultrasound allows to extract biometrics which are of importance for pelvic floor disorder assessment. In this work, we present a fully automatic method using a convolutional neural network (CNN) to outline the levator hiatus in a 2D image extracted from a 3D ultrasound volume. In particular, our method uses a recently developed scaled exponential linear unit (SELU) as a nonlinear self-normalising activation function, which for the first time has been applied in medical imaging with CNN. SELU has important advantages such as being parameter-free and mini-batch independent, which may help to overcome memory constraints during training. A dataset with 91 images from 35 patients during Valsalva, contraction and rest, all labelled by three operators, is used for training and evaluation in a leave-one-patient-out cross-validation. Results show a median Dice similarity coefficient of 0.90 with an interquartile range of 0.08, with equivalent performance to the three operators (with a Williams' index of 1.03), and outperforming a U-Net architecture without the need for batch normalisation. We conclude that the proposed fully automatic method achieved equivalent accuracy in segmenting the pelvic floor levator hiatus compared to a previous semi-automatic approach.

##### Abstract (translated by Google)
超声波提肌断层的分割允许提取对骨盆底紊乱评估重要的生物测量学。在这项工作中，我们提出了一个全自动的方法，使用卷积神经网络（CNN）来勾画从三维超声体积提取的二维图像中的提肌断层。具体而言，我们的方法使用最近开发的缩放指数线性单元（SELU）作为非线性自标准化激活函数，这是第一次在CNN医学成像中应用。 SELU具有诸如无参数和小批量独立等重要优点，可以帮助克服训练期间的内存限制。一个包含来自35位病人的91幅图像的数据集，收缩和休息，全部由三名操作员标记，用于训练和评估一个病人的交叉验证。结果显示Dice的中位数相似系数为0.90，四分位数间距为0.08，与三个操作员（威廉姆斯指数为1.03）的性能相当，并且在不需要批量标准化的情况下表现优于U-Net架构。我们的结论是，与以前的半自动方法相比，所提出的全自动方法在分割骨盆提肌间隙方面达到了等同的准确度。

##### URL
[http://arxiv.org/abs/1712.06452](http://arxiv.org/abs/1712.06452)

##### PDF
[http://arxiv.org/pdf/1712.06452](http://arxiv.org/pdf/1712.06452)

