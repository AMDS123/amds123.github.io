---
layout: post
title: "ScanComplete: Large-Scale Scene Completion and Semantic Segmentation for 3D Scans"
date: 2017-12-29 13:17:06
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Inference
author: Angela Dai, Daniel Ritchie, Martin Bokeloh, Scott Reed, Jürgen Sturm, Matthias Nießner
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce ScanComplete, a novel data-driven approach for taking an incomplete 3D scan of a scene as input and predicting a complete 3D model along with per-voxel semantic labels. The key contribution of our method is its ability to handle large scenes with varying spatial extent, managing the cubic growth in data size as scene size increases. To this end, we devise a fully-convolutional generative 3D CNN model whose filter kernels are invariant to the overall scene size. The model can be trained on scene subvolumes but deployed on arbitrarily large scenes at test time. In addition, we propose a coarse-to-fine inference strategy in order to produce high-resolution output while also leveraging large input context sizes. In an extensive series of experiments, we carefully evaluate different model design choices, considering both deterministic and probabilistic models for completion and semantic inference. Our results show that we outperform other methods not only in the size of the environments handled and processing efficiency, but also with regard to completion quality and semantic segmentation performance by a significant margin.

##### Abstract (translated by Google)
我们介绍ScanComplete，一种新颖的数据驱动方法，用于将场景的不完整三维扫描作为输入，并预测一个完整的3D模型以及每个体素语义标签。我们的方法的关键贡献是能够处理具有不同空间范围的大型场景，随着场景大小的增加管理数据大小的立方体增长。为此，我们设计了一个完全卷积生成的3D CNN模型，其滤波核函数对于整个场景尺寸是不变的。该模型可以在场景子卷上进行训练，但是可以在测试时间部署在任意大的场景中。此外，我们提出了一个粗到细的推理策略，以产生高分辨率的输出，同时也利用大的输入上下文大小。在广泛的系列实验中，我们仔细评估了不同的模型设计选择，考虑了完成和语义推断的确定性和概率性模型。我们的研究结果表明，我们不仅在处理环境的大小和处理效率方面优于其他方法，而且在完成质量和语义分割性能方面也有显着的优势。

##### URL
[https://arxiv.org/abs/1712.10215](https://arxiv.org/abs/1712.10215)

##### PDF
[https://arxiv.org/pdf/1712.10215](https://arxiv.org/pdf/1712.10215)

