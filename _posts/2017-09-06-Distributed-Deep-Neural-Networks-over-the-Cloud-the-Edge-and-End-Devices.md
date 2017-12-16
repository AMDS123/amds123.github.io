---
layout: post
title: "Distributed Deep Neural Networks over the Cloud, the Edge and End Devices"
date: 2017-09-06 04:00:18
categories: arXiv_CV
tags: arXiv_CV Inference Recognition
author: Surat Teerapittayanon, Bradley McDanel, H.T. Kung
mathjax: true
---

* content
{:toc}

##### Abstract
We propose distributed deep neural networks (DDNNs) over distributed computing hierarchies, consisting of the cloud, the edge (fog) and end devices. While being able to accommodate inference of a deep neural network (DNN) in the cloud, a DDNN also allows fast and localized inference using shallow portions of the neural network at the edge and end devices. When supported by a scalable distributed computing hierarchy, a DDNN can scale up in neural network size and scale out in geographical span. Due to its distributed nature, DDNNs enhance sensor fusion, system fault tolerance and data privacy for DNN applications. In implementing a DDNN, we map sections of a DNN onto a distributed computing hierarchy. By jointly training these sections, we minimize communication and resource usage for devices and maximize usefulness of extracted features which are utilized in the cloud. The resulting system has built-in support for automatic sensor fusion and fault tolerance. As a proof of concept, we show a DDNN can exploit geographical diversity of sensors to improve object recognition accuracy and reduce communication cost. In our experiment, compared with the traditional method of offloading raw sensor data to be processed in the cloud, DDNN locally processes most sensor data on end devices while achieving high accuracy and is able to reduce the communication cost by a factor of over 20x.

##### Abstract (translated by Google)
我们提出分布式深度神经网络（DDNN）分布式计算层次结构，包括云，边缘（雾）和终端设备。虽然能够容纳云中深度神经网络（DNN）的推断，但DDNN还允许使用边缘和终端设备处的神经网络的浅部分进行快速和局部推断。在可扩展的分布式计算层次结构的支持下，DDNN可以扩大神经网络的规模，扩大地理范围。由于其分布式特性，DDNN增强了DNN应用的传感器融合，系统容错性和数据隐私性。在实现DDNN时，我们将DNN的部分映射到分布式计算层次上。通过联合培训这些部分，我们尽量减少设备的通信和资源使用，并最大限度地提高云中使用的提取特性的实用性。由此产生的系统内置了对自动传感器融合和容错的支持。作为一个概念证明，我们展示一个DDNN可以利用传感器的地理多样性来提高物体识别的准确性和降低通信成本。在我们的实验中，与传统的将原始传感器数据卸载到云中进行处理的方法相比，DDNN本地处理终端设备上的大部分传感器数据，同时达到高精度，能够将通信成本降低20倍以上。

##### URL
[https://arxiv.org/abs/1709.01921](https://arxiv.org/abs/1709.01921)

##### PDF
[https://arxiv.org/pdf/1709.01921](https://arxiv.org/pdf/1709.01921)

