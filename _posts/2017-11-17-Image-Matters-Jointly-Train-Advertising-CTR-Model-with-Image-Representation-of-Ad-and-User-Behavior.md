---
layout: post
title: "Image Matters: Jointly Train Advertising CTR Model with Image Representation of Ad and User Behavior"
date: 2017-11-17 11:57:13
categories: arXiv_CV
tags: arXiv_CV Image_Caption Sparse Prediction
author: Tiezheng Ge, Liqin Zhao, Guorui Zhou, Keyu Chen, Shuying Liu, Huiming Yi, Zelin Hu, Bochao Liu, Peng Sun, Haoyu Liu, Pengtao Yi, Sui Huang, Zhiqiang Zhang, Xiaoqiang Zhu, Yu Zhang, Kun Gai
mathjax: true
---

* content
{:toc}

##### Abstract
Click Through Rate(CTR) prediction is vital for online advertising system. Recently sparse ID features are widely adopted in the industry. While the ID features, e.g. the serial number of ad, are of low computation complexity and cheap to acquire, they can reveal little intrinsic information about the ad itself. In this work, we propose a novel Deep Image CTR Model(DICM). DICM i) introduces image content features to exploit the intrinsic description of ad/goods and shows effectiveness on complete dataset in accordance with the product environment of a real commercial advertising system; ii) not only represents ad with image features, but also, for the first time, jointly models the user behaviors and ads with image features to capture user interests. However, the users historical behaviors involve massive images for industry scale training(e.g. 2.4 million images per mini-batch with the batchsize of 60k), which brings great challenges on both computation and storage. To tackle the challenges, we carefully design a highly efficient distributed system which enables daily-updated model training on billions of samples essential for product deployment. Extensive experiments show that the image features can be effective representations as well as good complements to the corresponding ID features.

##### Abstract (translated by Google)
点击率（CTR）预测对于在线广告系统是至关重要的。最近稀疏的ID功能在业界被广泛采用。尽管ID功能，例如广告序列号计算复杂度低，收购成本低，可以揭示广告本身的内在信息。在这项工作中，我们提出了一个新的深度图像CTR模型（DICM）。 DICM i）引入图像内容特征来利用广告/商品的内在描述，并根据真实的商业广告系统的产品环境显示完整数据集的有效性; ii）不仅代表具有图像特征的广告，还首次联合模拟用户行为和广告与图像特征以捕捉用户兴趣。然而，用户的历史行为涉及海量图像的行业规模培训（例如，每小批量240万图像，批量为60k），这给计算和存储带来了很大的挑战。为了应对这些挑战，我们精心设计了一个高效的分布式系统，能够对产品部署所需的数十亿样本进行日常更新的模型培训。大量的实验表明，图像特征可以是有效的表征，也是对相应ID特征的良好补充。

##### URL
[https://arxiv.org/abs/1711.06505](https://arxiv.org/abs/1711.06505)

##### PDF
[https://arxiv.org/pdf/1711.06505](https://arxiv.org/pdf/1711.06505)

