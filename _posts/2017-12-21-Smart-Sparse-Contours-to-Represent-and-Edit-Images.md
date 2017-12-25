---
layout: post
title: "Smart, Sparse Contours to Represent and Edit Images"
date: 2017-12-21 22:11:49
categories: arXiv_CV
tags: arXiv_CV Image_Caption Adversarial Sparse Knowledge Face
author: Tali Dekel, Chuang Gan, Dilip Krishnan, Ce Liu, William T. Freeman
mathjax: true
---

* content
{:toc}

##### Abstract
We study the problem of reconstructing an image from information stored at sparse contour locations. Existing contour-based image reconstruction methods struggle to balance contour sparsity and reconstruction fidelity. Therefore, denser contours are needed to capture subtle texture information even though contours were not meant for textures. We propose a novel image representation where image content is characterized by contours with gradient information via an encoder-decoder network, while image details are modeled by a conditional generative adversarial network. We show that high-quality reconstructions with high fidelity to the source image can be obtained from extremely sparse input, e.g., comprising less than 6% of image pixels. Our model synthesizes texture, details and fine structures in regions where no input information is provided. The semantic knowledge encoded into our model and the sparsity of the input allows using contours as an intuitive interface for semantically-aware image manipulation: local edits in contour domain such as scaling, translation and erasing, translate to long-range and coherent changes in the pixel space. Experiments on a variety of datasets verify the versatility and convenience afforded by our models.

##### Abstract (translated by Google)
我们研究从稀疏轮廓位置存储的信息重建图像的问题。现有的基于轮廓的图像重建方法难以平衡轮廓稀疏性和重建逼真度。因此，即使轮廓不是用于纹理，也需要更密集的轮廓来捕捉微妙的纹理信息。我们提出了一种新颖的图像表示形式，其中图像内容通过编码器 - 解码器网络通过具有梯度信息的轮廓表征，而图像细节由有条件的生成对抗网络建模。我们表明，对于源图像的高保真度的高质量重构可以从极其稀疏的输入获得，例如包含小于6％的图像像素。我们的模型在没有输入信息的地区合成纹理，细节和精细结构。编码到我们的模型中的语义知识和输入的稀疏性允许使用轮廓作为用于语义感知的图像操作的直观界面：轮廓域中的局部编辑，例如缩放，平移和擦除，转换为长程和连贯的变化像素空间。对各种数据集的实验验证了我们模型提供的多功能性和便利性。

##### URL
[https://arxiv.org/abs/1712.08232](https://arxiv.org/abs/1712.08232)

##### PDF
[https://arxiv.org/pdf/1712.08232](https://arxiv.org/pdf/1712.08232)

