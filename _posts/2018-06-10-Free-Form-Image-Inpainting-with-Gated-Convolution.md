---
layout: post
title: "Free-Form Image Inpainting with Gated Convolution"
date: 2018-06-10 05:51:32
categories: arXiv_CV
tags: arXiv_CV GAN Face Deep_Learning
author: Jiahui Yu, Zhe Lin, Jimei Yang, Xiaohui Shen, Xin Lu, Thomas S. Huang
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel deep learning based image inpainting system to complete images with free-form masks and inputs. The system is based on gated convolutions learned from millions of images without additional labelling efforts. The proposed gated convolution solves the issue of vanilla convolution that treats all input pixels as valid ones, generalizes partial convolution by providing a learnable dynamic feature selection mechanism for each channel at each spatial location across all layers. Moreover, as free-form masks may appear anywhere in images with any shapes, global and local GANs designed for a single rectangular mask are not suitable. To this end, we also present a novel GAN loss, named SN-PatchGAN, by applying spectral-normalized discriminators on dense image patches. It is simple in formulation, fast and stable in training. Results on automatic image inpainting and user-guided extension demonstrate that our system generates higher-quality and more flexible results than previous methods. We show that our system helps users quickly remove distracting objects, modify image layouts, clear watermarks, edit faces and interactively create novel objects in images. Furthermore, visualization of learned feature representations reveals the effectiveness of gated convolution and provides an interpretation of how the proposed neural network fills in missing regions. More high-resolution results and video materials are available at <a href="http://jiahuiyu.com/deepfill2">this http URL</a>

##### Abstract (translated by Google)
我们提出了一种新颖的基于深度学习的图像修复系统，用自由形式的面具和输入来完成图像。该系统基于从数百万图像学习的门控卷积，无需额外的标签工作。所提出的门控卷积解决了将所有输入像素视为有效像素的香草卷积问题，通过在所有层的每个空间位置上为每个通道提供可学习的动态特征选择机制来推广部分卷积。此外，由于自由形式的掩模可能出现在具有任何形状的图像中的任何地方，因此为单个矩形掩模设计的全局和局部GAN不适合。为此，我们还通过在密集图像块上应用谱归一化鉴别器来提出一种新的GAN损失，命名为SN-PatchGAN。配方简单，培训快速稳定。自动图像修补和用户引导扩展的结果表明，我们的系统比以前的方法产生更高质量和更灵活的结果。我们显示，我们的系统可帮助用户快速移除分散注意力的对象，修改图像布局，清除水印，编辑面部并交互式创建图像中的新物体。此外，学习特征表示的可视化揭示门控卷积的有效性，并提供了如何提出的神经网络填补缺失区域的解释。 <a href="http://jiahuiyu.com/deepfill2">此http URL </a>提供更高分辨率的结果和视频资料

##### URL
[http://arxiv.org/abs/1806.03589](http://arxiv.org/abs/1806.03589)

##### PDF
[http://arxiv.org/pdf/1806.03589](http://arxiv.org/pdf/1806.03589)

