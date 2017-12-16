---
layout: post
title: "Shape Completion using 3D-Encoder-Predictor CNNs and Shape Synthesis"
date: 2017-04-11 20:48:53
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Angela Dai, Charles Ruizhongtai Qi, Matthias Nießner
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a data-driven approach to complete partial 3D shapes through a combination of volumetric deep neural networks and 3D shape synthesis. From a partially-scanned input shape, our method first infers a low-resolution -- but complete -- output. To this end, we introduce a 3D-Encoder-Predictor Network (3D-EPN) which is composed of 3D convolutional layers. The network is trained to predict and fill in missing data, and operates on an implicit surface representation that encodes both known and unknown space. This allows us to predict global structure in unknown areas at high accuracy. We then correlate these intermediary results with 3D geometry from a shape database at test time. In a final pass, we propose a patch-based 3D shape synthesis method that imposes the 3D geometry from these retrieved shapes as constraints on the coarsely-completed mesh. This synthesis process enables us to reconstruct fine-scale detail and generate high-resolution output while respecting the global mesh structure obtained by the 3D-EPN. Although our 3D-EPN outperforms state-of-the-art completion method, the main contribution in our work lies in the combination of a data-driven shape predictor and analytic 3D shape synthesis. In our results, we show extensive evaluations on a newly-introduced shape completion benchmark for both real-world and synthetic data.

##### Abstract (translated by Google)
我们引入了一种数据驱动方法，通过结合体积深度神经网络和三维形状合成来完成部分3D形状。从部分扫描的输入形状，我们的方法首先推断出一个低分辨率，但完整的输出。为此，我们引入一个由三维卷积层组成的三维编码预测网络（3D-EPN）。训练网络来预测和填写缺失的数据，并对隐含的表面表示进行操作，从而对已知和未知空间进行编码。这使我们能够高精度地预测未知地区的全球结构。然后，我们在测试时将这些中间结果与形状数据库中的三维几何相关联。在最后一遍中，我们提出了一个基于补丁的三维形状合成方法，该方法从这些取回的形状中强制三维几何形状作为约束在粗糙完成的网格上。这个合成过程使我们能够重建精细的细节和生成高分辨率的输出，同时尊重由3D-EPN获得的全局网格结构。尽管我们的3D-EPN的性能优于最先进的完成方法，但我们工作的主要贡献在于将数据驱动的形状预测器和分析的三维形状综合相结合。在我们的研究结果中，我们展示了对现实世界和合成数据的新引入形状完成基准的广泛评估。

##### URL
[https://arxiv.org/abs/1612.00101](https://arxiv.org/abs/1612.00101)

##### PDF
[https://arxiv.org/pdf/1612.00101](https://arxiv.org/pdf/1612.00101)

