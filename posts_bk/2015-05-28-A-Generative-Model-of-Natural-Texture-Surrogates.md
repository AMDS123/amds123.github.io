---
layout: post
title: "A Generative Model of Natural Texture Surrogates"
date: 2015-05-28 12:37:15
categories: arXiv_CV
tags: arXiv_CV
author: Niklas Ludtke, Debapriya Das, Lucas Theis, Matthias Bethge
mathjax: true
---

* content
{:toc}

##### Abstract
Natural images can be viewed as patchworks of different textures, where the local image statistics is roughly stationary within a small neighborhood but otherwise varies from region to region. In order to model this variability, we first applied the parametric texture algorithm of Portilla and Simoncelli to image patches of 64X64 pixels in a large database of natural images such that each image patch is then described by 655 texture parameters which specify certain statistics, such as variances and covariances of wavelet coefficients or coefficient magnitudes within that patch. To model the statistics of these texture parameters, we then developed suitable nonlinear transformations of the parameters that allowed us to fit their joint statistics with a multivariate Gaussian distribution. We find that the first 200 principal components contain more than 99% of the variance and are sufficient to generate textures that are perceptually extremely close to those generated with all 655 components. We demonstrate the usefulness of the model in several ways: (1) We sample ensembles of texture patches that can be directly compared to samples of patches from the natural image database and can to a high degree reproduce their perceptual appearance. (2) We further developed an image compression algorithm which generates surprisingly accurate images at bit rates as low as 0.14 bits/pixel. Finally, (3) We demonstrate how our approach can be used for an efficient and objective evaluation of samples generated with probabilistic models of natural images.

##### Abstract (translated by Google)
自然图像可以被看作是不同纹理的拼贴，其中局部图像统计在一个小的邻域内大致是平稳的，但是在不同区域之间是不同的。为了对这种变化进行建模，我们首先应用了Portilla和Simoncelli的参数纹理算法，在自然图像的大型数据库中对64×64像素的块进行成像，以便每个图像块由655个纹理参数描述，这些纹理参数指定某些统计量小波系数的差异和协方差或该小片内的系数大小。为了对这些纹理参数的统计进行建模，我们开发了合适​​的非线性变换参数，使我们能够用多元高斯分布拟合它们的联合统计量。我们发现，前200个主成分包含99％以上的方差，足以生成与所有655个成分产生的感觉非常接近的纹理。我们用以下几种方法来证明模型的有用性：（1）我们对纹理贴片集合进行采样，这些贴图可以直接与自然图像数据库中的贴片样本进行比较，并且可以高度重现其感知外观。 （2）我们进一步开发了一种图像压缩算法，该算法以低至0.14比特/像素的比特率产生出人意料的精确图像。最后，（3）我们演示如何使用我们的方法来对自然图像的概率模型生成的样本进行高效客观的评估。

##### URL
[https://arxiv.org/abs/1505.07672](https://arxiv.org/abs/1505.07672)

##### PDF
[https://arxiv.org/pdf/1505.07672](https://arxiv.org/pdf/1505.07672)

