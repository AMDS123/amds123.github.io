---
layout: post
title: "Hand-held Video Deblurring via Efficient Fourier Aggregation"
date: 2015-12-04 15:22:25
categories: arXiv_CV
tags: arXiv_CV
author: Mauricio Delbracio, Guillermo Sapiro
mathjax: true
---

* content
{:toc}

##### Abstract
Videos captured with hand-held cameras often suffer from a significant amount of blur, mainly caused by the inevitable natural tremor of the photographer's hand. In this work, we present an algorithm that removes blur due to camera shake by combining information in the Fourier domain from nearby frames in a video. The dynamic nature of typical videos with the presence of multiple moving objects and occlusions makes this problem of camera shake removal extremely challenging, in particular when low complexity is needed. Given an input video frame, we first create a consistent registered version of temporally adjacent frames. Then, the set of consistently registered frames is block-wise fused in the Fourier domain with weights depending on the Fourier spectrum magnitude. The method is motivated from the physiological fact that camera shake blur has a random nature and therefore, nearby video frames are generally blurred differently. Experiments with numerous videos recorded in the wild, along with extensive comparisons, show that the proposed algorithm achieves state-of-the-art results while at the same time being much faster than its competitors.

##### Abstract (translated by Google)
用手持相机拍摄的视频经常会有大量的模糊，这主要是由摄影师手部的不可避免的自然震颤引起的。在这项工作中，我们提出了一种算法，通过结合视频中来自附近帧的傅立叶域中的信息来消除由于相机抖动造成的模糊。典型的视频具有多个移动对象和遮挡的动态性质使得这种去除相机抖动的问题极具挑战性，特别是当需要低复杂度时。给定一个输入视频帧，我们首先创建一个时间上相邻帧的一致注册版本。然后，在傅立叶域中，一致地注册的帧的集合按照傅里叶频谱幅度的权重进行块式融合。该方法受到生理事实的启发，即相机抖动模糊具有随机性，因此，附近的视频帧通常模糊不清。在野外录制的大量视频的实验以及广泛的比较表明，所提出的算法实现了最先进的结果，同时比竞争对手快得多。

##### URL
[https://arxiv.org/abs/1509.05251](https://arxiv.org/abs/1509.05251)

##### PDF
[https://arxiv.org/pdf/1509.05251](https://arxiv.org/pdf/1509.05251)

