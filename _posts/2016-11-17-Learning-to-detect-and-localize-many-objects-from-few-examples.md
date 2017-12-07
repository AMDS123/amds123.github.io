---
layout: post
title: "Learning to detect and localize many objects from few examples"
date: 2016-11-17 12:51:18
categories: arXiv_CV
tags: arXiv_CV Object_Detection RNN Prediction Detection
author: Bastien Moysset, Christoper Kermorvant, Christian Wolf
mathjax: true
---

* content
{:toc}

##### Abstract
The current trend in object detection and localization is to learn predictions with high capacity deep neural networks trained on a very large amount of annotated data and using a high amount of processing power. In this work, we propose a new neural model which directly predicts bounding box coordinates. The particularity of our contribution lies in the local computations of predictions with a new form of local parameter sharing which keeps the overall amount of trainable parameters low. Key components of the model are spatial 2D-LSTM recurrent layers which convey contextual information between the regions of the image. We show that this model is more powerful than the state of the art in applications where training data is not as abundant as in the classical configuration of natural images and Imagenet/Pascal VOC tasks. We particularly target the detection of text in document images, but our method is not limited to this setting. The proposed model also facilitates the detection of many objects in a single image and can deal with inputs of variable sizes without resizing.

##### Abstract (translated by Google)
对象检测和本地化的当前趋势是学习大容量深度神经网络的预测，训练大量的注释数据并使用大量的处理能力。在这项工作中，我们提出了一个直接预测边界框坐标的新的神经模型。我们的贡献的特殊性在于局部参数共享的预测的局部计算，其使可训练参数的总量保持较低。该模型的关键组件是空间2D-LSTM递归层，其传递图像区域之间的上下文信息。我们证明，这个模型比在自然图像和Imagenet / Pascal VOC任务的经典配置中培训数据不够丰富的应用程序的技术水平更加强大。我们特别针对文档图像中的文字检测，但是我们的方法不限于此设置。所提出的模型还有助于检测单个图像中的多个对象，并且可以处理不同大小的输入，而不用调整大小。

##### URL
[https://arxiv.org/abs/1611.05664](https://arxiv.org/abs/1611.05664)

##### PDF
[https://arxiv.org/pdf/1611.05664](https://arxiv.org/pdf/1611.05664)

