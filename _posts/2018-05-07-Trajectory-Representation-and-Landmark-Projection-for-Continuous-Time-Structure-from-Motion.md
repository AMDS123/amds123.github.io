---
layout: post
title: "Trajectory Representation and Landmark Projection for Continuous-Time Structure from Motion"
date: 2018-05-07 14:29:30
categories: arXiv_CV
tags: arXiv_CV
author: Hannes Ovr&#xe9;n, Per-Erik Forss&#xe9;n
mathjax: true
---

* content
{:toc}

##### Abstract
This paper revisits the problem of continuous-time structure from motion, and introduces a number of extensions that improve convergence and efficiency. The formulation with a $\mathcal{C}^2$-continuous spline for the trajectory naturally incorporates inertial measurements, as derivatives of the sought trajectory. We analyse the behaviour of split interpolation on $\mathbb{SO}(3)$ and on $\mathbb{R}^3$, and a joint interpolation on $\mathbb{SE}(3)$, and show that the latter implicitly couples the direction of translation and rotation. Such an assumption can make good sense for a camera mounted on a robot arm, but not for hand-held or body-mounted cameras. Our experiments show that split interpolation on $\mathbb{SO}(3)$ and on $\mathbb{R}^3$ is preferable over $\mathbb{SE}(3)$ interpolation in all tested cases. Finally, we investigate the problem of landmark reprojection on rolling shutter cameras, and show that the tested reprojection methods give similar quality, while their computational load varies by a factor of 2.

##### Abstract (translated by Google)
本文重新讨论了运动中连续时间结构的问题，并引入了一些扩展来提高收敛性和效率。具有用于轨迹的$ \ mathcal {C} ^ 2连续样条的公式自然地将惯性测量结合为寻求轨迹的导数。我们分析了$ \ mathbb {SO}（3）$和$ \ mathbb {R} ^ 3 $上的分割插值行为以及$ \ mathbb {SE}（3）$上的联合插值，并显示后者隐含地结合了翻译和旋转的方向。这样的假设对于安装在机器人手臂上的照相机可能是有意义的，但对于手持式或车身安装的照相机则不是。我们的实验表明，在所有测试的情况下，$ \ mathbb {SO}（3）$和$ \ mathbb {R} ^ 3 $上的分割插值优于$ \ mathbb {SE}（3）$插值。最后，我们研究了卷帘式快门相机上具有标志性重投影的问题，并且表明经过测试的重投影方法具有相似的质量，而它们的计算负载变化了2倍。

##### URL
[http://arxiv.org/abs/1805.02543](http://arxiv.org/abs/1805.02543)

##### PDF
[http://arxiv.org/pdf/1805.02543](http://arxiv.org/pdf/1805.02543)

