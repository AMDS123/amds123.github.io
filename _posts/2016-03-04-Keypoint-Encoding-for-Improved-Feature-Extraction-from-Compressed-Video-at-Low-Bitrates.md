---
layout: post
title: "Keypoint Encoding for Improved Feature Extraction from Compressed Video at Low Bitrates"
date: 2016-03-04 16:43:42
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Detection
author: Jianshu Chao, Eckehard Steinbach
mathjax: true
---

* content
{:toc}

##### Abstract
In many mobile visual analysis applications, compressed video is transmitted over a communication network and analyzed by a server. Typical processing steps performed at the server include keypoint detection, descriptor calculation, and feature matching. Video compression has been shown to have an adverse effect on feature-matching performance. The negative impact of compression can be reduced by using the keypoints extracted from the uncompressed video to calculate descriptors from the compressed video. Based on this observation, we propose to provide these keypoints to the server as side information and to extract only the descriptors from the compressed video. First, we introduce four different frame types for keypoint encoding to address different types of changes in video content. These frame types represent a new scene, the same scene, a slowly changing scene, or a rapidly moving scene and are determined by comparing features between successive video frames. Then, we propose Intra, Skip and Inter modes of encoding the keypoints for different frame types. For example, keypoints for new scenes are encoded using the Intra mode, and keypoints for unchanged scenes are skipped. As a result, the bitrate of the side information related to keypoint encoding is significantly reduced. Finally, we present pairwise matching and image retrieval experiments conducted to evaluate the performance of the proposed approach using the Stanford mobile augmented reality dataset and 720p format videos. The results show that the proposed approach offers significantly improved feature matching and image retrieval performance at a given bitrate.

##### Abstract (translated by Google)
在许多移动视觉分析应用中，压缩视频通过通信网络传输并由服务器分析。在服务器上执行的典型处理步骤包括关键点检测，描述符计算和特征匹配。已经显示视频压缩对特征匹配性能具有不利影响。通过使用从未压缩视频中提取的关键点来计算来自压缩视频的描述符，可以降低压缩的负面影响。基于这一观察，我们建议将这些关键点作为辅助信息提供给服务器，并仅从压缩视频中提取描述符。首先，我们为关键点编码引入四种不同的帧类型，以解决视频内容中不同类型的变化。这些帧类型表示新的场景，相同的场景，缓慢变化的场景或快速移动的场景，并且通过比较连续视频帧之间的特征来确定。然后，我们提出了Intra，Skip和Inter模式对不同帧类型的关键点进行编码。例如，使用帧内模式对新场景的关键点进行编码，并且跳过不变场景的关键点。结果，与关键点编码相关的辅助信息的比特率显着降低。最后，我们提出了成对匹配和图像检索实验来评估所提出的方法使用斯坦福移动增强现实数据集和720p格式视频的性能。结果表明，所提出的方法在给定比特率下提供显着改进的特征匹配和图像检索性能。

##### URL
[https://arxiv.org/abs/1506.08316](https://arxiv.org/abs/1506.08316)

##### PDF
[https://arxiv.org/pdf/1506.08316](https://arxiv.org/pdf/1506.08316)

