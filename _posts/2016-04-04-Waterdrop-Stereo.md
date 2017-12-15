---
layout: post
title: "Waterdrop Stereo"
date: 2016-04-04 03:16:40
categories: arXiv_CV
tags: arXiv_CV Knowledge Face Quantitative
author: Shaodi You, Robby T. Tan, Rei Kawakami, Yasuhiro Mukaigawa, Katsushi Ikeuchi
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces depth estimation from water drops. The key idea is that a single water drop adhered to window glass is totally transparent and convex, and thus optically acts like a fisheye lens. If we have more than one water drop in a single image, then through each of them we can see the environment with different view points, similar to stereo. To realize this idea, we need to rectify every water drop imagery to make radially distorted planar surfaces look flat. For this rectification, we consider two physical properties of water drops: (1) A static water drop has constant volume, and its geometric convex shape is determined by the balance between the tension force and gravity. This implies that the 3D geometric shape can be obtained by minimizing the overall potential energy, which is the sum of the tension energy and the gravitational potential energy. (2) The imagery inside a water-drop is determined by the water-drop 3D shape and total reflection at the boundary. This total reflection generates a dark band commonly observed in any adherent water drops. Hence, once the 3D shape of water drops are recovered, we can rectify the water drop images through backward raytracing. Subsequently, we can compute depth using stereo. In addition to depth estimation, we can also apply image refocusing. Experiments on real images and a quantitative evaluation show the effectiveness of our proposed method. To our best knowledge, never before have adherent water drops been used to estimate depth.

##### Abstract (translated by Google)
本文介绍了水滴的深度估计。关键的思想是，附着在窗玻璃上的单个水滴是完全透明和凸起的，因此光学作用就像鱼眼镜头一样。如果我们在一幅图像中有多个水滴，那么通过它们中的每一个我们都可以看到与立体视觉不同的观察点的环境。要实现这个想法，我们需要纠正每个水滴图像，使径向扭曲的平面表面看起来平坦。对于这种纠正，我们考虑了水滴的两个物理性质：（1）静态水滴具有恒定的体积，其几何凸形是由张力与重力的平衡决定的。这意味着三维几何形状可以通过最小化作为张力能量和重力势能之和的整体势能来获得。 （2）水滴内的图像是由水滴三维形状和边界全反射决定的。这种全反射产生了在任何粘附的水滴中通常观察到的暗带。因此，一旦水滴的三维形状得到恢复，我们就可以通过后向光线追踪来纠正水滴图像。随后，我们可以使用立体声来计算深度。除了深度估计，我们也可以应用图像重新聚焦。真实图像实验和定量评估显示了我们提出的方法的有效性。据我们所知，以前从来没有使用粘性水滴来估计深度。

##### URL
[https://arxiv.org/abs/1604.00730](https://arxiv.org/abs/1604.00730)

##### PDF
[https://arxiv.org/pdf/1604.00730](https://arxiv.org/pdf/1604.00730)

