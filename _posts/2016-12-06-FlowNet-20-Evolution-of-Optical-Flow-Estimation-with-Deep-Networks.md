---
layout: post
title: "FlowNet 2.0: Evolution of Optical Flow Estimation with Deep Networks"
date: 2016-12-06 17:52:47
categories: arXiv_CV
tags: arXiv_CV
author: Eddy Ilg, Nikolaus Mayer, Tonmoy Saikia, Margret Keuper, Alexey Dosovitskiy, Thomas Brox
mathjax: true
---

* content
{:toc}

##### Abstract
The FlowNet demonstrated that optical flow estimation can be cast as a learning problem. However, the state of the art with regard to the quality of the flow has still been defined by traditional methods. Particularly on small displacements and real-world data, FlowNet cannot compete with variational methods. In this paper, we advance the concept of end-to-end learning of optical flow and make it work really well. The large improvements in quality and speed are caused by three major contributions: first, we focus on the training data and show that the schedule of presenting data during training is very important. Second, we develop a stacked architecture that includes warping of the second image with intermediate optical flow. Third, we elaborate on small displacements by introducing a sub-network specializing on small motions. FlowNet 2.0 is only marginally slower than the original FlowNet but decreases the estimation error by more than 50%. It performs on par with state-of-the-art methods, while running at interactive frame rates. Moreover, we present faster variants that allow optical flow computation at up to 140fps with accuracy matching the original FlowNet.

##### Abstract (translated by Google)
FlowNet表明，光学流量估算可以作为一个学习问题。然而，关于流量质量的现有技术仍然由传统的方法来定义。特别是在小位移和实际数据方面，FlowNet无法与变分方法竞争。在本文中，我们提出了光流端到端学习的概念，并使其工作得很好。质量和速度的巨大提高是由三个主要的贡献造成的：首先，我们关注训练数据，显示训练期间提交数据的时间表非常重要。其次，我们开发了一种叠加架构，其中包括中间光流的第二个图像的翘曲。第三，我们通过引入一个专门研究小动作的子网络来阐述小的位移。 FlowNet 2.0只比原始的FlowNet稍微慢一些，但是估计误差减少了50％以上。它与最先进的方法相媲美，同时以交互式帧率运行。此外，我们提供更快速的变体，使流量计算速度高达140fps，并且与原始的FlowNet相匹配。

##### URL
[https://arxiv.org/abs/1612.01925](https://arxiv.org/abs/1612.01925)

##### PDF
[https://arxiv.org/pdf/1612.01925](https://arxiv.org/pdf/1612.01925)

