---
layout: post
title: "Modeling Visual Context is Key to Augmenting Object Detection Datasets"
date: 2018-07-19 13:50:42
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Image_Generation Detection Recognition
author: Nikita Dvornik (Thoth), Julien Mairal (Thoth), Cordelia Schmid (Thoth)
mathjax: true
---

* content
{:toc}

##### Abstract
Performing data augmentation for learning deep neural networks is well known to be important for training visual recognition systems. By artificially increasing the number of training examples, it helps reducing overfitting and improves generalization. For object detection, classical approaches for data augmentation consist of generating images obtained by basic geometrical transformations and color changes of original training images. In this work, we go one step further and leverage segmentation annotations to increase the number of object instances present on training data. For this approach to be successful, we show that modeling appropriately the visual context surrounding objects is crucial to place them in the right environment. Otherwise, we show that the previous strategy actually hurts. With our context model, we achieve significant mean average precision improvements when few labeled examples are available on the VOC'12 benchmark.

##### Abstract (translated by Google)
众所周知，执行用于学习深度神经网络的数据增强对于训练视觉识别系统是重要的。通过人为增加训练样本的数量，它有助于减少过度拟合并改善泛化。对于物体检测，用于数据增强的经典方法包括生成通过基本几何变换和原始训练图像的颜色变化获得的图像。在这项工作中，我们更进一步，利用分段注释来增加训练数据上存在的对象实例的数量。为了使这种方法获得成功，我们表明，适当地建模对象周围的视觉上下文对于将它们放置在正确的环境中至关重要。否则，我们会发现之前的策略确实会受到伤害。通过我们的上下文模型，当VOC'12基准测试中很少有标记示例可用时，我们实现了显着的平均精度改进。

##### URL
[https://arxiv.org/abs/1807.07428](https://arxiv.org/abs/1807.07428)

##### PDF
[https://arxiv.org/pdf/1807.07428](https://arxiv.org/pdf/1807.07428)

