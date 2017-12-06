---
layout: post
title: "Viewpoint Adaptation for Rigid Object Detection"
date: 2017-02-24 02:37:15
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Patrick Wang, Kenneth Morton, Peter Torrione, Leslie Collins
mathjax: true
---

* content
{:toc}

##### Abstract
An object detector performs suboptimally when applied to image data taken from a viewpoint different from the one with which it was trained. In this paper, we present a viewpoint adaptation algorithm that allows a trained single-view object detector to be adapted to a new, distinct viewpoint. We first illustrate how a feature space transformation can be inferred from a known homography between the source and target viewpoints. Second, we show that a variety of trained classifiers can be modified to behave as if that transformation were applied to each testing instance. The proposed algorithm is evaluated on a person detection task using images from the PETS 2007 and CAVIAR datasets, as well as from a new synthetic multi-view person detection dataset. It yields substantial performance improvements when adapting single-view person detectors to new viewpoints, and simultaneously reduces computational complexity. This work has the potential to improve detection performance for cameras viewing objects from arbitrary viewpoints, while simplifying data collection and feature extraction.

##### Abstract (translated by Google)
物体检测器在应用于从与被训练的视点不同的视点获取的图像数据时执行次优化。在本文中，我们提出了一个观点适应算法，允许一个训练的单视物体检测器适应一个新的，不同的观点。我们首先说明如何从源和目标观点之间的已知单应性推断特征空间转换。其次，我们展示了各种训练过的分类器可以被修改，就好像这个转换被应用到每个测试实例一样。所提出的算法在使用来自PETS 2007和CAVIAR数据集的图像以及来自新的合成多视图人员检测数据集的人检测任务上进行评估。当将单视角人员检测器适应新的视点时，其产生显着的性能改进，并同时降低计算复杂度。这项工作有可能提高从任意视角观察物体的相机的检测性能，同时简化数据收集和特征提取。

##### URL
[https://arxiv.org/abs/1702.07451](https://arxiv.org/abs/1702.07451)

