---
layout: post
title: "Sketch-to-Image Generation Using Deep Contextual Completion"
date: 2017-11-24 14:19:25
categories: arXiv_CV
tags: arXiv_CV Image_Caption
author: Yongyi Lu, Shangzhe Wu, Yu-Wing Tai, Chi-Keung Tang
mathjax: true
---

* content
{:toc}

##### Abstract
When the input to pix2pix translation is a badly drawn sketch, the output follows the input edges due to the strict alignment imposed by the translation process. In this paper we propose sketch-to-image generation, where the output edges do not necessarily follow the input edges. We address the image generation problem using a novel joint image completion approach, where the sketch provides the image context for completing, or generating the output image. We train a deep generative model to learn the joint distribution of sketch and the corresponding image by using joint images. Our deep contextual completion approach has several advantages. First, the simple joint image representation allows for simple and effective definition of losses in the same joint image-sketch space, which avoids complicated issues in cross-domain learning. Second, while the output is related to its input overall, the generated features exhibit more freedom in appearance and do not strictly align with the input features. Third, from the joint image's point of view, image and sketch are of no difference, thus exactly the same deep joint image completion network can be used for image-to-sketch generation. Experiments evaluated on three different datasets show that the proposed approach can generate more realistic images than the state-ofthe- arts on challenging inputs and generalize well on common categories.

##### Abstract (translated by Google)
当pix2pix转换的输入是一个草草图，由于翻译过程严格对齐，输出会跟随输入边缘。在本文中，我们提出草图到图像的生成，其中输出边缘不一定跟随输入边缘。我们使用一种新颖的联合图像完成方法来处理图像生成问题，其中草图提供用于完成的图像上下文或生成输出图像。我们训练一个深刻的生成模型，通过使用联合图像来学习草图和相应图像的联合分布。我们深入的语境完成方法有几个优点。首先，简单的联合图像表示允许在相同的联合图像素描空间中简单有效地定义损失，从而避免了跨领域学习中的复杂问题。其次，输出与输入整体相关，产生的特征表现出更大的自由度，不严格对齐输入特征。第三，从联合图像的角度来看，图像和草图没有区别，因此完全相同的深度联合图像完成网络可以用于图像到草图的生成。在三个不同的数据集上评估的实验表明，所提出的方法可以产生比具有挑战性的输入的艺术现状更逼真的图像，并在普通类别上很好地概括。

##### URL
[https://arxiv.org/abs/1711.08972](https://arxiv.org/abs/1711.08972)

##### PDF
[https://arxiv.org/pdf/1711.08972](https://arxiv.org/pdf/1711.08972)

