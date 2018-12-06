---
layout: post
title: "DS-SLAM: A Semantic Visual SLAM towards Dynamic Environments"
date: 2018-12-05 14:16:51
categories: arXiv_RO
tags: arXiv_RO Segmentation Tracking Semantic_Segmentation SLAM
author: Chao Yu, Zuxin Liu, Xinjun Liu, Fugui Xie, Yi Yang, Qi Wei, Qiao Fei
mathjax: true
---

* content
{:toc}

##### Abstract
Simultaneous Localization and Mapping (SLAM) is considered to be a fundamental capability for intelligent mobile robots. Over the past decades, many impressed SLAM systems have been developed and achieved good performance under certain circumstances. However, some problems are still not well solved, for example, how to tackle the moving objects in the dynamic environments, how to make the robots truly understand the surroundings and accomplish advanced tasks. In this paper, a robust semantic visual SLAM towards dynamic environments named DS-SLAM is proposed. Five threads run in parallel in DS-SLAM: tracking, semantic segmentation, local mapping, loop closing, and dense semantic map creation. DS-SLAM combines semantic segmentation network with moving consistency check method to reduce the impact of dynamic objects, and thus the localization accuracy is highly improved in dynamic environments. Meanwhile, a dense semantic octo-tree map is produced, which could be employed for high-level tasks. We conduct experiments both on TUM RGB-D dataset and in the real-world environment. The results demonstrate the absolute trajectory accuracy in DS-SLAM can be improved by one order of magnitude compared with ORB-SLAM2. It is one of the state-of-the-art SLAM systems in high-dynamic environments. Now the code is available at our github: https://github.com/ivipsourcecode/DS-SLAM

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.08379](http://arxiv.org/abs/1809.08379)

##### PDF
[http://arxiv.org/pdf/1809.08379](http://arxiv.org/pdf/1809.08379)

