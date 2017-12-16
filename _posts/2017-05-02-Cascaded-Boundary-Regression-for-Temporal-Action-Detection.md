---
layout: post
title: "Cascaded Boundary Regression for Temporal Action Detection"
date: 2017-05-02 21:45:21
categories: arXiv_CV
tags: arXiv_CV Salient Detection
author: Jiyang Gao, Zhenheng Yang, Ram Nevatia
mathjax: true
---

* content
{:toc}

##### Abstract
Temporal action detection in long videos is an important problem. State-of-the-art methods address this problem by applying action classifiers on sliding windows. Although sliding windows may contain an identifiable portion of the actions, they may not necessarily cover the entire action instance, which would lead to inferior performance. We adapt a two-stage temporal action detection pipeline with Cascaded Boundary Regression (CBR) model. Class-agnostic proposals and specific actions are detected respectively in the first and the second stage. CBR uses temporal coordinate regression to refine the temporal boundaries of the sliding windows. The salient aspect of the refinement process is that, inside each stage, the temporal boundaries are adjusted in a cascaded way by feeding the refined windows back to the system for further boundary refinement. We test CBR on THUMOS-14 and TVSeries, and achieve state-of-the-art performance on both datasets. The performance gain is especially remarkable under high IoU thresholds, e.g. map@tIoU=0.5 on THUMOS-14 is improved from 19.0% to 31.0%.

##### Abstract (translated by Google)
长视频中的时间动作检测是一个重要的问题。最先进的方法通过在滑动窗口上应用动作分类器来解决这个问题。尽管滑动窗口可能包含可识别部分的动作，但是它们可能不一定涵盖整个动作实例，这会导致性能较差。我们采用级联边界回归（CBR）模型来调整两阶段时间动作检测流水线。在第一阶段和第二阶段分别检测类别不可知的提议和具体行动。 CBR使用时间坐标回归来优化滑动窗口的时间边界。细化过程的突出之处在于，在每个阶段内，通过将细化的窗口送回系统以进一步进行边界细化，以级联的方式调整时间边界。我们在THUMOS-14和TVSeries上测试CBR，并在两个数据集上获得最先进的性能。在较高的IoU阈值下，性能增益尤其显着。在THUMOS-14上的map@tIoU=0.5从19.0％提高到31.0％。

##### URL
[https://arxiv.org/abs/1705.01180](https://arxiv.org/abs/1705.01180)

##### PDF
[https://arxiv.org/pdf/1705.01180](https://arxiv.org/pdf/1705.01180)

