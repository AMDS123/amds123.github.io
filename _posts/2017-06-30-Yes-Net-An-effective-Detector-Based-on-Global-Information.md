---
layout: post
title: "Yes-Net: An effective Detector Based on Global Information"
date: 2017-06-30 07:14:40
categories: arXiv_CV
tags: arXiv_CV Object_Detection RNN Prediction Detection
author: Liangzhuang Ma, Xin Kan, Qianjiang Xiao, Wenlong Liu, Peiqin Sun
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a new real-time object detection approach named Yes-Net. It realizes the prediction of bounding boxes and class via single neural network like YOLOv2 and SSD, but owns more efficient and outstanding features. It combines local information with global information by adding the RNN architecture as a packed unit in CNN model to form the basic feature extractor. Independent anchor boxes coming from full-dimension k-means is also applied in Yes-Net, it brings better average IOU than grid anchor box. In addition, instead of NMS, Yes-Net uses RNN as a filter to get the final boxes, which is more efficient. For 416 x 416 input, Yes-Net achieves 79.2% mAP on VOC2007 test at 39 FPS on an Nvidia Titan X Pascal.

##### Abstract (translated by Google)
本文介绍了一种名为Yes-Net的新型实时对象检测方法。通过YOLOv2，SSD等单一神经网络实现对边界框和类的预测，但具有更高效和突出的特点。它将本地信息与全局信息相结合，在CNN模型中增加RNN结构作为打包单元，形成基本特征提取器。来自全维k-means的独立锚箱在Yes-Net中也被应用，它比平面锚箱带来更好的平均IOU。另外，Yes-Net不是使用NMS，而是使用RNN作为过滤器来获取最终的方框，这样更有效率。对于416 x 416的输入，在Nvidia Titan X Pascal上，以39 FPS在VOC2007测试中，Yes-Net达到了79.2％的mAP。

##### URL
[https://arxiv.org/abs/1706.09180](https://arxiv.org/abs/1706.09180)

##### PDF
[https://arxiv.org/pdf/1706.09180](https://arxiv.org/pdf/1706.09180)

