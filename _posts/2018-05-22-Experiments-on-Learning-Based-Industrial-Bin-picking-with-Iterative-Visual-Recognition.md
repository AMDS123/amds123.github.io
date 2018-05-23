---
layout: post
title: "Experiments on Learning Based Industrial Bin-picking with Iterative Visual Recognition"
date: 2018-05-22 08:21:45
categories: arXiv_RO
tags: arXiv_RO Recognition
author: Kensuke Harada, Weiwei Wan, Tokuo Tsuji, Kohei Kikuchi, Kazuyuki Nagata, Hiromu Onda
mathjax: true
---

* content
{:toc}

##### Abstract
This paper shows experimental results on learning based randomized bin-picking combined with iterative visual recognition. We use the random forest to predict whether or not a robot will successfully pick an object for given depth images of the pile taking the collision between a finger and a neighboring object into account. For the discriminator to be accurate, we consider estimating objects' poses by merging multiple depth images of the pile captured from different points of view by using a depth sensor attached at the wrist. We show that, even if a robot is predicted to fail in picking an object with a single depth image due to its large occluded area, it is finally predicted as success after merging multiple depth images. In addition, we show that the random forest can be trained with the small number of training data.

##### Abstract (translated by Google)
本文展示了基于学习的随机选取结合迭代视觉识别的实验结果。我们使用随机森林来预测一个机器人是否会成功地选取一个物体作为给定的深度图像，并将手指与相邻物体之间的碰撞考虑在内。为了使鉴别器准确无误，我们考虑通过使用连接在手腕处的深度传感器合并从不同视点捕获的堆的多个深度图像来估计物体的姿势。我们证明，即使机器人由于其较大的遮挡区域而被预测为拾取具有单个深度图像的对象时失败，但它在合并多个深度图像之后最终预测为成功。另外，我们表明随机森林可以用少量的训练数据进行训练。

##### URL
[https://arxiv.org/abs/1805.08449](https://arxiv.org/abs/1805.08449)

##### PDF
[https://arxiv.org/pdf/1805.08449](https://arxiv.org/pdf/1805.08449)

