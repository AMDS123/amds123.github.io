---
layout: post
title: "Human Action Localization with Sparse Spatial Supervision"
date: 2017-05-23 19:19:23
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Tracking Detection
author: Philippe Weinzaepfel, Xavier Martin, Cordelia Schmid
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce an approach for spatio-temporal human action localization using sparse spatial supervision. Our method leverages the large amount of annotated humans available today and extracts human tubes by combining a state-of-the-art human detector with a tracking-by-detection approach. Given these high-quality human tubes and temporal supervision, we select positive and negative tubes with very sparse spatial supervision, i.e., only one spatially annotated frame per instance. The selected tubes allow us to effectively learn a spatio-temporal action detector based on dense trajectories or CNNs. We conduct experiments on existing action localization benchmarks: UCF-Sports, J-HMDB and UCF-101. Our results show that our approach, despite using sparse spatial supervision, performs on par with methods using full supervision, i.e., one bounding box annotation per frame. To further validate our method, we introduce DALY (Daily Action Localization in YouTube), a dataset for realistic action localization in space and time. It contains high quality temporal and spatial annotations for 3.6k instances of 10 actions in 31 hours of videos (3.3M frames). It is an order of magnitude larger than existing datasets, with more diversity in appearance and long untrimmed videos.

##### Abstract (translated by Google)
我们引入了一种使用稀疏空间监督的时空人体动作定位方法。我们的方法利用了当今大量可用的注释人类，并通过将最先进的人体检测器与逐个检测方法相结合来提取人体管。鉴于这些高质量的人体管和时间监督，我们选择非常稀疏的空间监督的正面和负面的管，即每个实例只有一个空间注释帧。所选择的管允许我们有效地学习基于密集轨迹或CNN的时空动作检测器。我们在现有的动作本地化基准上进行实验：UCF-Sports，J-HMDB和UCF-101。我们的研究结果表明，尽管采用了稀疏的空间监督，但我们的方法与使用全面监督的方法（即每帧一个边界框注释）相当。为了进一步验证我们的方法，我们引入了DALY（YouTube中的Daily Action Localization），这是一个在空间和时间上实际动作定位的数据集。它包含高质量的时间和空间注释，在31小时的视频（3.3M帧）中，有10个动作的3.6k个实例。它比现有数据集大一个数量级，外观更加多样化，视频长度更长。

##### URL
[https://arxiv.org/abs/1605.05197](https://arxiv.org/abs/1605.05197)

##### PDF
[https://arxiv.org/pdf/1605.05197](https://arxiv.org/pdf/1605.05197)

