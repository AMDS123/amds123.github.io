---
layout: post
title: "Visual descriptors for content-based retrieval of remote sensing images"
date: 2017-08-08 09:36:07
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval CNN
author: Paolo Napoletano
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present an extensive evaluation of visual descriptors for the content-based retrieval of remote sensing (RS) images. The evaluation includes global hand-crafted, local hand-crafted, and Convolutional Neural Network (CNNs) features coupled with four different Content-Based Image Retrieval schemes. We conducted all the experiments on two publicly available datasets: the 21-class UC Merced Land Use/Land Cover (LandUse) dataset and 19-class High-resolution Satellite Scene dataset (SceneSat). The content of RS images might be quite heterogeneous, ranging from images containing fine grained textures, to coarse grained ones or to images containing objects. It is therefore not obvious in this domain, which descriptor should be employed to describe images having such a variability. Results demonstrate that CNN-based features perform better than both global and and local hand-crafted features whatever is the retrieval scheme adopted. Features extracted from SatResNet-50, a residual CNN suitable fine-tuned on the RS domain, shows much better performance than a residual CNN pre-trained on multimedia scene and object images. Features extracted from NetVLAD, a CNN that considers both CNN and local features, works better than others CNN solutions on those images that contain fine-grained textures and objects.

##### Abstract (translated by Google)
在本文中，我们提出了对基于内容的遥感（RS）图像检索的视觉描述符的广泛评估。评估包括全球手工制作，本地手工制作和卷积神经网络（CNNs）特征以及四种不同的基于内容的图像检索方案。我们在两个公开可用的数据集上进行了所有的实验：21级UC Merced土地利用/土地覆盖（LandUse）数据集和19级高分辨率卫星场景数据集（SceneSat）。 RS图像的内容可能是非常不均匀的，从包含细粒度纹理的图像到粗粒度图像或包含对象的图像。因此在这个领域中不明显，应该使用哪个描述符来描述具有这种变化的图像。结果表明，基于CNN的特征比全球和当地的手工特征表现都好，无论采用何种检索方案。从SatResNet-50提取的特征，在RS域上精确调整的残余CNN，比在多媒体场景和目标图像上预先训练的残余CNN表现出更好的性能。从NetVLAD中提取的特征，一个考虑CNN和本地特征的CNN，比那些包含细粒度纹理和对象的图像上的其他CNN解决方案效果更好。

##### URL
[https://arxiv.org/abs/1602.00970](https://arxiv.org/abs/1602.00970)

##### PDF
[https://arxiv.org/pdf/1602.00970](https://arxiv.org/pdf/1602.00970)

