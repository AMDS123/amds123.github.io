---
layout: post
title: "Brain Extraction from Normal and Pathological Images: A Joint PCA/Image-Reconstruction Approach"
date: 2017-11-15 17:57:52
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Xu Han, Roland Kwitt, Stephen Aylward, Bjoern Menze, Alexander Asturias, Paul Vespa, John Van Horn, Marc Niethammer
mathjax: true
---

* content
{:toc}

##### Abstract
Brain extraction from 3D medical images is a common pre-processing step. A variety of approaches exist, but they are frequently only designed to perform brain extraction from images without strong pathologies. Extracting the brain from images exhibiting strong pathologies, for example, the presence of a brain tumor or of a traumatic brain injury (TBI), is challenging. In such cases, tissue appearance may deviate from normal tissue appearance and hence violates algorithmic assumptions for standard approaches; consequently, the brain may not be correctly extracted. This paper proposes a brain extraction approach which can explicitly account for pathologies by jointly modeling normal tissue appearance and pathologies. Specifically, our model uses a three-part image decomposition: (1) normal tissue appearance is captured by principal component analysis (PCA), (2) pathologies are captured via a total variation term, and (3) the skull and surrounding tissue is captured by a sparsity term. Decomposition and image registration steps are alternated to allow statistical modeling of normal tissue appearance in a fixed atlas space. As a beneficial side effect, the model allows for the identification of potentially pathological areas and the reconstruction of a quasi-normal image in atlas space. We demonstrate the effectiveness of our approach on four datasets: the publicly available IBSR and LPBA40 datasets which show normal image appearance, the BRATS dataset containing images with brain tumors, and a dataset containing clinical TBI images. We compare the performance with other popular brain extraction models: ROBEX, BET, BSE and a recently proposed deep learning approach. Our model performs better than these competing approaches on all four datasets. Hence, our approach is an effective method for brain extraction for a wide variety of images with high-quality brain extraction results.

##### Abstract (translated by Google)
从3D医学图像提取脑部是一个常见的预处理步骤。存在各种各样的方法，但是它们经常仅被设计用于从没有强烈病态的图像中执行脑提取。从显示强病理的图像（例如，脑肿瘤或创伤性脑损伤（TBI）的存在）提取大脑是具有挑战性的。在这种情况下，组织外观可能偏离正常的组织外观，因此违反标准方法的算法假设;因此，大脑可能无法正确提取。本文提出了一种脑部提取方法，可以通过联合建模正常组织外观和病理来明确地解释病理。具体而言，我们的模型使用三部分图像分解：（1）通过主成分分析（PCA）捕获正常组织外观，（2）通过总变异项捕获病理学，（3）颅骨和周围组织由稀疏项捕获。分解和图像配准步骤交替，以允许在固定的阿特拉斯空间的正常组织外观的统计建模。作为一种有益的副作用，该模型允许在阿特拉斯空间中识别潜在的病理区域和准正态图像的重建。我们证明了我们的方法在四个数据集上的有效性：公开可用的显示正常图像外观的IBSR和LPBA40数据集，包含脑肿瘤图像的BRATS数据集和包含临床TBI图像的数据集。我们比较其他流行的脑部提取模型的性能：ROBEX，BET，BSE和最近提出的深度学习方法。我们的模型在所有四个数据集上的表现都优于这些竞争方法。因此，我们的方法是一种高质量的脑提取结果，提取各种图像的脑部提取的有效方法。

##### URL
[https://arxiv.org/abs/1711.05702](https://arxiv.org/abs/1711.05702)

##### PDF
[https://arxiv.org/pdf/1711.05702](https://arxiv.org/pdf/1711.05702)

