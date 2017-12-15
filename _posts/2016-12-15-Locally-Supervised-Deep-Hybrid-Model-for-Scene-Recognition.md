---
layout: post
title: "Locally-Supervised Deep Hybrid Model for Scene Recognition"
date: 2016-12-15 21:30:09
categories: arXiv_CV
tags: arXiv_CV Image_Caption CNN Image_Classification Classification Recognition
author: Sheng Guo, Weilin Huang, Limin Wang, Yu Qiao
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNN) have recently achieved remarkable successes in various image classification and understanding tasks. The deep features obtained at the top fully-connected layer of the CNN (FC-features) exhibit rich global semantic information and are extremely effective in image classification. On the other hand, the convolutional features in the middle layers of the CNN also contain meaningful local information, but are not fully explored for image representation. In this paper, we propose a novel Locally-Supervised Deep Hybrid Model (LS-DHM) that effectively enhances and explores the convolutional features for scene recognition. Firstly, we notice that the convolutional features capture local objects and fine structures of scene images, which yield important cues for discriminating ambiguous scenes, whereas these features are significantly eliminated in the highly-compressed FC representation. Secondly, we propose a new Local Convolutional Supervision (LCS) layer to enhance the local structure of the image by directly propagating the label information to the convolutional layers. Thirdly, we propose an efficient Fisher Convolutional Vector (FCV) that successfully rescues the orderless mid-level semantic information (e.g. objects and textures) of scene image. The FCV encodes the large-sized convolutional maps into a fixed-length mid-level representation, and is demonstrated to be strongly complementary to the high-level FC-features. Finally, both the FCV and FC-features are collaboratively employed in the LSDHM representation, which achieves outstanding performance in our experiments. It obtains 83.75% and 67.56% accuracies respectively on the heavily benchmarked MIT Indoor67 and SUN397 datasets, advancing the stat-of-the-art substantially.

##### Abstract (translated by Google)
卷积神经网络（CNN）最近在各种图像分类和理解任务中取得了显着的成功。 CNN（FC-特征）顶部全连接层获得的深层特征展现出丰富的全局语义信息，在图像分类中非常有效。另一方面，CNN中间层的卷积特征也包含有意义的局部信息，但对图像表示还没有充分的探索。在本文中，我们提出了一种新的局部监督深度混合模型（LS-DHM），有效地提高和探索了场景识别的卷积特征。首先，我们注意到卷积特征捕获场景图像的局部对象和精细结构，这些特征产生了用于区分模糊场景的重要线索，而在高度压缩的FC表示中这些特征被显着消除。其次，提出了一种新的局部卷积监督（LCS）层，通过直接将标签信息传递给卷积层来增强图像的局部结构。再次，提出了一种高效的Fisher卷积矢量（FCV），成功地挽救了场景图像中无序的中级语义信息（如对象和纹理）。 FCV将大尺寸卷积映射编码为固定长度的中间表示，并且被证明与高级FC特征强烈互补。最后，在LSDHM表示中，FCV和FC-feature都被合作使用，在我们的实验中取得了优异的表现。它们分别在基准MIT Indoor67和SUN397数据集上分别获得了83.75％和67.56％的精度，大大提高了技术水平。

##### URL
[https://arxiv.org/abs/1601.07576](https://arxiv.org/abs/1601.07576)

##### PDF
[https://arxiv.org/pdf/1601.07576](https://arxiv.org/pdf/1601.07576)

