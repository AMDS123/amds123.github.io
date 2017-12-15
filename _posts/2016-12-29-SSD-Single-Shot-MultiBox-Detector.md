---
layout: post
title: "SSD: Single Shot MultiBox Detector"
date: 2016-12-29 19:05:11
categories: arXiv_CV
tags: arXiv_CV Object_Detection Inference Prediction Detection
author: Wei Liu, Dragomir Anguelov, Dumitru Erhan, Christian Szegedy, Scott Reed, Cheng-Yang Fu, Alexander C. Berg
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method for detecting objects in images using a single deep neural network. Our approach, named SSD, discretizes the output space of bounding boxes into a set of default boxes over different aspect ratios and scales per feature map location. At prediction time, the network generates scores for the presence of each object category in each default box and produces adjustments to the box to better match the object shape. Additionally, the network combines predictions from multiple feature maps with different resolutions to naturally handle objects of various sizes. Our SSD model is simple relative to methods that require object proposals because it completely eliminates proposal generation and subsequent pixel or feature resampling stage and encapsulates all computation in a single network. This makes SSD easy to train and straightforward to integrate into systems that require a detection component. Experimental results on the PASCAL VOC, MS COCO, and ILSVRC datasets confirm that SSD has comparable accuracy to methods that utilize an additional object proposal step and is much faster, while providing a unified framework for both training and inference. Compared to other single stage methods, SSD has much better accuracy, even with a smaller input image size. For $300\times 300$ input, SSD achieves 72.1% mAP on VOC2007 test at 58 FPS on a Nvidia Titan X and for $500\times 500$ input, SSD achieves 75.1% mAP, outperforming a comparable state of the art Faster R-CNN model. Code is available at this https URL .

##### Abstract (translated by Google)
我们提出了一种使用单个深度神经网络来检测图像中的对象的方法。我们的方法命名为SSD，将边界框的输出空间离散化为一组根据不同长宽比和每个特征地图位置缩放的默认框。在预测时间，网络会在每个默认框中为每个对象类别的出现生成分数，并对框进行调整以更好地匹配对象形状。另外，网络结合不同分辨率的多个特征地图的预测来自然处理各种尺寸的对象。我们的SSD模型相对于需要对象提议的方法而言简单，因为它完全消除了提案生成和后续的像素或特征重采样阶段，并将所有计算封装在单个网络中。这使得SSD易于训练和直接集成到需要检测组件的系统中。 PASCAL VOC，MS COCO和ILSVRC数据集上的实验结果证实，SSD具有与使用额外对象提议步骤的方法相当的准确性，并且速度更快，同时为训练和推理提供了统一的框架。与其他单级方法相比，即使输入图像尺寸较小，SSD也具有更高的精度。对于300美元的投入300美元，固态硬盘在VOC2007测试中达到72.1％的mAP，在Nvidia Titan X上达到58 FPS，并以500美元的价格投入500美元，SSD达到75.1％的mAP，超越了同类技术的更快的R-CNN模型。代码可在此https网址获得。

##### URL
[https://arxiv.org/abs/1512.02325](https://arxiv.org/abs/1512.02325)

##### PDF
[https://arxiv.org/pdf/1512.02325](https://arxiv.org/pdf/1512.02325)

