---
layout: post
title: "Resampling Forgery Detection Using Deep Learning and A-Contrario Analysis"
date: 2018-03-01 21:59:04
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Detection
author: Arjuna Flenner, Lawrence Peterson, Jason Bunk, Tajuddin Manhar Mohammed, Lakshmanan Nataraj, B.S. Manjunath
mathjax: true
---

* content
{:toc}

##### Abstract
The amount of digital imagery recorded has recently grown exponentially, and with the advancement of software, such as Photoshop or Gimp, it has become easier to manipulate images. However, most images on the internet have not been manipulated and any automated manipulation detection algorithm must carefully control the false alarm rate. In this paper we discuss a method to automatically detect local resampling using deep learning while controlling the false alarm rate using a-contrario analysis. The automated procedure consists of three primary steps. First, resampling features are calculated for image blocks. A deep learning classifier is then used to generate a heatmap that indicates if the image block has been resampled. We expect some of these blocks to be falsely identified as resampled. We use a-contrario hypothesis testing to both identify if the patterns of the manipulated blocks indicate if the image has been tampered with and to localize the manipulation. We demonstrate that this strategy is effective in indicating if an image has been manipulated and localizing the manipulations.

##### Abstract (translated by Google)
记录的数字图像数量近来呈指数增长，随着软件（如Photoshop或Gimp）的进步，图像操作变得更加容易。但是，互联网上的大多数图像都没有被操纵，任何自动操纵检测算法都必须小心控制误报率。在本文中，我们讨论一种使用深度学习自动检测局部重采样的方法，同时使用反式分析来控制虚警率。自动化程序由三个主要步骤组成。首先，针对图像块计算重采样特征。然后使用深度学习分类器生成指示图像块是否已被重新采样的热图。我们预计这些块中的一些被错误地识别为重采样。我们使用反例假设检验来识别操纵块的模式是否表明图像是否被篡改并定位操作。我们证明这种策略在指示图像是否被操纵和本地化操作方面是有效的。

##### URL
[http://arxiv.org/abs/1803.01711](http://arxiv.org/abs/1803.01711)

##### PDF
[http://arxiv.org/pdf/1803.01711](http://arxiv.org/pdf/1803.01711)

