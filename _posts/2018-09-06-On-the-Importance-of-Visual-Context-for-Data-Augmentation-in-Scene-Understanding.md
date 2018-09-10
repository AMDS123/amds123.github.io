---
layout: post
title: "On the Importance of Visual Context for Data Augmentation in Scene Understanding"
date: 2018-09-06 08:37:15
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Segmentation CNN Semantic_Segmentation Detection Recognition
author: Nikita Dvornik, Julien Mairal, Cordelia Schmid
mathjax: true
---

* content
{:toc}

##### Abstract
Performing data augmentation for learning deep neural networks is known to be important for training visual recognition systems. By artificially increasing the number of training examples, it helps reducing overfitting and improves generalization. While simple image transformations such as changing color intensity or adding random noise can already improve predictive performance in most vision tasks, larger gains can be obtained by leveraging task-specific prior knowledge. In this work, we consider object detection and semantic segmentation and augment the training images by blending objects in existing scenes, using instance segmentation annotations. We observe that randomly pasting objects on images hurts the performance, unless the object is placed in the right context. To resolve this issue, we propose an explicit context model by using a convolutional neural network, which predicts whether an image region is suitable for placing a given object or not. In our experiments, we show that by using copy-paste data augmentation with context guidance we are able to improve detection and segmentation on the PASCAL VOC12 and COCO datasets, with significant gains when few labeled examples are available. We also show that the method is not limited to datasets that come with expensive pixel-wise instance annotations and can be used when only bounding box annotations are available, by employing weakly-supervised learning for instance masks approximation.

##### Abstract (translated by Google)
已知用于学习深度神经网络的数据增强对于训练视觉识别系统是重要的。通过人为增加训练样本的数量，它有助于减少过度拟合并改善泛化。虽然简单的图像变换（例如改变颜色强度或添加随机噪声）已经可以提高大多数视觉任务的预测性能，但通过利用特定于任务的先验知识可以获得更大的增益。在这项工作中，我们考虑对象检测和语义分割，并通过使用实例分割注释在现有场景中混合对象来增强训练图像。我们观察到，除非将对象置于正确的上下文中，否则随机粘贴图像上的对象会损害性能。为了解决这个问题，我们通过使用卷积神经网络提出了一个显式的上下文模型，该网络预测图像区域是否适合放置给定的对象。在我们的实验中，我们展示了通过使用上下文引导的复制粘贴数据增强，我们能够改进PASCAL VOC12和COCO数据集的检测和分割，当几个标记示例可用时，显着增益。我们还表明，该方法不限于带有昂贵的像素实例注释的数据集，并且可以在仅有边界框注释可用时使用，通过采用弱监督学习（例如掩模近似）。

##### URL
[http://arxiv.org/abs/1809.02492](http://arxiv.org/abs/1809.02492)

##### PDF
[http://arxiv.org/pdf/1809.02492](http://arxiv.org/pdf/1809.02492)

