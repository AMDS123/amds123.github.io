---
layout: post
title:  'A Two-Streamed Network for Estimating Fine-Scaled Depth Maps from Single RGB Images'
date:   2017-12-05 18:47:33
categories: CV
tags: CV
author: Jun Li, Reinhard Klein, Angela Yao
---

* content
{:toc}

##### Abstract
Estimating depth from a single RGB image is an ill-posed and inherently ambiguous problem. State-of-the-art deep learning methods can now estimate accurate 2D depth maps, but when the maps are projected into 3D, they lack local detail and are often highly distorted. We propose a fast-to-train two-streamed CNN that predicts depth and depth gradients, which are then fused together into an accurate and detailed depth map. We also define a novel set loss over multiple images; by regularizing the estimation between a common set of images, the network is less prone to over-fitting and achieves better accuracy than competing methods. Experiments on the NYU Depth v2 dataset shows that our depth predictions are competitive with state-of-the-art and lead to faithful 3D projections.

##### Abstract (translated by Google)
从单个RGB图像估计深度是一个不适当的，固有的模糊问题。现在最先进的深度学习方法现在可以估算精确的二维深度图，但是当这些图投影到三维图中时，它们缺乏局部细节，并且往往是高度失真的。我们提出了一种快速训练的双流CNN，可以预测深度和深度梯度，然后将这些梯度融合在一起，形成精确而详细的深度图。我们还定义了一个新的集合损失多个图像;通过规范一组普通的图像之间的估计，网络不太容易过度拟合，并且实现比竞争方法更好的准确性。在纽约大学深度v2数据集上进行的实验表明，我们的深度预测与最先进的技术相比具有竞争力，并且可以实现忠实的3D投影。

##### URL
[http://arxiv.org/abs/1607.00730](http://arxiv.org/abs/1607.00730)

