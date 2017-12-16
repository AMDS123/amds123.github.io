---
layout: post
title: "Holistic, Instance-Level Human Parsing"
date: 2017-09-11 22:06:34
categories: arXiv_CV
tags: arXiv_CV Segmentation Detection
author: Qizhu Li, Anurag Arnab, Philip H.S. Torr
mathjax: true
---

* content
{:toc}

##### Abstract
Object parsing -- the task of decomposing an object into its semantic parts -- has traditionally been formulated as a category-level segmentation problem. Consequently, when there are multiple objects in an image, current methods cannot count the number of objects in the scene, nor can they determine which part belongs to which object. We address this problem by segmenting the parts of objects at an instance-level, such that each pixel in the image is assigned a part label, as well as the identity of the object it belongs to. Moreover, we show how this approach benefits us in obtaining segmentations at coarser granularities as well. Our proposed network is trained end-to-end given detections, and begins with a category-level segmentation module. Thereafter, a differentiable Conditional Random Field, defined over a variable number of instances for every input image, reasons about the identity of each part by associating it with a human detection. In contrast to other approaches, our method can handle the varying number of people in each image and our holistic network produces state-of-the-art results in instance-level part and human segmentation, together with competitive results in category-level part segmentation, all achieved by a single forward-pass through our neural network.

##### Abstract (translated by Google)
对象解析 - 将对象分解成其语义部分的任务传统上被定义为类别级别的分割问题。因此，当图像中存在多个对象时，当前的方法不能计算场景中的对象数量，也不能确定哪个对象属于哪个对象。我们通过在实例级分割对象的部分来解决这个问题，使得图像中的每个像素被分配一个部分标签，以及它所属的对象的标识。此外，我们还展示了这种方法如何让我们以更粗的粒度获得分割。我们提出的网络是训练有素的端到端检测，并从一个分类层次的分割模块开始。此后，针对每个输入图像在可变数量的实例上定义的可微条件随机场通过将其与人体检测相关联而引起关于每个部分的身份的原因。与其他方法相比，我们的方法可以处理每个图像中不同数量的人，我们的整体网络产生实例级别和人体分割的最新结果，并与类别级别部分分割中的竞争结果，都是通过我们的神经网络来实现的。

##### URL
[https://arxiv.org/abs/1709.03612](https://arxiv.org/abs/1709.03612)

##### PDF
[https://arxiv.org/pdf/1709.03612](https://arxiv.org/pdf/1709.03612)

