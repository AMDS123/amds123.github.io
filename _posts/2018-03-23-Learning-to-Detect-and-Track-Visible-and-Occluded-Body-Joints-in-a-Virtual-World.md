---
layout: post
title: "Learning to Detect and Track Visible and Occluded Body Joints in a Virtual World"
date: 2018-03-23 10:37:34
categories: arXiv_CV
tags: arXiv_CV Tracking Detection
author: Matteo Fabbri, Fabio Lanzi, Simone Calderara, Andrea Palazzi, Roberto Vezzani, Rita Cucchiara
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-People Tracking in an open-world setting requires a special effort in precise detection. Moreover, temporal continuity in the detection phase gains more importance when scene cluttering introduces the challenging problems of occluded targets. For the purpose, we propose a deep network architecture that jointly extracts people body parts and associates them across short temporal spans. Our model explicitly deals with occluded body parts, by hallucinating plausible solutions of not visible joints. We propose a new end-to-end architecture composed by four branches (\textit{visible heatmaps}, \textit{occluded heatmaps}, \textit{part affinity fields} and \textit{temporal affinity fields}) fed by a \textit{time linker} feature extractor. To overcome the lack of surveillance data with tracking, body part and occlusion annotations we created the vastest Computer Graphics dataset for people tracking in urban scenarios by exploiting a photorealistic videogame. It is up to now the vastest dataset (about 500.000 frames, more than 10 million body poses) of human body parts for people tracking in urban scenarios. Our architecture trained on virtual data exhibits good generalization capabilities also on public real tracking benchmarks, when image resolution and sharpness are high enough, producing reliable tracklets useful for further batch data association or re-id modules.

##### Abstract (translated by Google)
在开放的世界环境中进行多人追踪需要特别的努力来进行精确的检测。此外，当场景混乱引入遮挡目标的挑战性问题时，检测阶段的时间连续性变得更加重要。为此，我们提出了一个深度网络体系结构，它可以共同提取人体部位，并在短暂的时间跨度内将它们关联起来。我们的模型明确地处理闭塞的身体部位，通过幻觉看不见关节的合理解决方案。我们提出了由\ textit提供的四个分支（\ textit {可见heatmaps}，\ textit {occluded heatmaps}，\ textit {零件关联字段}和\ textit {时间关联字段}）组成的新的端到端体系结构{时间链接器}功能提取器。为了克服跟踪，身体部分和遮挡注释缺乏监视数据，我们创建了最快的计算机图形数据集，用于人们在城市场景中进行跟踪，通过利用真实感的视频游戏。它是迄今为止在城市情景下追踪人体的最快数据集（约500,000帧，超过1000万个身体姿态）。我们在虚拟数据方面进行培训的体系结构在公共实际跟踪基准上展现出良好的泛化能力，当图像分辨率和清晰度足够高时，可生成可用于进一步批量数据关联或重新标识模块的可靠tracklets。

##### URL
[https://arxiv.org/abs/1803.08319](https://arxiv.org/abs/1803.08319)

##### PDF
[https://arxiv.org/pdf/1803.08319](https://arxiv.org/pdf/1803.08319)

