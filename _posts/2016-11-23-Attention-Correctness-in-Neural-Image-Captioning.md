---
layout: post
title: "Attention Correctness in Neural Image Captioning"
date: 2016-11-23 07:29:46
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption Deep_Learning
author: Chenxi Liu, Junhua Mao, Fei Sha, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Attention mechanisms have recently been introduced in deep learning for various tasks in natural language processing and computer vision. But despite their popularity, the "correctness" of the implicitly-learned attention maps has only been assessed qualitatively by visualization of several examples. In this paper we focus on evaluating and improving the correctness of attention in neural image captioning models. Specifically, we propose a quantitative evaluation metric for the consistency between the generated attention maps and human annotations, using recently released datasets with alignment between regions in images and entities in captions. We then propose novel models with different levels of explicit supervision for learning attention maps during training. The supervision can be strong when alignment between regions and caption entities are available, or weak when only object segments and categories are provided. We show on the popular Flickr30k and COCO datasets that introducing supervision of attention maps during training solidly improves both attention correctness and caption quality, showing the promise of making machine perception more human-like.

##### Abstract (translated by Google)
最近在深度学习中引入了注意机制，用于自然语言处理和计算机视觉的各种任务。但是，尽管它们很受欢迎，隐性学习的关注图的“正确性”只是通过几个例子的可视化来定性评估。在本文中，我们着重于评估和改善神经图像字幕模型中的注意力的正确性。具体来说，我们提出了一个量化评估指标，用于生成关注地图和人类注释之间的一致性，使用最近发布的数据集，图像中的区域和字幕中的实体之间进行对齐。然后，我们提出了不同层次的显式监督的新模型，用于训练期间的学习关注地图。区域和标题实体之间的对齐可以是强有力的，只有提供对象分区和类别时，监督才是有力的。我们在受欢迎的Flickr30k和COCO数据集上展示了在培训期间引入关注地图的监督，可以显着提高注意正确性和字幕质量，显示出使机器感知更像人类的承诺。

##### URL
[https://arxiv.org/abs/1605.09553](https://arxiv.org/abs/1605.09553)

