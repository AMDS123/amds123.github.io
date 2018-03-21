---
layout: post
title: "Faces as Lighting Probes via Unsupervised Deep Highlight Extraction"
date: 2018-03-16 17:53:06
categories: arXiv_CV
tags: arXiv_CV Knowledge Face
author: Renjiao Yi, Chenyang Zhu, Ping Tan, Stephen Lin
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method for estimating detailed scene illumination using human faces in a single image. In contrast to previous works that estimate lighting in terms of low-order basis functions or distant point lights, our technique estimates illumination at a higher precision in the form of a non-parametric environment map. Based on the observation that faces can exhibit strong highlight reflections from a broad range of lighting directions, we propose a deep neural network for extracting highlights from faces, and then trace these reflections back to the scene to acquire the environment map. Since real training data for highlight extraction is very limited, we introduce an unsupervised scheme for finetuning the network on real images, based on the consistent diffuse chromaticity of a given face seen in multiple real images. In tracing the estimated highlights to the environment, we reduce the blurring effect of skin reflectance on reflected light through a deconvolution determined by prior knowledge on face material properties. Comparisons to previous techniques for highlight extraction and illumination estimation show the state-of-the-art performance of this approach on a variety of indoor and outdoor scenes.

##### Abstract (translated by Google)
我们提出了一种在单个图像中使用人脸估计详细场景照明的方法。与先前的以低阶基函数或远点光源估计照明的作品相比，我们的技术以非参数环境地图的形式以更高的精度估算照明。基于观察到人脸可以从广泛的照明方向表现出强烈的高光反射，我们提出了一个深度神经网络来提取人脸上的高光，然后将这些反射回溯到场景以获取环境地图。由于用于高光提取的实际训练数据非常有限，我们基于在多个真实图像中看到的给定脸部的一致漫反射色度，引入用于在真实图像上微调网络的无监督方案。在将估计的高光追踪到环境中时，我们通过由面部材料属性的先验知识确定的反卷积来减少反射光的皮肤反射的模糊效应。与之前用于高光提取和照明估计的技术的比较显示了这种方法在各种室内和室外场景中的最新性能。

##### URL
[https://arxiv.org/abs/1803.06340](https://arxiv.org/abs/1803.06340)

##### PDF
[https://arxiv.org/pdf/1803.06340](https://arxiv.org/pdf/1803.06340)

