---
layout: post
title: "TW-SMNet: Deep Multitask Learning of Tele-Wide Stereo Matching"
date: 2019-06-11 09:46:26
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Mostafa El-Khamy, Haoyu Ren, Xianzhi Du, Jungwon Lee
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce the problem of estimating the real world depth of elements in a scene captured by two cameras with different field of views, where the first field of view (FOV) is a Wide FOV (WFOV) captured by a wide angle lens, and the second FOV is contained in the first FOV and is captured by a tele zoom lens. We refer to the problem of estimating the inverse depth for the union of FOVs, while leveraging the stereo information in the overlapping FOV, as Tele-Wide Stereo Matching (TW-SM). We propose different deep learning solutions to the TW-SM problem. Since the disparity is proportional to the inverse depth, we train stereo matching disparity estimation (SMDE) networks to estimate the disparity for the union WFOV. We further propose an end-to-end deep multitask tele-wide stereo matching neural network (MT-TW-SMNet), which simultaneously learns the SMDE task for the overlapped Tele FOV and the single image inverse depth estimation (SIDE) task for the WFOV. Moreover, we design multiple methods for the fusion of the SMDE and SIDE networks. We evaluate the performance of TW-SM on the popular KITTI and SceneFlow stereo datasets, and demonstrate its practicality by synthesizing the Bokeh effect on the WFOV from a tele-wide stereo image pair.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04463](http://arxiv.org/abs/1906.04463)

##### PDF
[http://arxiv.org/pdf/1906.04463](http://arxiv.org/pdf/1906.04463)

