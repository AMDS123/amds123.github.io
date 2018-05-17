---
layout: post
title: "Photorealistic Image Reconstruction from Hybrid Intensity and Event based Sensor"
date: 2018-05-16 05:49:25
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Prasan A Shedligeri, Ketul Shah, Dhruv Kumar, Kaushik Mitra
mathjax: true
---

* content
{:toc}

##### Abstract
Event based sensors encode pixel wise contrast changes as positive or negative events at the instant they occur. This paradigm shift away from conventional image sensors provides advantages like low bandwidth requirement, low operating power requirement and low latency. However, in the process of encoding these contrast changes most of the spatial intensity information is lost. Previously there have been attempts at recovering this lost intensity information directly from the event data. Although the results are promising they lack the texture and the consistency of natural videos. We propose to reconstruct photorealistic intensity images by using a low frame rate conventional camera along with the event sensor. The low frame rate conventional camera provides us with texture-rich information, while the event sensor provides us with dense temporal measurements. We combine the strength of both by warping the low-frame rate video to intermediate locations where we only have event sensor data, resulting in high frame rate video. For accomplishing this task, we need the knowledge of scene depth and dense ego-motion estimates. We propose to use an unsupervised, learning free method to estimate depth from low-frame rate images. Unlike previous works, instead of estimating ego-motion directly from events, we propose an autoencoder based model to map events to pseudo-intensity frames. Using pseudo-intensity frames as input, we propose an unsupervised, learning free method adapted from Deep Image Prior to estimate the sensor ego-motion. Finally, we demonstrate photo-realistic reconstructions on a real hybrid sensor (DAVIS) dataset.

##### Abstract (translated by Google)
基于事件的传感器将像素明显的对比度变化编码为正或负事件发生时的瞬间。与传统图像传感器相比，这种模式转变提供了低带宽要求，低运行功耗要求和低延迟等优势。但是，在编码这些对比度变化的过程中，大部分空间强度信息都会丢失。以前一直试图直接从事件数据中恢复丢失的强度信息。虽然结果很有希望，但它们缺乏自然视频的质感和一致性。我们建议通过使用低帧率传统相机和事件传感器来重建照片级强度图像。低帧率传统相机为我们提供了丰富的纹理信息，而事件传感器为我们提供了密集的时间测量。我们通过将低帧速率视频扭曲到只有事件传感器数据的中间位置来结合两者的优势，从而获得高帧速率视频。为了完成这个任务，我们需要了解场景深度和密集的自我运动估计。我们建议使用无监督的免学习方法来估计低帧速率图像的深度。与以前的作品不同，我们不是直接从事件来估计自我运动，而是提出一个基于自动编码器的模型来将事件映射到伪强度帧。使用伪强度帧作为输入，我们提出了一种无监督的免学习方法，由Deep Image Prior调整以估计传感器的自我运动。最后，我们在真实的混合传感器（DAVIS）数据集上演示照片般逼真的重建。

##### URL
[http://arxiv.org/abs/1805.06140](http://arxiv.org/abs/1805.06140)

##### PDF
[http://arxiv.org/pdf/1805.06140](http://arxiv.org/pdf/1805.06140)

