---
layout: post
title: "Deep Smoke Segmentation"
date: 2018-09-04 02:48:28
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Optimization Detection
author: Feiniu Yuan, Lin Zhang, Xue Xia, Boyang Wan, Qinghua Huang, Xuelong Li
mathjax: true
---

* content
{:toc}

##### Abstract
Inspired by the recent success of fully convolutional networks (FCN) in semantic segmentation, we propose a deep smoke segmentation network to infer high quality segmentation masks from blurry smoke images. To overcome large variations in texture, color and shape of smoke appearance, we divide the proposed network into a coarse path and a fine path. The first path is an encoder-decoder FCN with skip structures, which extracts global context information of smoke and accordingly generates a coarse segmentation mask. To retain fine spatial details of smoke, the second path is also designed as an encoder-decoder FCN with skip structures, but it is shallower than the first path network. Finally, we propose a very small network containing only add, convolution and activation layers to fuse the results of the two paths. Thus, we can easily train the proposed network end to end for simultaneous optimization of network parameters. To avoid the difficulty in manually labelling fuzzy smoke objects, we propose a method to generate synthetic smoke images. According to results of our deep segmentation method, we can easily and accurately perform smoke detection from videos. Experiments on three synthetic smoke datasets and a realistic smoke dataset show that our method achieves much better performance than state-of-the-art segmentation algorithms based on FCNs. Test results of our method on videos are also appealing.

##### Abstract (translated by Google)
受最近完全卷积网络（FCN）在语义分割中的成功启发，我们提出了一种深度烟雾分割网络，用于从模糊烟雾图像中推断出高质量的分割掩模。为了克服烟雾外观的纹理，颜色和形状的巨大变化，我们将所提出的网络划分为粗略路径和精细路径。第一路径是具有跳过结构的编码器 - 解码器FCN，其提取烟雾的全局上下文信息并因此生成粗略分段掩码。为了保留烟雾的精细空间细节，第二条路径也被设计为具有跳过结构的编码器 - 解码器FCN，但它比第一路径网络浅。最后，我们提出了一个非常小的网络，只包含加法，卷积和激活层来融合两条路径的结果。因此，我们可以轻松地端到端地训练所提出的网络，以同时优化网络参数。为了避免手动标记模糊烟雾对象的困难，我们提出了一种生成合成烟雾图像的方法。根据我们的深度分割方法的结果，我们可以轻松准确地从视频中执行烟雾检测。对三个合成烟雾数据集和真实烟雾数据集的实验表明，我们的方法比基于FCN的最先进的分割算法实现了更好的性能。我们的视频方法的测试结果也很吸引人。

##### URL
[http://arxiv.org/abs/1809.00774](http://arxiv.org/abs/1809.00774)

##### PDF
[http://arxiv.org/pdf/1809.00774](http://arxiv.org/pdf/1809.00774)

