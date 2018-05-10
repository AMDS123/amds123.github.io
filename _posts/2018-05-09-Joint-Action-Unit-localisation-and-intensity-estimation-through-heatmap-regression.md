---
layout: post
title: "Joint Action Unit localisation and intensity estimation through heatmap regression"
date: 2018-05-09 12:49:20
categories: arXiv_CV
tags: arXiv_CV Face
author: Enrique Sanchez, Georgios Tzimiropoulos, Michel Valstar
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a supervised learning approach to jointly perform facial Action Unit (AU) localisation and intensity estimation. Contrary to previous works that try to learn an unsupervised representation of the Action Unit regions, we propose to directly and jointly estimate all AU intensities through heatmap regression, along with the location in the face where they cause visible changes. Our approach aims to learn a pixel-wise regression function returning a score per AU, which indicates an AU intensity at a given spatial location. Heatmap regression then generates an image, or channel, per AU, in which each pixel indicates the corresponding AU intensity. To generate the ground-truth heatmaps for a target AU, the facial landmarks are first estimated, and a 2D Gaussian is drawn around the points where the AU is known to cause changes. The amplitude and size of the Gaussian is determined by the intensity of the AU. We show that using a single Hourglass network suffices to attain new state of the art results, demonstrating the effectiveness of such a simple approach. The use of heatmap regression allows learning of a shared representation between AUs without the need to rely on latent representations, as these are implicitly learned from the data. We validate the proposed approach on the BP4D dataset, showing a modest improvement on recent, complex, techniques, as well as robustness against misalignment errors. We will release the code and the models to validate the experimental results.

##### Abstract (translated by Google)
本文提出了一种监督学习方法来联合执行面部动作单元（AU）定位和强度估计。与先前试图学习动作单元区域的无监督表示的作品相反，我们建议通过热图回归直接和联合估计所有AU强度，以及它们引起可见变化的面部位置。我们的方法旨在学习像素方式的回归函数，每AU返回一个分数，表示在给定空间位置的AU强度。热图回归然后生成每个AU的图像或通道，其中每个像素指示对应的AU强度。为了生成目标AU的地面真实热图，首先估计面部地标，并且在AU已知引起变化的点周围绘制二维高斯。高斯的幅度和大小由AU的强度确定。我们证明，使用一个单一的沙漏网络就可以获得最新的艺术成果，展示这种简单方法的有效性。热图回归的使用允许学习AU之间的共享表示，而不需要依赖潜在表示，因为这些隐含地从数据中学习。我们验证了BP4D数据集上提出的方法，显示了对近期复杂技术的适度改进，以及针对错位错误的稳健性。我们将发布代码和模型来验证实验结果。

##### URL
[http://arxiv.org/abs/1805.03487](http://arxiv.org/abs/1805.03487)

##### PDF
[http://arxiv.org/pdf/1805.03487](http://arxiv.org/pdf/1805.03487)

