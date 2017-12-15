---
layout: post
title: "Understanding and Diagnosing Visual Tracking Systems"
date: 2015-04-23 06:37:29
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Naiyan Wang, Jianping Shi, Dit-Yan Yeung, Jiaya Jia
mathjax: true
---

* content
{:toc}

##### Abstract
Several benchmark datasets for visual tracking research have been proposed in recent years. Despite their usefulness, whether they are sufficient for understanding and diagnosing the strengths and weaknesses of different trackers remains questionable. To address this issue, we propose a framework by breaking a tracker down into five constituent parts, namely, motion model, feature extractor, observation model, model updater, and ensemble post-processor. We then conduct ablative experiments on each component to study how it affects the overall result. Surprisingly, our findings are discrepant with some common beliefs in the visual tracking research community. We find that the feature extractor plays the most important role in a tracker. On the other hand, although the observation model is the focus of many studies, we find that it often brings no significant improvement. Moreover, the motion model and model updater contain many details that could affect the result. Also, the ensemble post-processor can improve the result substantially when the constituent trackers have high diversity. Based on our findings, we put together some very elementary building blocks to give a basic tracker which is competitive in performance to the state-of-the-art trackers. We believe our framework can provide a solid baseline when conducting controlled experiments for visual tracking research.

##### Abstract (translated by Google)
近年来提出了几种用于视觉跟踪研究的基准数据集。尽管它们有用，但它们是否足以理解和诊断不同跟踪器的优缺点仍然值得怀疑。为了解决这个问题，我们提出了一个框架，把跟踪器分成运动模型，特征提取器，观察模型，模型更新器和集成后处理器五个组成部分。然后，我们对每个组件进行烧蚀实验，研究它是如何影响整体结果的。令人惊讶的是，我们的发现与视觉追踪研究界的一些共同信念是不一致的。我们发现特征提取器在跟踪器中扮演着最重要的角色。另一方面，尽管观察模型是许多研究的重点，但我们发现它往往没有显着的改善。此外，运动模型和模型更新包含许多可能影响结果的细节。另外，当组成跟踪器具有高度的多样性时，集成后处理器可以大大改善结果。根据我们的研究结果，我们将一些非常基本的构建块放在一起，以提供一个跟最先进的跟踪器相比具有竞争力的基本跟踪器。我们相信，我们的框架可以为进行视觉跟踪研究的受控实验提供一个坚实的基线。

##### URL
[https://arxiv.org/abs/1504.06055](https://arxiv.org/abs/1504.06055)

##### PDF
[https://arxiv.org/pdf/1504.06055](https://arxiv.org/pdf/1504.06055)

