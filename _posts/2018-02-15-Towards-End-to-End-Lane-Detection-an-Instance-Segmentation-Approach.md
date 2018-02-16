---
layout: post
title: "Towards End-to-End Lane Detection: an Instance Segmentation Approach"
date: 2018-02-15 15:09:19
categories: arXiv_CV
tags: arXiv_CV Segmentation Deep_Learning Detection
author: Davy Neven, Bert De Brabandere, Stamatios Georgoulis, Marc Proesmans, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
Modern cars are incorporating an increasing number of driver assist features, among which automatic lane keeping. The latter allows the car to properly position itself within the road lanes, which is also crucial for any subsequent lane departure or trajectory planning decision in fully autonomous cars. Traditional lane detection methods rely on a combination of highly-specialized, hand-crafted features and heuristics, usually followed by post-processing techniques, that are computationally expensive and prone to scalability due to road scene variations. More recent approaches leverage deep learning models, trained for pixel-wise lane segmentation, even when no markings are present in the image due to their big receptive field. Despite their advantages, these methods are limited to detecting a pre-defined, fixed number of lanes, e.g. ego-lanes, and can not cope with lane changes. In this paper, we go beyond the aforementioned limitations and propose to cast the lane detection problem as an instance segmentation problem - in which each lane forms its own instance - that can be trained end-to-end. To parametrize the segmented lane instances before fitting the lane, we further propose to apply a learned perspective transformation, conditioned on the image, in contrast to a fixed "bird's-eye view" transformation. By doing so, we ensure a lane fitting which is robust against road plane changes, unlike existing approaches that rely on a fixed, pre-defined transformation. In summary, we propose a fast lane detection algorithm, running at 50 fps, which can handle a variable number of lanes and cope with lane changes. We verify our method on the tuSimple dataset and achieve competitive results.

##### Abstract (translated by Google)
现代汽车正在加入越来越多的驾驶辅助功能，其中包括自动车道保持功能。后者允许汽车将其自身正确定位在道路车道内，这对于完全自动化汽车中的任何随后的车道偏离或轨迹规划决定也是重要的。传统的车道检测方法依赖于高度专业化的手工特征和启发式技术的组合，后者通常采用后处理技术，这些技术计算昂贵，并且由于道路场景的变化而易于扩展。更近期的方法利用深度学习模型，即使在图像中由于其较大的接受场而没有标记时，也可针对逐像素车道分割进行训练。尽管它们有优点，但这些方法仅限于检测预定义的固定数量的车道，例如，自我通道，并且不能应付车道变化。在本文中，我们超越了上述限制，并提出将车道检测问题作为一个实例分割问题 - 其中每个车道形成自己的实例 - 可以进行端到端的训练。为了在拟合车道之前对分段的车道实例进行参数化，我们进一步建议应用以图像为条件的学习透视变换，而不是固定的“鸟瞰图”变换。通过这样做，我们确保了对道路平面变化具有鲁棒性的车道拟合，而不像依赖于固定的预定义变换的现有方法。总之，我们提出了一种快速车道检测算法，运行速度为50 fps，可以处理不同数量的车道并应对车道变化。我们在tuSimple数据集上验证了我们的方法并获得了有竞争力的结果。

##### URL
[https://arxiv.org/abs/1802.05591](https://arxiv.org/abs/1802.05591)

##### PDF
[https://arxiv.org/pdf/1802.05591](https://arxiv.org/pdf/1802.05591)

