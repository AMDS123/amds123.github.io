---
layout: post
title: "Tracking Randomly Moving Objects on Edge Box Proposals"
date: 2015-11-29 23:51:02
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Detection
author: Gao Zhu, Fatih Porikli, Hongdong Li
mathjax: true
---

* content
{:toc}

##### Abstract
Most tracking-by-detection methods employ a local search window around the predicted object location in the current frame assuming the previous location is accurate, the trajectory is smooth, and the computational capacity permits a search radius that can accommodate the maximum speed yet small enough to reduce mismatches. These, however, may not be valid always, in particular for fast and irregularly moving objects. Here, we present an object tracker that is not limited to a local search window and has ability to probe efficiently the entire frame. Our method generates a small number of "high-quality" proposals by a novel instance-specific objectness measure and evaluates them against the object model that can be adopted from an existing tracking-by-detection approach as a core tracker. During the tracking process, we update the object model concentrating on hard false-positives supplied by the proposals, which help suppressing distractors caused by difficult background clutters, and learn how to re-rank proposals according to the object model. Since we reduce significantly the number of hypotheses the core tracker evaluates, we can use richer object descriptors and stronger detector. Our method outperforms most recent state-of-the-art trackers on popular tracking benchmarks, and provides improved robustness for fast moving objects as well as for ultra low-frame-rate videos.

##### Abstract (translated by Google)
大多数逐行检测方法在当前帧的预测对象位置周围使用本地搜索窗口，前提是前一个位置是准确的，轨迹是平滑的，计算容量允许搜索半径可以容纳最大速度但足够小减少错配。然而，这些可能并不总是有效的，特别是对于快速和不规则移动的物体。在这里，我们提出一个不局限于本地搜索窗口的对象跟踪器，并且能够有效地探测整个帧。我们的方法通过一个新颖的特定于实例的对象度量来生成少量的“高质量”提议，并根据可以从现有的逐个检测方法作为核心跟踪器所采用的对象模型对它们进行评估。在跟踪过程中，我们更新了针对提案提供的硬性误报的对象模型，这些模型有助于抑制由背景混乱造成的干扰，并学习如何根据对象模型重新排列提议。由于我们大大减少了核心跟踪器评估的假设数量，我们可以使用更丰富的对象描述符和更强的检测器。我们的方法在流行的跟踪基准测试中胜过了最新的最先进的跟踪器，并且为快速移动的对象以及超低帧频视频提供了改进的鲁棒性。

##### URL
[https://arxiv.org/abs/1507.08085](https://arxiv.org/abs/1507.08085)

##### PDF
[https://arxiv.org/pdf/1507.08085](https://arxiv.org/pdf/1507.08085)

