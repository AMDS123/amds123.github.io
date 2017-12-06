---
layout: post
title: "Knowing When to Look: Adaptive Attention via A Visual Sentinel for Image Captioning"
date: 2017-06-06 06:59:15
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption
author: Jiasen Lu, Caiming Xiong, Devi Parikh, Richard Socher
---

* content
{:toc}

##### Abstract
Attention-based neural encoder-decoder frameworks have been widely adopted for image captioning. Most methods force visual attention to be active for every generated word. However, the decoder likely requires little to no visual information from the image to predict non-visual words such as "the" and "of". Other words that may seem visual can often be predicted reliably just from the language model e.g., "sign" after "behind a red stop" or "phone" following "talking on a cell". In this paper, we propose a novel adaptive attention model with a visual sentinel. At each time step, our model decides whether to attend to the image (and if so, to which regions) or to the visual sentinel. The model decides whether to attend to the image and where, in order to extract meaningful information for sequential word generation. We test our method on the COCO image captioning 2015 challenge dataset and Flickr30K. Our approach sets the new state-of-the-art by a significant margin.

##### Abstract (translated by Google)
基于注意的神经编码器 - 解码器框架已被广泛用于图像字幕。大多数方法强制视觉注意力为每个生成的单词活跃。然而，解码器可能需要很少或不需要来自图像的视觉信息来预测诸如“the”和“of”之类的非视觉单词。其他可能看起来是可视的词语通常仅仅可以从语言模型中可靠地预测，例如在“在单元上讲话”之后的“红色停止之后”或“电话”之后的“签名”。在本文中，我们提出了一个新的自适应注意模型与视觉哨兵。在每一个时间步骤，我们的模型决定是否参加图像（如果是的话，到哪些地区）或视觉哨兵。该模型决定是否参加图像，并在哪里，为了提取有意义的信息，为顺序词的生成。我们在COCO图像字幕2015挑战数据集和Flickr30K上测试我们的方法。我们的方法确定了新的技术水平。

##### URL
[https://arxiv.org/abs/1612.01887](https://arxiv.org/abs/1612.01887)

