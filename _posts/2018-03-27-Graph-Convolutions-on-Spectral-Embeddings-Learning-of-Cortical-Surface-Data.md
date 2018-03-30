---
layout: post
title: "Graph Convolutions on Spectral Embeddings: Learning of Cortical Surface Data"
date: 2018-03-27 21:25:12
categories: arXiv_CV
tags: arXiv_CV Face Embedding
author: Karthik Gopinath, Christian Desrosiers, Herve Lombaert
mathjax: true
---

* content
{:toc}

##### Abstract
Neuronal cell bodies mostly reside in the cerebral cortex. The study of this thin and highly convoluted surface is essential for understanding how the brain works. The analysis of surface data is, however, challenging due to the high variability of the cortical geometry. This paper presents a novel approach for learning and exploiting surface data directly across surface domains. Current approaches rely on geometrical simplifications, such as spherical inflations, a popular but costly process. For instance, the widely used FreeSurfer takes about 3 hours to parcellate brain surfaces on a standard machine. Direct learning of surface data via graph convolutions would provide a new family of fast algorithms for processing brain surfaces. However, the current limitation of existing state-of-the-art approaches is their inability to compare surface data across different surface domains. Surface bases are indeed incompatible between brain geometries. This paper leverages recent advances in spectral graph matching to transfer surface data across aligned spectral domains. This novel approach enables a direct learning of surface data across compatible surface bases. It exploits spectral filters over intrinsic representations of surface neighborhoods. We illustrate the benefits of this approach with an application to brain parcellation. We validate the algorithm over 101 manually labeled brain surfaces. The results show a significant improvement in labeling accuracy over recent Euclidean approaches, while gaining a drastic speed improvement over conventional methods.

##### Abstract (translated by Google)
神经元细胞体大多存在于大脑皮质中。对这个薄而高度复杂的表面的研究对于理解大脑的工作方式至关重要。然而，表面数据的分析由于皮质几何形状的高度可变性而具有挑战性。本文介绍了一种用于直接跨表面域学习和利用表面数据的新方法。目前的方法依赖于几何简化，例如球形通货膨胀，这是一种流行但昂贵的过程。例如，广泛使用的FreeSurfer花费大约3个小时在标准机器上分割大脑表面。通过图形卷积直接学习曲面数据将为处理大脑表面提供一个新的快速算法族。然而，目前现有技术方法的当前局限性是它们无法比较不同表面域的表面数据。表面基部确实在脑几何之间不相容。本文利用频谱图匹配的最新进展在对齐的频谱域上传输表面数据。这种新颖的方法可以在兼容的表面基础上直接学习表面数据。它利用频谱滤波器对表面邻域的内在表示进行处理。我们通过应用于脑区划来说明这种方法的好处。我们通过101个手动标记的脑表面验证算法。结果显示，与最近的欧几里得方法相比，标注精度显着提高，同时相对于传统方法获得了显着的速度提升。

##### URL
[https://arxiv.org/abs/1803.10336](https://arxiv.org/abs/1803.10336)

##### PDF
[https://arxiv.org/pdf/1803.10336](https://arxiv.org/pdf/1803.10336)

