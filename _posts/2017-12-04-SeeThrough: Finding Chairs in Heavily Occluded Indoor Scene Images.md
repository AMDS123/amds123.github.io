---
layout: post
title:  'SeeThrough: Finding Chairs in Heavily Occluded Indoor Scene Images'
date:   2017-12-05 18:44:29
categories: CV
tags: CV
author: Moos Hueting, Pradyumna Reddy, Vladimir Kim, Ersin Yumer, Nathan Carr, Niloy Mitra
---

* content
{:toc}

##### Abstract
Discovering 3D arrangements of objects from single indoor images is important given its many applications including interior design, content creation, etc. Although heavily researched in the recent years, existing approaches break down under medium or heavy occlusion as the core object detection module starts failing in absence of directly visible cues. Instead, we take into account holistic contextual 3D information, exploiting the fact that objects in indoor scenes co-occur mostly in typical near-regular configurations. First, we use a neural network trained on real indoor annotated images to extract 2D keypoints, and feed them to a 3D candidate object generation stage. Then, we solve a global selection problem among these 3D candidates using pairwise co-occurrence statistics discovered from a large 3D scene database. We iterate the process allowing for candidates with low keypoint response to be incrementally detected based on the location of the already discovered nearby objects. Focusing on chairs, we demonstrate significant performance improvement over combinations of state-of-the-art methods, especially for scenes with moderately to severely occluded objects.

##### Abstract (translated by Google)
在室内设计，内容创作等诸多应用中，发现单个室内图像中的对象的3D排列是重要的。虽然近年来进行了大量的研究，但是现有方法在中等或重度遮挡下分解，因为核心对象检测模块开始失败没有直接可见的线索。相反，我们考虑整体上下文3D信息，利用室内场景中的物体主要以典型的接近常规配置共存的事实。首先，我们使用在真实的室内注释图像上训练的神经网络来提取2D关键点，并将其馈送到3D候选对象生成阶段。然后，我们使用从大型三维场景数据库中发现的成对共现统计来解决这些3D候选之间的全局选择问题。我们迭代该过程，以便根据已经发现的附近对象的位置增量检测具有低关键点响应的候选。专注于椅子，我们展示了与最先进方法的组合相比显着的性能改进，尤其是对于具有中等到严重遮挡物体的场景。

