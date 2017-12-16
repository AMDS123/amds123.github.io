---
layout: post
title: "PCANet-II: When PCANet Meets the Second Order Pooling"
date: 2017-09-30 09:11:38
categories: arXiv_CV
tags: arXiv_CV CNN
author: Lei Tian, Xiaopeng Hong, Guoying Zhao, Chunxiao Fan, Yue Ming, Matti Pietikäinen
mathjax: true
---

* content
{:toc}

##### Abstract
PCANet, as one noticeable shallow network, employs the histogram representation for feature pooling. However, there are three main problems about this kind of pooling method. First, the histogram-based pooling method binarizes the feature maps and leads to inevitable discriminative information loss. Second, it is difficult to effectively combine other visual cues into a compact representation, because the simple concatenation of various visual cues leads to feature representation inefficiency. Third, the dimensionality of histogram-based output grows exponentially with the number of feature maps used. In order to overcome these problems, we propose a novel shallow network model, named as PCANet-II. Compared with the histogram-based output, the second order pooling not only provides more discriminative information by preserving both the magnitude and sign of convolutional responses, but also dramatically reduces the size of output features. Thus we combine the second order statistical pooling method with the shallow network, i.e., PCANet. Moreover, it is easy to combine other discriminative and robust cues by using the second order pooling. So we introduce the binary feature difference encoding scheme into our PCANet-II to further improve robustness. Experiments demonstrate the effectiveness and robustness of our proposed PCANet-II method.

##### Abstract (translated by Google)
PCANet作为一个明显的浅层网络，采用直方图表示进行特征池化。但是这种池化方法存在三个主要问题。首先，基于直方图的池化方法对特征图进行二值化，并导致不可避免的区分性信息丢失。其次，将其他视觉线索有效地组合成一个紧凑的表示是困难的，因为各种视觉线索的简单连接导致特征表示效率低下。第三，基于直方图的输出的维数随着所使用的特征图的数量呈指数增长。为了克服这些问题，我们提出了一种新的浅层网络模型，命名为PCANet-II。与基于直方图的输出相比，二阶汇总不仅通过保留卷积响应的幅度和符号来提供更多的判别性信息，而且显着减小了输出特征的大小。因此，我们将二阶统计池方法与浅层网络即PCANet结合起来。而且，通过使用二阶池可以很容易地组合其他的判别和强大的线索。所以我们在PCANet-II中引入了二进制特征差分编码方案以进一步提高鲁棒性。实验证明了我们提出的PCANet-II方法的有效性和鲁棒性。

##### URL
[https://arxiv.org/abs/1710.00166](https://arxiv.org/abs/1710.00166)

##### PDF
[https://arxiv.org/pdf/1710.00166](https://arxiv.org/pdf/1710.00166)

