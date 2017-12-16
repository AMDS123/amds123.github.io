---
layout: post
title: "Filmy Cloud Removal on Satellite Imagery with Multispectral Conditional Generative Adversarial Nets"
date: 2017-10-13 08:26:13
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Embedding
author: Kenji Enomoto, Ken Sakurada, Weimin Wang, Hiroshi Fukui, Masashi Matsuoka, Ryosuke Nakamura, Nobuo Kawaguchi
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a method for cloud removal from visible light RGB satellite images by extending the conditional Generative Adversarial Networks (cGANs) from RGB images to multispectral images. Satellite images have been widely utilized for various purposes, such as natural environment monitoring (pollution, forest or rivers), transportation improvement and prompt emergency response to disasters. However, the obscurity caused by clouds makes it unstable to monitor the situation on the ground with the visible light camera. Images captured by a longer wavelength are introduced to reduce the effects of clouds. Synthetic Aperture Radar (SAR) is such an example that improves visibility even the clouds exist. On the other hand, the spatial resolution decreases as the wavelength increases. Furthermore, the images captured by long wavelengths differs considerably from those captured by visible light in terms of their appearance. Therefore, we propose a network that can remove clouds and generate visible light images from the multispectral images taken as inputs. This is achieved by extending the input channels of cGANs to be compatible with multispectral images. The networks are trained to output images that are close to the ground truth using the images synthesized with clouds over the ground truth as inputs. In the available dataset, the proportion of images of the forest or the sea is very high, which will introduce bias in the training dataset if uniformly sampled from the original dataset. Thus, we utilize the t-Distributed Stochastic Neighbor Embedding (t-SNE) to improve the problem of bias in the training dataset. Finally, we confirm the feasibility of the proposed network on the dataset of four bands images, which include three visible light bands and one near-infrared (NIR) band.

##### Abstract (translated by Google)
在本文中，我们通过将条件生成对抗网络（cGANs）从RGB图像扩展到多光谱图像，提出了一种从可见光RGB卫星图像去除云的方法。卫星图像被广泛应用于自然环境监测（污染，森林或河流），交通改善和迅速应对灾害等各种目的。然而，由云引起的模糊不清使用可见光照相机监视地面上的情况变得不稳定。引入较长波长的图像以减少云的影响。合成孔径雷达（SAR）就是这样一个例子，即使云存在也能提高能见度。另一方面，空间分辨率随着波长的增加而减小。此外，由长波长捕获的图像在外观上明显不同于可见光捕获的图像。因此，我们提出一个网络，可以消除云，并从作为输入的多光谱图像生成可见光图像。这是通过扩展cGAN的输入通道以与多光谱图像兼容来实现的。这些网络被训练成使用与地面真实上的云合成的图像作为输入来输出接近地面真实的图像。在可用的数据集中，森林或海洋的图像比例非常高，如果从原始数据集中均匀采样，则会在训练数据集中引入偏差。因此，我们利用t分布随机相邻嵌入（t-SNE）来改善训练数据集中的偏倚问题。最后，我们证实了所提出的网络在四个波段图像数据集上的可行性，其中包括三个可见光波段和一个近红外（NIR）波段。

##### URL
[https://arxiv.org/abs/1710.04835](https://arxiv.org/abs/1710.04835)

##### PDF
[https://arxiv.org/pdf/1710.04835](https://arxiv.org/pdf/1710.04835)

