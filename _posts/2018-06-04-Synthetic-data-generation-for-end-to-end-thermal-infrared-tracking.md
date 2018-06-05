---
layout: post
title: "Synthetic data generation for end-to-end thermal infrared tracking"
date: 2018-06-04 08:52:28
categories: arXiv_CV
tags: arXiv_CV Knowledge Tracking CNN
author: Lichao Zhang, Abel Gonzalez-Garcia, Joost van de Weijer, Martin Danelljan, Fahad Shahbaz Khan
mathjax: true
---

* content
{:toc}

##### Abstract
The usage of both off-the-shelf and end-to-end trained deep networks have significantly improved performance of visual tracking on RGB videos. However, the lack of large labeled datasets hampers the usage of convolutional neural networks for tracking in thermal infrared (TIR) images. Therefore, most state of the art methods on tracking for TIR data are still based on handcrafted features. To address this problem, we propose to use image-to-image translation models. These models allow us to translate the abundantly available labeled RGB data to synthetic TIR data. We explore both the usage of paired and unpaired image translation models for this purpose. These methods provide us with a large labeled dataset of synthetic TIR sequences, on which we can train end-to-end optimal features for tracking. To the best of our knowledge we are the first to train end-to-end features for TIR tracking. We perform extensive experiments on VOT-TIR2017 dataset. We show that a network trained on a large dataset of synthetic TIR data obtains better performance than one trained on the available real TIR data. Combining both data sources leads to further improvement. In addition, when we combine the network with motion features we outperform the state of the art with a relative gain of over 10%, clearly showing the efficiency of using synthetic data to train end-to-end TIR trackers.

##### Abstract (translated by Google)
现成的和端到端训练的深度网络的使用显着提高了RGB视频的视觉跟踪性能。然而，缺乏大型标记数据集阻碍了卷积神经网络在热红外（TIR）图像中的跟踪使用。因此，跟踪TIR数据的最先进的方法仍然基于手工制作的特征。为了解决这个问题，我们建议使用图像到图像的翻译模型。这些模型使我们能够将丰富的标记RGB数据转换为合成TIR数据。我们为此探索了配对和不配对图像翻译模型的使用。这些方法为我们提供了合成TIR序列的大型标记数据集，我们可以在这些数据集上训练端到端的最佳跟踪特征。据我们所知，我们是第一个培训端到端TIR跟踪功能的人。我们对VOT-TIR2017数据集进行了大量实验。我们表明，在合成TIR数据的大型数据集上训练的网络比在可用真实TIR数据上训练的人获得更好的性能。结合这两种数据源可以进一步改进。此外，当我们将网络与运动特征相结合时，我们的表现优于现有技术，相对增益超过10％，清楚地显示了使用合成数据训练端到端TIR跟踪器的效率。

##### URL
[http://arxiv.org/abs/1806.01013](http://arxiv.org/abs/1806.01013)

##### PDF
[http://arxiv.org/pdf/1806.01013](http://arxiv.org/pdf/1806.01013)

