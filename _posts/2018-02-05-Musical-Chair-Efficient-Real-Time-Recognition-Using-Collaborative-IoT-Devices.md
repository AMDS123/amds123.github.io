---
layout: post
title: "Musical Chair: Efficient Real-Time Recognition Using Collaborative IoT Devices"
date: 2018-02-05 19:32:35
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Recognition
author: Ramyad Hadidi, Jiashen Cao, Matthew Woodward, Michael Ryoo, Hyesoon Kim
mathjax: true
---

* content
{:toc}

##### Abstract
The prevalence of Internet of things (IoT) devices and abundance of sensor data has created an increase in real-time data processing such as recognition of speech, image, and video. While currently such processes are offloaded to the computationally powerful cloud system, a localized and distributed approach is desirable because (i) it preserves the privacy of users and (ii) it omits the dependency on cloud services. However, IoT networks are usually composed of resource-constrained devices, and a single device is not powerful enough to process real-time data. To overcome this challenge, we examine data and model parallelism for such devices in the context of deep neural networks. We propose Musical Chair to enable efficient, localized, and dynamic real-time recognition by harvesting the aggregated computational power from the resource-constrained devices in the same IoT network as input sensors. Musical chair adapts to the availability of computing devices at runtime and adjusts to the inherit dynamics of IoT networks. To demonstrate Musical Chair, on a network of Raspberry PIs (up to 12) each connected to a camera, we implement a state-of-the-art action recognition model for videos and two recognition models for images. Compared to the Tegra TX2, an embedded low-power platform with a quad-core CPU and a GPU, our distributed action recognition system achieves not only similar energy consumption but also twice the performance of the TX2. Furthermore, in image recognition, Musical Chair achieves similar performance and saves dynamic energy.

##### Abstract (translated by Google)
物联网（IoT）设备的普及以及传感器数据的丰富已经使得实时数据处理（诸如语音，图像和视频的识别）增加。虽然目前这样的流程被卸载到计算能力强大的云系统，但是本地化和分布式的方法是可取的，因为（i）它保留了用户的隐私，并且（ii）它省略了对云服务的依赖。但是，物联网网络通常由资源受限的设备组成，单个设备的功能不足以处理实时数据。为了克服这个挑战，我们在深度神经网络的背景下研究这些设备的数据和模型并行性。我们建议使用音乐座椅，通过从输入传感器所在的同一物联网网络中的资源受限设备收集汇总的计算能力，从而实现高效，本地化和动态的实时识别。音乐椅在运行时适应计算设备的可用性，并适应物联网网络的继承动态。为了展示Musical Chair，在一个连接到摄像机的Raspberry PI（最多12个）网络上，我们实现了视频和两个图像识别模型的最先进的动作识别模型。与Tegra TX2（一款采用四核CPU和GPU的嵌入式低功耗平台）相比，我们的分布式动作识别系统不仅能达到相同的能耗，而且还能达到TX2的两倍。此外，在图像识别中，音乐厅达到相似的性能并节省动态能量。

##### URL
[https://arxiv.org/abs/1802.02138](https://arxiv.org/abs/1802.02138)

##### PDF
[https://arxiv.org/pdf/1802.02138](https://arxiv.org/pdf/1802.02138)

