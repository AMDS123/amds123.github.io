---
layout: post
title: "Hide and Seek tracker: Real-time recovery from target loss"
date: 2018-06-20 17:09:02
categories: arXiv_CV
tags: arXiv_CV Tracking Detection
author: Alessandro Bay, Panagiotis Sidiropoulos, Eduard Vazquez, Michele Sasdelli
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we examine the real-time recovery of a video tracker from a target loss, using information that is already available from the original tracker and without a significant computational overhead. More specifically, before using the tracker output to update the target position we estimate the detection confidence. In the case of a low confidence, the position update is rejected and the tracker passes to a single-frame failure mode, during which the patch low-level visual content is used to swiftly update the object position, before recovering from the target loss in the next frame. Orthogonally to this improvement, we further enhance the running average method used for creating the query model in tracking-through-similarity. The experimental evidence provided by evaluation on standard tracking datasets (OTB-50, OTB-100 and OTB-2013) validate that target recovery can be successfully achieved without compromising the real-time update of the target position.

##### Abstract (translated by Google)
在本白皮书中，我们使用原始跟踪器中已有的信息，并且没有显着的计算开销，从视频丢失中检查视频跟踪器的实时恢复。更具体地说，在使用跟踪器输出来更新目标位置之前，我们估计检测置信度。在置信度较低的情况下，位置更新被拒绝并且跟踪器转到单帧失败模式，在此期间，在从目标丢失恢复之前，使用修补程序底层视觉内容来快速更新对象位置下一帧。与此改进正交的是，我们进一步增强了用于在跟踪相似度中创建查询模型的运行平均方法。通过对标准跟踪数据集（OTB-50，OTB-100和OTB-2013）进行评估所提供的实验证据证实，可以成功实现目标恢复，而不影响目标位置的实时更新。

##### URL
[http://arxiv.org/abs/1806.07844](http://arxiv.org/abs/1806.07844)

##### PDF
[http://arxiv.org/pdf/1806.07844](http://arxiv.org/pdf/1806.07844)

