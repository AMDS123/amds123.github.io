---
layout: post
title: "Learning to Detect and Track Visible and Occluded Body Joints in a Virtual World"
date: 2018-09-18 14:34:14
categories: arXiv_CV
tags: arXiv_CV Tracking Detection
author: Matteo Fabbri, Fabio Lanzi, Simone Calderara, Andrea Palazzi, Roberto Vezzani, Rita Cucchiara
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-People Tracking in an open-world setting requires a special effort in precise detection. Moreover, temporal continuity in the detection phase gains more importance when scene cluttering introduces the challenging problems of occluded targets. For the purpose, we propose a deep network architecture that jointly extracts people body parts and associates them across short temporal spans. Our model explicitly deals with occluded body parts, by hallucinating plausible solutions of not visible joints. We propose a new end-to-end architecture composed by four branches (visible heatmaps, occluded heatmaps, part affinity fields and temporal affinity fields) fed by a time linker feature extractor. To overcome the lack of surveillance data with tracking, body part and occlusion annotations we created the vastest Computer Graphics dataset for people tracking in urban scenarios by exploiting a photorealistic videogame. It is up to now the vastest dataset (about 500.000 frames, almost 10 million body poses) of human body parts for people tracking in urban scenarios. Our architecture trained on virtual data exhibits good generalization capabilities also on public real tracking benchmarks, when image resolution and sharpness are high enough, producing reliable tracklets useful for further batch data association or re-id modules.

##### Abstract (translated by Google)
在开放世界环境中进行多人跟踪需要特别精确的检测。此外，当场景混乱引入被遮挡目标的挑战性问题时，检测阶段的时间连续性变得更加重要。为此，我们提出了一种深层网络架构，它可以共同提取人体部位，并将它们与短时间跨度相关联。我们的模型通过幻觉不可见关节的合理解决方案明确地处理闭塞的身体部位。我们提出了一种新的端到端架构，由四个分支（可见热图，遮挡热图，部分亲和场和时间亲和场）组成，由时间链接器特征提取器提供。为了通过跟踪，身体部位和遮挡注释来克服缺乏监控数据，我们通过利用逼真的视频游戏为人们在城市场景中跟踪创建了最快的计算机图形数据集。到目前为止，人体零件的最快数据集（约500,000帧，近1000万个身体姿势）供人们在城市场景中跟踪。我们的虚拟数据架构在公共实际跟踪基准测试中表现出良好的泛化能力，当图像分辨率和清晰度足够高时，可生成可用于进一步批量数据关联或重新模块的可靠跟踪。

##### URL
[http://arxiv.org/abs/1803.08319](http://arxiv.org/abs/1803.08319)

##### PDF
[http://arxiv.org/pdf/1803.08319](http://arxiv.org/pdf/1803.08319)

