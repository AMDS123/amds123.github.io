---
layout: post
title: "TextureGAN: Controlling Deep Image Synthesis with Texture Patches"
date: 2017-06-09 03:35:08
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Wenqi Xian, Patsorn Sangkloy, Jingwan Lu, Chen Fang, Fisher Yu, James Hays
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we investigate deep image synthesis guided by sketch, color, and texture. Previous image synthesis methods can be controlled by sketch and color strokes but we are the first to examine texture control. We allow a user to place a texture patch on a sketch at arbitrary location and scale to control the desired output texture. Our generative network learns to synthesize objects consistent with these texture suggestions. To achieve this, we develop a local texture loss in addition to adversarial and content loss to train the generative network. The new local texture loss can improve generated texture quality without knowing the patch location and size in advance. We conduct experiments using sketches generated from real images and textures sampled from the Describable Textures Dataset and results show that our proposed algorithm is able to generate plausible images that are faithful to user controls. Ablation studies show that our proposed pipeline can generate more realistic images than adapting existing methods directly.

##### Abstract (translated by Google)
在本文中，我们研究由草图，颜色和纹理引导的深层图像合成。先前的图像合成方法可以通过草图和颜色笔划进行控制，但我们是首先检查纹理控制。我们允许用户在草图上的任意位置放置纹理贴图，并调整比例以控制所需的输出纹理。我们的生成网络学习合成符合这些纹理建议的对象。为了达到这个目的，除了对抗性和内容损失之外，我们还发展了局部纹理损失来训练生成网络。新的局部纹理损失可以提前生成纹理质量，而无需提前了解补丁位置和大小。我们使用从描述纹理数据集中抽取的真实图像和纹理生成的草图进行实验，结果显示我们提出的算法能够生成忠实于用户控件的合理图像。消融研究表明，我们提出的管道可以产生比直接调整现有方法更为真实的图像。

##### URL
[https://arxiv.org/abs/1706.02823](https://arxiv.org/abs/1706.02823)

##### PDF
[https://arxiv.org/pdf/1706.02823](https://arxiv.org/pdf/1706.02823)

