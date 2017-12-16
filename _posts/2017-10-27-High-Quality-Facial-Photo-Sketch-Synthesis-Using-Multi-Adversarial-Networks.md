---
layout: post
title: "High-Quality Facial Photo-Sketch Synthesis Using Multi-Adversarial Networks"
date: 2017-10-27 14:56:45
categories: arXiv_CV
tags: arXiv_CV Adversarial QA GAN Face
author: Lidan Wang, Vishwanath A. Sindagi, Vishal M. Patel
mathjax: true
---

* content
{:toc}

##### Abstract
Synthesizing face sketches from real photos and its inverse are well studied problems and they have many applications in digital forensics and entertainment. However, photo/sketch synthesis remains a challenging problem due to the fact that photo and sketch have different characteristics. In this work, we consider this task as an image-to-image translation problem and explore the recently popular generative models (GANs) to generate high-quality realistic photos from sketches and sketches from photos. Recent methods such as Pix2Pix, CycleGAN and DualGAN have shown promising results on image-to-image translation problems and photo-to-sketch synthesis in particular, however, they are known to have limited abilities in generating high-resolution realistic images. To this end, we propose a novel synthesis framework called Photo-Sketch Synthesis using Multi-Adversarial Networks, (PS\textsuperscript{2}-MAN) that iteratively generates low resolution to high resolution images in an adversarial way. The hidden layers of the generator are supervised to first generate lower resolution images followed by implicit refinement in the network to generate higher resolution images. Furthermore, since photo-sketch synthesis is a coupled/paired translation problem where photo-sketch and sketch-photo are equally important, we leverage the pair information in the CycleGAN framework. Evaluation of the proposed method is performed on two datasets: CUHK and CUFSF. Both Image Quality Assessment (IQA) and Photo-Sketch Matching experiments are conducted to demonstrate the superior performance of our framework in comparison to existing state-of-the-art solutions. Additionally, ablation studies are conducted to verify the effectiveness iterative synthesis and various loss functions.

##### Abstract (translated by Google)
从真实照片及其逆向合成人脸素描已经有了很好的研究，在数字取证和娱乐方面有很多应用。然而，照片/素描合成仍然是一个具有挑战性的问题，因为照片和素描有不同的特点。在这项工作中，我们将这个任务视为一个图像到图像的翻译问题，并探索最近流行的生成模型（GAN），从草图和草图中生成高质量的真实照片。最近的方法如Pix2Pix，CycleGAN和DualGAN已经在图像到图像的转换问题和照片到草图的合成方面显示出有希望的结果，但是已知在生成高分辨率的真实图像方面能力有限。为此，我们提出了一种新的综合框架，称为Photo-Sketch Synthesis，使用多对抗网络（PS \ textsuperscript {2} -MAN），以对抗方式迭代地产生低分辨率的高分辨率图像。监测发生器的隐藏层首先生成较低分辨率的图像，然后在网络中进行隐式细化以生成更高分辨率的图像。此外，由于照片素描合成是一个耦合/配对翻译问题，其中照片素描和素描照片同样重要，因此我们利用CycleGAN框架中的配对信息。所提出的方法的评估在两个数据集上进行：中大和CUFSF。进行图像质量评估（IQA）和Photo-Sketch匹配实验，以证明我们的框架与现有的最先进的解决方案相比的优越性能。此外，进行消融研究来验证迭代合成和各种损失函数的有效性。

##### URL
[https://arxiv.org/abs/1710.10182](https://arxiv.org/abs/1710.10182)

##### PDF
[https://arxiv.org/pdf/1710.10182](https://arxiv.org/pdf/1710.10182)

