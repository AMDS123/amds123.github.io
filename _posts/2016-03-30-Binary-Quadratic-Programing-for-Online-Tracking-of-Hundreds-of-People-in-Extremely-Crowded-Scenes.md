---
layout: post
title: "Binary Quadratic Programing for Online Tracking of Hundreds of People in Extremely Crowded Scenes"
date: 2016-03-30 15:11:38
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Object_Tracking Optimization Detection
author: Afshin Dehghan, Mubarak Shah
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-object tracking has been studied for decades. However, when it comes to tracking pedestrians in extremely crowded scenes, we are limited to only few works. This is an important problem which gives rise to several challenges. Pre-trained object detectors fail to localize targets in crowded sequences. This consequently limits the use of data-association based multi-target tracking methods which rely on the outcome of an object detector. Additionally, the small apparent target size makes it challenging to extract features to discriminate targets from their surroundings. Finally, the large number of targets greatly increases computational complexity which in turn makes it hard to extend existing multi-target tracking approaches to high-density crowd scenarios. In this paper, we propose a tracker that addresses the aforementioned problems and is capable of tracking hundreds of people efficiently. We formulate online crowd tracking as Binary Quadratic Programing. Our formulation employs target's individual information in the form of appearance and motion as well as contextual cues in the form of neighborhood motion, spatial proximity and grouping constraints, and solves detection and data association simultaneously. In order to solve the proposed quadratic optimization efficiently, where state-of art commercial quadratic programing solvers fail to find the answer in a reasonable amount of time, we propose to use the most recent version of the Modified Frank Wolfe algorithm, which takes advantage of SWAP-steps to speed up the optimization. We show that the proposed formulation can track hundreds of targets efficiently and improves state-of-art results by significant margins on eleven challenging high density crowd sequences.

##### Abstract (translated by Google)
多目标跟踪已经研究了数十年。但是，当我们在极其拥挤的场景中追踪行人时，我们仅限于少数作品。这是一个引起几个挑战的重要问题。预先训练的物体检测器无法在拥挤的序列中定位目标。这因此限制了使用依赖于对象检测器的结果的基于数据关联的多目标跟踪方法。另外，小的目标尺寸使得提取特征来区分目标与周围环境具有挑战性。最后，大量的目标大大增加了计算复杂度，这反过来又难以将现有的多目标跟踪方法扩展到高密度人群情景。在本文中，我们提出了一个跟踪器，解决上述问题，并能够有效跟踪数百人。我们制定在线人群跟踪作为二进制二次编程。我们的公式采用目标的个人信息的外观和运动的形式，以及以邻域运动，空间邻近和分组约束的形式的上下文线索，同时解决检测和数据关联。为了有效地解决所提出的二次优化问题，在现有技术的商业二次编程求解器无法在合理的时间内找到答案的情况下，我们建议使用最新版本的改进的Frank Wolfe算法，该算法利用SWAP步骤加快优化。我们表明，拟议的公式可以有效地追踪数百个目标，并通过对十一个具有挑战性的高密度人群序列的显着利润率来提高最先进的结果。

##### URL
[https://arxiv.org/abs/1603.09240](https://arxiv.org/abs/1603.09240)

##### PDF
[https://arxiv.org/pdf/1603.09240](https://arxiv.org/pdf/1603.09240)

