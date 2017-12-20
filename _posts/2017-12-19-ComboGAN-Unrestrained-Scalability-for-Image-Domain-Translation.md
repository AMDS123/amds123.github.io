---
layout: post
title: "ComboGAN: Unrestrained Scalability for Image Domain Translation"
date: 2017-12-19 13:18:42
categories: arXiv_CV
tags: arXiv_CV GAN
author: Asha Anoosheh, Eirikur Agustsson, Radu Timofte, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
This year alone has seen unprecedented leaps in the area of learning-based image translation, namely CycleGAN, by Zhu et al. But experiments so far have been tailored to merely two domains at a time, and scaling them to more would require an quadratic number of models to be trained. And with two-domain models taking days to train on current hardware, the number of domains quickly becomes limited by the time and resources required to process them. In this paper, we propose a multi-component image translation model and training scheme which scales linearly - both in resource consumption and time required - with the number of domains. We demonstrate its capabilities on a dataset of paintings by 14 different artists and on images of the four different seasons in the Alps. Note that 14 data groups would need (14 choose 2) = 91 different CycleGAN models: a total of 182 generator/discriminator pairs; whereas our model requires only 14 generator/discriminator pairs.

##### Abstract (translated by Google)
仅在今年，朱等人在基于学习的图像翻译领域即CycleGAN方面取得了前所未有的飞跃。但是到目前为止，实验只能针对两个领域进行量身定制，而将其扩展到更多的领域则需要对二次模型进行训练。随着两个领域的模型花费数天的时间在当前的硬件上进行培训，领域的数量很快就会受到处理它们所需的时间和资源的限制。在本文中，我们提出了一个多分量的图像转换模型和训练方案，无论是在资源消耗和所需的时间线性缩放与域的数量。我们展示了14位不同艺术家的绘画数据集以及阿尔卑斯山四个不同季节的图像。注意，14个数据组需要（14个选择2）= 91个不同的CycleGAN模型：总共182个发生器/鉴别器对;而我们的模型只需要14个发生器/鉴别器对。

##### URL
[http://arxiv.org/abs/1712.06909](http://arxiv.org/abs/1712.06909)

##### PDF
[http://arxiv.org/pdf/1712.06909](http://arxiv.org/pdf/1712.06909)

