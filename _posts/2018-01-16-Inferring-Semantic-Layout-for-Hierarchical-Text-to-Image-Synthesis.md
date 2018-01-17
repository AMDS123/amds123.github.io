---
layout: post
title: "Inferring Semantic Layout for Hierarchical Text-to-Image Synthesis"
date: 2018-01-16 01:49:29
categories: arXiv_CV
tags: arXiv_CV
author: Seunghoon Hong, Dingdong Yang, Jongwook Choi, Honglak Lee
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel hierarchical approach for text-to-image synthesis by inferring semantic layout. Instead of learning a direct mapping from text to image, our algorithm decomposes the generation process into multiple steps, in which it first constructs a semantic layout from the text by the layout generator and converts the layout to an image by the image generator. The proposed layout generator progressively constructs a semantic layout in a coarse-to-fine manner by generating object bounding boxes and refining each box by estimating object shapes inside the box. The image generator synthesizes an image conditioned on the inferred semantic layout, which provides a useful semantic structure of an image matching with the text description. Our model not only generates semantically more meaningful images, but also allows automatic annotation of generated images and user-controlled generation process by modifying the generated scene layout. We demonstrate the capability of the proposed model on challenging MS-COCO dataset and show that the model can substantially improve the image quality, interpretability of output and semantic alignment to input text over existing approaches.

##### Abstract (translated by Google)
我们通过推断语义布局提出了一种新的文本到图像合成的分层方法。我们的算法不是直接从文本映射到图像，而是将生成过程分解为多个步骤，首先由布局生成器从文本中构建语义布局，然后通过图像生成器将布局转换为图像。所提出的布局生成器通过生成对象边界框逐渐地以粗到细的方式构建语义布局，并通过估计框内的对象形状来细化每个框。图像生成器合成基于推断的语义布局的图像，其提供与文本描述匹配的图像的有用的语义结构。我们的模型不仅在语义上生成更有意义的图像，而且允许通过修改生成的场景布局来自动注释生成的图像和用户控制的生成过程。我们证明了提出的模型在挑战MS-COCO数据集上的能力，并证明该模型能够显着提高图像质量，输出文本的解释性和语义对齐。

##### URL
[http://arxiv.org/abs/1801.05091](http://arxiv.org/abs/1801.05091)

##### PDF
[http://arxiv.org/pdf/1801.05091](http://arxiv.org/pdf/1801.05091)

