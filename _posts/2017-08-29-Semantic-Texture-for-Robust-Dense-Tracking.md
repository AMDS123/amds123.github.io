---
layout: post
title: "Semantic Texture for Robust Dense Tracking"
date: 2017-08-29 15:58:18
categories: arXiv_CV
tags: arXiv_CV Tracking CNN SLAM
author: Jan Czarnowski, Stefan Leutenegger, Andrew Davison
mathjax: true
---

* content
{:toc}

##### Abstract
We argue that robust dense SLAM systems can make valuable use of the layers of features coming from a standard CNN as a pyramid of `semantic texture' which is suitable for dense alignment while being much more robust to nuisance factors such as lighting than raw RGB values. We use a straightforward Lucas-Kanade formulation of image alignment, with a schedule of iterations over the coarse-to-fine levels of a pyramid, and simply replace the usual image pyramid by the hierarchy of convolutional feature maps from a pre-trained CNN. The resulting dense alignment performance is much more robust to lighting and other variations, as we show by camera rotation tracking experiments on time-lapse sequences captured over many hours. Looking towards the future of scene representation for real-time visual SLAM, we further demonstrate that a selection using simple criteria of a small number of the total set of features output by a CNN gives just as accurate but much more efficient tracking performance.

##### Abstract (translated by Google)
我们认为强大的密集SLAM系统可以有价值地使用来自标准CNN的特征层作为“语义纹理”的金字塔，这种金字塔适合于密集对齐，同时对于诸如照明之类的干扰因素，比原始RGB值。我们使用简单的卢卡斯 - 卡纳德图像对齐公式，在金字塔的粗糙到精细的级别上进行迭代计划，并简单地用预先训练的CNN的卷积特征映射层次替换通常的图像金字塔。由此产生的密集对准性能对于照明和其他变化更为稳健，正如我们通过摄像机旋转跟踪实验所显示的，在多个小时内捕获的时间推移序列。展望实时视觉SLAM的场景表示的未来，我们进一步证明，使用CNN输出的少量特征集合的简单标准进行选择给出了同样准确但更高效的跟踪性能。

##### URL
[https://arxiv.org/abs/1708.08844](https://arxiv.org/abs/1708.08844)

##### PDF
[https://arxiv.org/pdf/1708.08844](https://arxiv.org/pdf/1708.08844)

