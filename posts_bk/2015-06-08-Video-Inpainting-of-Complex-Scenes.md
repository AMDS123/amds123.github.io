---
layout: post
title: "Video Inpainting of Complex Scenes"
date: 2015-06-08 06:43:01
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Alasdair Newson, Andrés Almansa (LTCI), Matthieu Fradet, Yann Gousseau, Patrick Pérez
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an automatic video inpainting algorithm which relies on the optimisation of a global, patch-based functional. Our algorithm is able to deal with a variety of challenging situations which naturally arise in video inpainting, such as the correct reconstruction of dynamic textures, multiple moving objects and moving background. Furthermore, we achieve this in an order of magnitude less execution time with respect to the state-of-the-art. We are also able to achieve good quality results on high definition videos. Finally, we provide specific algorithmic details to make implementation of our algorithm as easy as possible. The resulting algorithm requires no segmentation or manual input other than the definition of the inpainting mask, and can deal with a wider variety of situations than is handled by previous work. 1. Introduction. Advanced image and video editing techniques are increasingly common in the image processing and computer vision world, and are also starting to be used in media entertainment. One common and difficult task closely linked to the world of video editing is image and video " inpainting ". Generally speaking, this is the task of replacing the content of an image or video with some other content which is visually pleasing. This subject has been extensively studied in the case of images, to such an extent that commercial image inpainting products destined for the general public are available, such as Photoshop's " Content Aware fill " [1]. However, while some impressive results have been obtained in the case of videos, the subject has been studied far less extensively than image inpainting. This relative lack of research can largely be attributed to high time complexity due to the added temporal dimension. Indeed, it has only very recently become possible to produce good quality inpainting results on high definition videos, and this only in a semi-automatic manner. Nevertheless, high-quality video inpainting has many important and useful applications such as film restoration, professional post-production in cinema and video editing for personal use. For this reason, we believe that an automatic, generic video inpainting algorithm would be extremely useful for both academic and professional communities.

##### Abstract (translated by Google)
我们提出了一种自动视频修补算法，它依赖于全局的，基于补丁的功能的优化。我们的算法能够处理视频修补中自然产生的各种具有挑战性的情况，如动态纹理的正确重构，多个移动对象和移动背景。此外，我们以相对于现有技术的执行时间少一个数量级来实现这一点。我们也能够在高清视频上获得高质量的效果。最后，我们提供了具体的算法细节，使我们的算法实现尽可能简单。除了修复蒙版的定义之外，所产生的算法不需要分割或手动输入，并且可以处理比以前的工作更多的情况。 1.介绍先进的图像和视频编辑技术在图像处理和计算机视觉世界中越来越普遍，并且也开始用于媒体娱乐。与视频编辑世界紧密相连的一个常见而困难的任务是图像和视频“修补”。一般来说，这是将图像或视频内容替换为视觉上令人愉悦的其他内容的任务。在图像的情况下，这个主题已经被广泛的研究，以至于商业图像修复产品的目的地为公众可用，如Photoshop的“内容意识填充”[1]。然而，虽然在视频方面取得了令人印象深刻的成果，但是这个问题的研究远不及图像修复。由于增加了时间维度，这种相对较少的研究可以在很大程度上归因于高时间复杂度。实际上，最近才有可能在高清晰度视频上产生高质量的修补效果，而这只是半自动的。尽管如此，高质量的视频修补还是有许多重要而有用的应用，如电影修复，电影专业后期制作和个人使用的视频编辑。出于这个原因，我们相信一个自动的，通用的视频修复算法对于学术界和专业界都是非常有用的。

##### URL
[https://arxiv.org/abs/1503.05528](https://arxiv.org/abs/1503.05528)

##### PDF
[https://arxiv.org/pdf/1503.05528](https://arxiv.org/pdf/1503.05528)

