---
layout: post
title: "A MultiPath Network for Object Detection"
date: 2016-08-08 13:29:02
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Detection
author: Sergey Zagoruyko, Adam Lerer, Tsung-Yi Lin, Pedro O. Pinheiro, Sam Gross, Soumith Chintala, Piotr Dollár
mathjax: true
---

* content
{:toc}

##### Abstract
The recent COCO object detection dataset presents several new challenges for object detection. In particular, it contains objects at a broad range of scales, less prototypical images, and requires more precise localization. To address these challenges, we test three modifications to the standard Fast R-CNN object detector: (1) skip connections that give the detector access to features at multiple network layers, (2) a foveal structure to exploit object context at multiple object resolutions, and (3) an integral loss function and corresponding network adjustment that improve localization. The result of these modifications is that information can flow along multiple paths in our network, including through features from multiple network layers and from multiple object views. We refer to our modified classifier as a "MultiPath" network. We couple our MultiPath network with DeepMask object proposals, which are well suited for localization and small objects, and adapt our pipeline to predict segmentation masks in addition to bounding boxes. The combined system improves results over the baseline Fast R-CNN detector with Selective Search by 66% overall and by 4x on small objects. It placed second in both the COCO 2015 detection and segmentation challenges.

##### Abstract (translated by Google)
最近的COCO物体检测数据集为物体检测提出了几个新的挑战。特别是，它包含广泛范围的对象，较少的原型图像，并且需要更精确的定位。为了解决这些挑战，我们测试了对标准Fast R-CNN对象检测器的三种修改：（1）跳过允许检测器访问多个网络层的特征的连接，（2）利用多个对象分辨率的对象上下文的中心凹结构（3）整体损失函数和相应的网络调整，以提高本地化。这些修改的结果是，信息可以在我们的网络中沿着多个路径流动，包括通过来自多个网络层的特征和来自多个对象视图的特征。我们将修改后的分类器称为“多路径”网络。我们将MultiPath网络与DeepMask对象提案耦合，非常适合本地化和小型对象，并使我们的流水线能够预测分割模板以及边界框。综合系统比基线快速R-CNN检测器的选择性搜索的结果总体上提高了66％，在小物体上提高了4倍。它在COCO 2015检测和细分挑战中排名第二。

##### URL
[https://arxiv.org/abs/1604.02135](https://arxiv.org/abs/1604.02135)

##### PDF
[https://arxiv.org/pdf/1604.02135](https://arxiv.org/pdf/1604.02135)

