---
layout: post
title: "Summarization of ICU Patient Motion from Multimodal Multiview Videos"
date: 2017-06-28 18:08:37
categories: arXiv_CV
tags: arXiv_CV Summarization Classification Detection
author: Carlos Torres, Kenneth Rose, Jeffrey C. Fried, B. S. Manjunath
mathjax: true
---

* content
{:toc}

##### Abstract
Clinical observations indicate that during critical care at the hospitals, patients sleep positioning and motion affect recovery. Unfortunately, there is no formal medical protocol to record, quantify, and analyze patient motion. There is a small number of clinical studies, which use manual analysis of sleep poses and motion recordings to support medical benefits of patient positioning and motion monitoring. Manual processes are not scalable, are prone to human errors, and strain an already taxed healthcare workforce. This study introduces DECU (Deep Eye-CU): an autonomous mulitmodal multiview system, which addresses these issues by autonomously monitoring healthcare environments and enabling the recording and analysis of patient sleep poses and motion. DECU uses three RGB-D cameras to monitor patient motion in a medical Intensive Care Unit (ICU). The algorithms in DECU estimate pose direction at different temporal resolutions and use keyframes to efficiently represent pose transition dynamics. DECU combines deep features computed from the data with a modified version of Hidden Markov Model to more flexibly model sleep pose duration, analyze pose patterns, and summarize patient motion. Extensive experimental results are presented. The performance of DECU is evaluated in ideal (BC: Bright and Clear/occlusion-free) and natural (DO: Dark and Occluded) scenarios at two motion resolutions in a mock-up and a real ICU. The results indicate that deep features allow DECU to match the classification performance of engineered features in BC scenes and increase the accuracy by up to 8% in DO scenes. In addition, the overall pose history summarization tracing accuracy shows an average detection rate of 85% in BC and of 76% in DO scenes. The proposed keyframe estimation algorithm allows DECU to reach an average 78% transition classification accuracy.

##### Abstract (translated by Google)
临床观察表明，在医院急救期间，患者的睡眠定位和运动会影响恢复。不幸的是，没有正式的医疗记录来记录，量化和分析患者的运动。有少量的临床研究使用手动分析睡眠姿势和运动记录来支持患者定位和运动监测的医疗效益。手动流程不可扩展，很容易出现人为错误，并使已经纳税的医疗队伍紧张。这项研究介绍了DECU（Deep Eye-CU）：一种自主的多视图多视图系统，通过自主监测医疗环境以及记录和分析患者的睡眠姿势和运动来解决这些问题。 DECU使用三台RGB-D摄像机监控医疗重症监护病房（ICU）的病人运动。 DECU中的算法以不同的时间分辨率估计姿态方向，并使用关键帧高效地表示姿态转换动态。 DECU将从数据计算的深度特征与隐马尔可夫模型的修改版本结合起来，以更灵活地模拟睡眠姿势持续时间，分析姿势模式并且总结患者运动。提出了广泛的实验结果。 DECU的性能在模拟和真实的ICU中以理想的（BC：明亮和清晰/无遮挡）和自然（DO：黑暗和遮挡）场景以两种运动分辨率进行评估。结果表明，深度特征允许DECU匹配BC场景中的工程特征的分类性能，并且在DO场景中提高高达8％的精度。此外，整体姿势历史追踪精确度显示，卑诗省的平均检出率为85％，DO的平均检出率为76％。所提出的关键帧估计算法允许DECU达到平均78％的过渡分类准确度。

##### URL
[https://arxiv.org/abs/1706.09430](https://arxiv.org/abs/1706.09430)

##### PDF
[https://arxiv.org/pdf/1706.09430](https://arxiv.org/pdf/1706.09430)

