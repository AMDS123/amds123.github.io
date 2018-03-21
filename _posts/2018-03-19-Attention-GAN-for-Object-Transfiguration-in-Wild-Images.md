---
layout: post
title: "Attention-GAN for Object Transfiguration in Wild Images"
date: 2018-03-19 04:00:13
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Attention GAN
author: Xinyuan Chen, Chang Xu, Xiaokang Yang, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
This paper studies the object transfiguration problem in wild images. The generative network in classical GANs for object transfiguration often undertakes a dual responsibility: to detect the objects of interests and to convert the object from source domain to target domain. In contrast, we decompose the generative network into two separat networks, each of which is only dedicated to one particular sub-task. The attention network predicts spatial attention maps of images, and the transformation network focuses on translating objects. Attention maps produced by attention network are encouraged to be sparse, so that major attention can be paid to objects of interests. No matter before or after object transfiguration, attention maps should remain constant. In addition, learning attention network can receive more instructions, given the available segmentation annotations of images. Experimental results demonstrate the necessity of investigating attention in object transfiguration, and that the proposed algorithm can learn accurate attention to improve quality of generated images.

##### Abstract (translated by Google)
本文研究野外图像中的目标变形问题。经典GAN中用于对象变形的生成网络经常承担双重责任：检测感兴趣的对象并将对象从源域转换为目标域。相反，我们将生成网络分解成两个分离网络，每个网络只专用于一个特定的子任务。注意网络预测图像的空间关注图，转换网络侧重于翻译对象。鼓励注意力网络产生的注意力地图稀少，以便能够关注对象。无论在物体变形之前还是之后，注意图都应该保持不变。另外，考虑到图像的可用分割注释，学习关注网络可以接收更多指令。实验结果表明了研究物体变形中注意力的必要性，并且该算法可以准确的注意到提高生成图像的质量。

##### URL
[https://arxiv.org/abs/1803.06798](https://arxiv.org/abs/1803.06798)

##### PDF
[https://arxiv.org/pdf/1803.06798](https://arxiv.org/pdf/1803.06798)

