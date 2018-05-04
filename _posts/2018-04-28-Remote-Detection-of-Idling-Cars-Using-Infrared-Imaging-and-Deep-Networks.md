---
layout: post
title: "Remote Detection of Idling Cars Using Infrared Imaging and Deep Networks"
date: 2018-04-28 14:01:58
categories: arXiv_CV
tags: arXiv_CV CNN Detection
author: Muhammet Bastan, Kim-Hui Yap, Lap-Pui Chau
mathjax: true
---

* content
{:toc}

##### Abstract
Idling vehicles waste energy and pollute the environment through exhaust emission. In some countries, idling a vehicle for more than a predefined duration is prohibited and automatic idling vehicle detection is desirable for law enforcement. We propose the first automatic system to detect idling cars, using infrared (IR) imaging and deep networks. We rely on the differences in spatio-temporal heat signatures of idling and stopped cars and monitor the car temperature with a long-wavelength IR camera. We formulate the idling car detection problem as spatio-temporal event detection in IR image sequences and employ deep networks for spatio-temporal modeling. We collected the first IR image sequence dataset for idling car detection. First, we detect the cars in each IR image using a convolutional neural network, which is pre-trained on regular RGB images and fine-tuned on IR images for higher accuracy. Then, we track the detected cars over time to identify the cars that are parked. Finally, we use the 3D spatio-temporal IR image volume of each parked car as input to convolutional and recurrent networks to classify them as idling or not. We carried out an extensive empirical evaluation of temporal and spatio-temporal modeling approaches with various convolutional and recurrent architectures. We present promising experimental results on our IR image sequence dataset.

##### Abstract (translated by Google)
怠速车辆通过废气排放浪费能源并污染环境。在某些国家，禁止将车辆空转超过预定的时间，并且执法机构需要自动检测怠速车辆。我们提出了第一个使用红外（IR）成像和深度网络来检测怠速车的自动系统。我们依靠怠速和停车时空热特征的差异，并使用长波红外摄像机监控车内温度。我们将怠速车检测问题制定为IR图像序列中的时空事件检测，并采用深度网络进行时空建模。我们收集了第一个IR图像序列数据集，用于怠速汽车检测。首先，我们使用卷积神经网络在每个红外图像中检测汽车，该网络在规则的RGB图像上进行预先训练，并在IR图像上进行微调以获得更高的精度。然后，我们跟踪检测到的汽车随着时间的推移，以识别停放的汽车。最后，我们使用每辆停放汽车的3D时空红外图像体积作为卷积和循环网络的输入，以将它们分类为空闲或不空闲。我们对各种卷积和循环体系结构的时间和时空建模方法进行了广泛的经验性评估。我们在我们的IR图像序列数据集上呈现出有前景的实验结果

##### URL
[https://arxiv.org/abs/1804.10805](https://arxiv.org/abs/1804.10805)

##### PDF
[https://arxiv.org/pdf/1804.10805](https://arxiv.org/pdf/1804.10805)

