---
layout: post
title: "Real-Time End-to-End Action Detection with Two-Stream Networks"
date: 2018-02-23 02:21:46
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Detection Recognition
author: Alaaeldin El-Nouby, Graham W. Taylor
mathjax: true
---

* content
{:toc}

##### Abstract
Two-stream networks have been very successful for solving the problem of action detection. However, prior work using two-stream networks train both streams separately, which prevents the network from exploiting regularities between the two streams. Moreover, unlike the visual stream, the dominant forms of optical flow computation typically do not maximally exploit GPU parallelism. We present a real-time end-to-end trainable two-stream network for action detection. First, we integrate the optical flow computation in our framework by using Flownet2. Second, we apply early fusion for the two streams and train the whole pipeline jointly end-to-end. Finally, for better network initialization, we transfer from the task of action recognition to action detection by pre-training our framework using the recently released large-scale Kinetics dataset. Our experimental results show that training the pipeline jointly end-to-end with fine-tuning the optical flow for the objective of action detection improves detection performance significantly. Additionally, we observe an improvement when initializing with parameters pre-trained using Kinetics. Last, we show that by integrating the optical flow computation, our framework is more efficient, running at real-time speeds (up to 31 fps).

##### Abstract (translated by Google)
双流网络在解决动作检测问题方面非常成功。然而，之前使用双流网络的工作分别对两个流进行训练，这阻止了网络利用两个流之间的规律性。而且，与视觉流不同，光流计算的主要形式通常不会最大程度地利用GPU并行性。我们提供了一个实时的端到端可训练双流网络来进行动作检测。首先，我们使用Flownet2将光流计算集成到我们的框架中。其次，我们对两条流进行早期融合，并将整个流水线端到端地进行联合训练。最后，为了更好的网络初始化，我们通过使用最近发布的大规模动力学数据集对我们的框架进行预训练，从动作识别任务转移到动作检测。我们的实验结果表明，为了动作检测的目标，端到端联合训练流水线和微调光流，显着提高了检测性能。此外，我们观察到使用动力学预先训练参数进行初始化时的改进。最后，我们展示了通过集成光流计算，我们的框架更加高效，以实时速度运行（高达31 fps）。

##### URL
[http://arxiv.org/abs/1802.08362](http://arxiv.org/abs/1802.08362)

##### PDF
[http://arxiv.org/pdf/1802.08362](http://arxiv.org/pdf/1802.08362)

