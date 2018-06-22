---
layout: post
title: "Can Deep Learning Relax Endomicroscopy Hardware Miniaturization Requirements?"
date: 2018-06-21 17:28:00
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN Deep_Learning Quantitative
author: Saeed Izadi, Kathleen P. Moriarty, Ghassan Hamarneh
mathjax: true
---

* content
{:toc}

##### Abstract
Confocal laser endomicroscopy (CLE) is a novel imaging modality that provides in vivo histological cross-sections of examined tissue. Recently, attempts have been made to develop miniaturized in vivo imaging devices, specifically confocal laser microscopes, for both clinical and research applications. However, current implementations of miniature CLE components, such as confocal lenses, compromise image resolution, signal-to-noise ratio, or both, which negatively impacts the utility of in vivo imaging. In this work, we demonstrate that software-based techniques can be used to recover lost information due to endomicroscopy hardware miniaturization and reconstruct images of higher resolution. Particularly, a densely connected convolutional neural network is used to reconstruct a high-resolution CLE image from a low-resolution input. In the proposed network, each layer is directly connected to all subsequent layers, which results in an effective combination of low-level and high-level features and efficient information flow throughout the network. To train and evaluate our network, we use a dataset of 181 high-resolution CLE images. Both quantitative and qualitative results indicate superiority of the proposed network compared to traditional interpolation techniques and competing learning-based methods. This work demonstrates that software-based super-resolution is a viable approach to compensate for loss of resolution due to endoscopic hardware miniaturization.

##### Abstract (translated by Google)
共聚焦激光内显微镜（CLE）是一种新型成像方式，可提供被检查组织的体内组织学横断面。近来，已经尝试开发小型化的体内成像装置，特别是共焦激光显微镜，用于临床和研究应用。然而，微型CLE组件（例如共聚焦镜头）的当前实施方式会损害图像分辨率，信噪比或两者，这会负面影响体内成像的效用。在这项工作中，我们证明了基于软件的技术可以用来恢复由于内显微镜硬件小型化而丢失的信息并重建更高分辨率的图像。特别是，使用密集连接的卷积神经网络从低分辨率输入重建高分辨率CLE图像。在所提出的网络中，每一层直接连接到所有后续层，这导致整个网络中的低层和高层功能以及高效信息流的有效组合。为了训练和评估我们的网络，我们使用了181个高分辨率CLE图像的数据集。定量和定性结果表明，与传统的插值技术和竞争的基于学习的方法相比，所提出的网络具有优越性。这项工作表明，基于软件的超分辨率是弥补因内窥镜硬件小型化而导致分辨率损失的可行方法。

##### URL
[http://arxiv.org/abs/1806.08338](http://arxiv.org/abs/1806.08338)

##### PDF
[http://arxiv.org/pdf/1806.08338](http://arxiv.org/pdf/1806.08338)

