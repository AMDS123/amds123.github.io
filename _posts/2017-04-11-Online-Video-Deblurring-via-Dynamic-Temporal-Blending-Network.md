---
layout: post
title: "Online Video Deblurring via Dynamic Temporal Blending Network"
date: 2017-04-11 13:41:50
categories: arXiv_CV
tags: arXiv_CV
author: Tae Hyun Kim, Kyoung Mu Lee, Bernhard Schölkopf, Michael Hirsch
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art video deblurring methods are capable of removing non-uniform blur caused by unwanted camera shake and/or object motion in dynamic scenes. However, most existing methods are based on batch processing and thus need access to all recorded frames, rendering them computationally demanding and time consuming and thus limiting their practical use. In contrast, we propose an online (sequential) video deblurring method based on a spatio-temporal recurrent network that allows for real-time performance. In particular, we introduce a novel architecture which extends the receptive field while keeping the overall size of the network small to enable fast execution. In doing so, our network is able to remove even large blur caused by strong camera shake and/or fast moving objects. Furthermore, we propose a novel network layer that enforces temporal consistency between consecutive frames by dynamic temporal blending which compares and adaptively (at test time) shares features obtained at different time steps. We show the superiority of the proposed method in an extensive experimental evaluation.

##### Abstract (translated by Google)
现有技术的视频去模糊方法能够去除在动态场景中由不想要的相机抖动和/或物体移动引起的不均匀模糊。然而，大多数现有的方法是基于批量处理的，因此需要访问所有记录的帧，使得它们在计算上耗费时间并且因此限制了它们的实际使用。相反，我们提出一种基于时空循环网络的在线（顺序）视频去模糊方法，其允许实时性能。特别是，我们引入了一种新颖的架构，扩展了接受领域，同时保持网络的整体规模小，以实现快速执行。这样做，我们的网络能够消除强烈的相机震动和/或快速移动的物体造成的大的模糊。此外，我们提出了一种新的网络层，通过动态时间混合来实现连续帧之间的时间一致性，该时间混合比较和自适应地（在测试时间）共享在不同时间步骤获得的特征。我们在广泛的实验评估中展示了所提出方法的优越性。

##### URL
[https://arxiv.org/abs/1704.03285](https://arxiv.org/abs/1704.03285)

##### PDF
[https://arxiv.org/pdf/1704.03285](https://arxiv.org/pdf/1704.03285)

