---
layout: post
title: "REST: Real-to-Synthetic Transform for Illumination Invariant Camera Localization"
date: 2018-03-26 07:36:11
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Sota Shoman, Tomohiro Mashita, Alexander Plopski, Photchara Ratsamee, Yuki Uranishi, Haruo Takemura
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate camera localization is an essential part of tracking systems. However, localization results are greatly affected by illumination. Including data collected under various lighting conditions can improve the robustness of the localization algorithm to lighting variation. However, this is very tedious and time consuming. By using synthesized images it is possible to easily accumulate a large variety of views under varying illumination and weather conditions. Despite continuously improving processing power and rendering algorithms, synthesized images do not perfectly match real images of the same scene, i.e. there exists a gap between real and synthesized images that also affects the accuracy of camera localization. To reduce the impact of this gap, we introduce "REal-to-Synthetic Transform (REST)." REST is an autoencoder-like network that converts real features to their synthetic counterpart. The converted features can then be matched against the accumulated database for robust camera localization. In our experiments REST improved feature matching accuracy under variable lighting conditions by approximately 30%. Moreover, our system outperforms state of the art CNN-based camera localization methods trained with synthetic images. We believe our method could be used to initialize local tracking and to simplify data accumulation for lighting robust localization.

##### Abstract (translated by Google)
准确的相机定位是跟踪系统的重要组成部分。但是，本地化结果受照明影响很大。包括在各种照明条件下收集的数据可以提高定位算法对照明变化的鲁棒性。但是，这是非常乏味和耗时的。通过使用合成图像，可以在变化的照明和天气条件下轻松聚集各种视图。尽管不断提高处理能力和渲染算法，但合成图像并不能完美匹配同一场景的真实图像，即真实图像和合成图像之间存在差距，这也会影响相机定位的准确性。为了减少这种差距的影响，我们引入了“实数到合成变换（REST）”。 REST是一种类似于自动编码器的网络，可将真实特征转换为合成对象。然后可以将转换后的功能与累积数据库进行匹配，以获得稳定的相机定位。在我们的实验中，REST改进了可变光照条件下的特征匹配精度约30％。此外，我们的系统胜过了用合成图像训练的基于CNN的相机定位方法。我们相信我们的方法可用于初始化本地跟踪并简化照明稳健本地化的数据积累。

##### URL
[https://arxiv.org/abs/1803.09448](https://arxiv.org/abs/1803.09448)

##### PDF
[https://arxiv.org/pdf/1803.09448](https://arxiv.org/pdf/1803.09448)

