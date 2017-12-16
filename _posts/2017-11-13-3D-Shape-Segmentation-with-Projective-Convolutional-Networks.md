---
layout: post
title: "3D Shape Segmentation with Projective Convolutional Networks"
date: 2017-11-13 05:46:17
categories: arXiv_CV
tags: arXiv_CV Segmentation Face CNN
author: Evangelos Kalogerakis, Melinos Averkiou, Subhransu Maji, Siddhartha Chaudhuri
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a deep architecture for segmenting 3D objects into their labeled semantic parts. Our architecture combines image-based Fully Convolutional Networks (FCNs) and surface-based Conditional Random Fields (CRFs) to yield coherent segmentations of 3D shapes. The image-based FCNs are used for efficient view-based reasoning about 3D object parts. Through a special projection layer, FCN outputs are effectively aggregated across multiple views and scales, then are projected onto the 3D object surfaces. Finally, a surface-based CRF combines the projected outputs with geometric consistency cues to yield coherent segmentations. The whole architecture (multi-view FCNs and CRF) is trained end-to-end. Our approach significantly outperforms the existing state-of-the-art methods in the currently largest segmentation benchmark (ShapeNet). Finally, we demonstrate promising segmentation results on noisy 3D shapes acquired from consumer-grade depth cameras.

##### Abstract (translated by Google)
本文介绍了一种深入的体系结构，将三维对象分割为标注的语义部分。我们的架构将基于图像的完全卷积网络（FCN）和基于表面的条件随机场（CRF）相结合，以产生三维形状的相干分段。基于图像的FCN被用于关于3D对象部分的高效的基于视图的推理。通过一个特殊的投影层，FCN输出在多个视图和尺度上被有效地聚合，然后被投影到3D物体表面上。最后，基于表面的CRF将投影输出与几何一致性提示相结合，以产生相干分割。整个架构（多视图FCN和CRF）是端对端培训。我们的方法明显优于目前最大的细分基准（ShapeNet）中现有的最先进的方法。最后，我们展示了在从消费级深度相机获得的嘈杂的3D形状上有希望的分割结果。

##### URL
[https://arxiv.org/abs/1612.02808](https://arxiv.org/abs/1612.02808)

##### PDF
[https://arxiv.org/pdf/1612.02808](https://arxiv.org/pdf/1612.02808)

