---
layout: post
title: "Beyond Spatial Auto-Regressive Models: Predicting Housing Prices with Satellite Imagery"
date: 2016-10-16 01:17:19
categories: arXiv_CV
tags: arXiv_CV CNN Relation
author: Archith J. Bency, Swati Rallapalli, Raghu K. Ganti, Mudhakar Srivatsa, B. S. Manjunath
mathjax: true
---

* content
{:toc}

##### Abstract
When modeling geo-spatial data, it is critical to capture spatial correlations for achieving high accuracy. Spatial Auto-Regression (SAR) is a common tool used to model such data, where the spatial contiguity matrix (W) encodes the spatial correlations. However, the efficacy of SAR is limited by two factors. First, it depends on the choice of contiguity matrix, which is typically not learnt from data, but instead, is assumed to be known apriori. Second, it assumes that the observations can be explained by linear models. In this paper, we propose a Convolutional Neural Network (CNN) framework to model geo-spatial data (specifi- cally housing prices), to learn the spatial correlations automatically. We show that neighborhood information embedded in satellite imagery can be leveraged to achieve the desired spatial smoothing. An additional upside of our framework is the relaxation of linear assumption on the data. Specific challenges we tackle while implementing our framework include, (i) how much of the neighborhood is relevant while estimating housing prices? (ii) what is the right approach to capture multiple resolutions of satellite imagery? and (iii) what other data-sources can help improve the estimation of spatial correlations? We demonstrate a marked improvement of 57% on top of the SAR baseline through the use of features from deep neural networks for the cities of London, Birmingham and Liverpool.

##### Abstract (translated by Google)
在对地理空间数据进行建模时，捕获空间相关性以实现高精度至关重要。空间自回归（SAR）是用于模拟这种数据的常用工具，其中空间邻接矩阵（W）编码空间相关性。然而，SAR的功效受到两个因素的限制。首先，它取决于连续性矩阵的选择，通常不是从数据中学习，而是假设已知的先验。其次，它假定观测值可以用线性模型来解释。在本文中，我们提出了一个卷积神经网络（CNN）框架来模拟地理空间数据（特别是房价），以自动学习空间相关性。我们显示嵌入在卫星图像中的邻域信息可以被用来实现期望的空间平滑。我们框架的另外一个优势是放宽对数据的线性假设。我们在实施我们的框架时遇到的具体挑战包括（i）在估算房价时，有多少邻里关系相关？ （ii）捕捉卫星图像多重分辨率的正确方法是什么？ （iii）还有哪些其他数据来源可以帮助改进空间相关性的估计？通过使用来自伦敦，伯明翰和利物浦等城市的深层神经网络的特征，我们在SAR基线之上显示出57％的显着提高。

##### URL
[https://arxiv.org/abs/1610.04805](https://arxiv.org/abs/1610.04805)

##### PDF
[https://arxiv.org/pdf/1610.04805](https://arxiv.org/pdf/1610.04805)

