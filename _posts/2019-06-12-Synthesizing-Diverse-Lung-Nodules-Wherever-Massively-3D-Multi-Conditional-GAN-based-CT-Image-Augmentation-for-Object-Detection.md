---
layout: post
title: "Synthesizing Diverse Lung Nodules Wherever Massively: 3D Multi-Conditional GAN-based CT Image Augmentation for Object Detection"
date: 2019-06-12 06:31:39
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Segmentation GAN CNN Detection VQA
author: Changhee Han, Yoshiro Kitamura, Akira Kudo, Akimichi Ichinose, Leonardo Rundo, Yujiro Furukawa, Kazuki Umemoto, Hideki Nakayama, Yuanzhong Li
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate computer-assisted diagnosis, relying on large-scale annotated pathological images, can alleviate the risk of overlooking the diagnosis. Unfortunately, in medical imaging, most available datasets are small/fragmented. To tackle this, as a Data Augmentation (DA) method, 3D conditional Generative Adversarial Networks (GANs) can synthesize desired realistic/diverse 3D images as additional training data. However, no 3D conditional GAN-based DA approach exists for general bounding box-based 3D object detection, while it can locate disease areas with physicians' minimum annotation cost, unlike rigorous 3D segmentation. Moreover, since lesions vary in position/size/attenuation, further GAN-based DA performance requires multiple conditions. Therefore, we propose 3D Multi-Conditional GAN (MCGAN) to generate realistic/diverse 32 x 32 x 32 nodules placed naturally on lung Computed Tomography images to boost sensitivity in 3D object detection. Our MCGAN adopts two discriminators for conditioning: the context discriminator learns to classify real vs synthetic nodule/surrounding pairs with noise box-centered surroundings; the nodule discriminator attempts to classify real vs synthetic nodules with size/attenuation conditions. The results show that 3D Convolutional Neural Network-based detection can achieve higher sensitivity under any nodule size/attenuation at fixed False Positive rates and overcome the medical data paucity with the MCGAN-generated realistic nodules---even expert physicians fail to distinguish them from the real ones in Visual Turing Test.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04962](http://arxiv.org/abs/1906.04962)

##### PDF
[http://arxiv.org/pdf/1906.04962](http://arxiv.org/pdf/1906.04962)

