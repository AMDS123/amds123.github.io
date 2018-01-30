---
layout: post
title: "Road Damage Detection Using Deep Neural Networks with Images Captured Through a Smartphone"
date: 2018-01-29 11:25:20
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Face CNN Detection
author: Hiroya Maeda, Yoshihide Sekimoto, Toshikazu Seto, Takehiro Kashiyama, Hiroshi Omata
mathjax: true
---

* content
{:toc}

##### Abstract
Research on damage detection of road surfaces using image processing techniques has been actively conducted, achieving considerably high detection accuracies. Many studies only focus on the detection of the presence or absence of damage. However, in a real-world scenario, when the road managers from a governing body need to repair such damage, they need to clearly understand the type of damage in order to take effective action. In addition, in many of these previous studies, the researchers acquire their own data using different methods. Hence, there is no uniform road damage dataset available openly, leading to the absence of a benchmark for road damage detection. This study makes three contributions to address these issues. First, to the best of our knowledge, for the first time, a large-scale road damage dataset is prepared. This dataset is composed of 9,053 road damage images captured with a smartphone installed on a car, with 15,435 instances of road surface damage included in these road images. In order to generate this dataset, we cooperated with 7 municipalities in Japan and acquired road images for more than 40 hours. These images were captured in a wide variety of weather and illuminance conditions. In each image, we annotated the bounding box representing the location and type of damage. Next, we used a state-of-the-art object detection method using convolutional neural networks to train the damage detection model with our dataset, and compared the accuracy and runtime speed on both, using a GPU server and a smartphone. Finally, we demonstrate that the type of damage can be classified into eight types with high accuracy by applying the proposed object detection method. The road damage dataset, our experimental results, and the developed smartphone application used in this study are publicly available (https://github.com/sekilab/RoadDamageDetector/).

##### Abstract (translated by Google)
利用图像处理技术对路面损伤检测进行了研究，取得了相当高的检测精度。许多研究只关注检测是否存在损害。但是，在现实情况下，当一个管理机构的道路管理者需要修复这种损害时，他们需要清楚地了解损害的类型以采取有效的行动。此外，在以前的许多研究中，研究人员使用不同的方法获取自己的数据。因此，没有统一的公路损害数据集可供公开使用，导致缺少道路损害检测的基准。本研究为解决这些问题做了三项贡献。首先，据我们所知，第一次准备了一个大规模的道路损坏数据集。该数据集由安装在汽车上的智能手机拍摄的9,053次道路损坏图像组成，在这些道路图像中包含15,435道路路面损坏。为了生成这个数据集，我们与日本的7个城市合作，获得了40多个小时的道路图像。这些图像是在各种天气和照度条件下拍摄的。在每个图像中，我们注释了表示损伤位置和类型的边界框。接下来，我们使用了一种使用卷积神经网络的最先进的物体检测方法来利用我们的数据集来训练损伤检测模型，并且使用GPU服务器和智能手机比较两者的精度和运行速度。最后，我们通过应用所提出的目标检测方法来证明损伤的类型可以被高精度地分成八类。道路损坏数据集，我们的实验结果以及本研究中使用的智能手机应用程序都是公开的（https://github.com/sekilab/RoadDamageDetector/）。

##### URL
[http://arxiv.org/abs/1801.09454](http://arxiv.org/abs/1801.09454)

##### PDF
[http://arxiv.org/pdf/1801.09454](http://arxiv.org/pdf/1801.09454)

