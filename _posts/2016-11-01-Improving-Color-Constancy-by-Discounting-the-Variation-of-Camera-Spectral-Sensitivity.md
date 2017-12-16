---
layout: post
title: "Improving Color Constancy by Discounting the Variation of Camera Spectral Sensitivity"
date: 2016-11-01 15:33:30
categories: arXiv_CV
tags: arXiv_CV
author: Shao-Bing Gao, Ming Zhang, Chao-Yi Li, Yong-Jie Li
mathjax: true
---

* content
{:toc}

##### Abstract
It is an ill-posed problem to recover the true scene colors from a color biased image by discounting the effects of scene illuminant and camera spectral sensitivity (CSS) at the same time. Most color constancy (CC) models have been designed to first estimate the illuminant color, which is then removed from the color biased image to obtain an image taken under white light, without the explicit consideration of CSS effect on CC. This paper first studies the CSS effect on illuminant estimation arising in the inter-dataset-based CC (inter-CC), i.e., training a CC model on one dataset and then testing on another dataset captured by a distinct CSS. We show the clear degradation of existing CC models for inter-CC application. Then a simple way is proposed to overcome such degradation by first learning quickly a transform matrix between the two distinct CSSs (CSS-1 and CSS-2). The learned matrix is then used to convert the data (including the illuminant ground truth and the color biased images) rendered under CSS-1 into CSS-2, and then train and apply the CC model on the color biased images under CSS-2, without the need of burdensome acquiring of training set under CSS-2. Extensive experiments on synthetic and real images show that our method can clearly improve the inter-CC performance for traditional CC algorithms. We suggest that by taking the CSS effect into account, it is more likely to obtain the truly color constant images invariant to the changes of both illuminant and camera sensors.

##### Abstract (translated by Google)
通过对场景光源和相机光谱灵敏度（CSS）的影响同时进行折扣，从色彩偏差图像恢复真实场景色彩是一个不适当的问题。大多数颜色恒常（CC）模型被设计为首先估计光源颜色，然后将其从偏色图像中去除以获得在白光下拍摄的图像，而没有明确考虑对CC的CSS效果。本文首先研究了基于数据集间CC（Inter-CC）的光源估计CSS效应，即在一个数据集上训练一个CC模型，然后测试由不同的CSS捕获的另一个数据集。我们展示了CC间应用的现有CC模型的明显退化。然后提出一种简单的方法来克服这种退化，首先快速学习两个不同的CSS（CSS-1和CSS-2）之间的变换矩阵。然后用学习矩阵将CSS-1下渲染的数据（包括光照地面实况和色彩偏差图像）转换成CSS-2，然后在CSS-2下的颜色偏差图像上训练和应用CC模型，不需要繁重的CSS-2培训。对合成和真实图像的大量实验表明，我们的方法可以明显改善传统CC算法的CC间性能。我们建议，通过考虑CSS效应，更有可能获得真正的彩色恒定图像不变的光源和相机传感器的变化。

##### URL
[https://arxiv.org/abs/1609.01670](https://arxiv.org/abs/1609.01670)

##### PDF
[https://arxiv.org/pdf/1609.01670](https://arxiv.org/pdf/1609.01670)

