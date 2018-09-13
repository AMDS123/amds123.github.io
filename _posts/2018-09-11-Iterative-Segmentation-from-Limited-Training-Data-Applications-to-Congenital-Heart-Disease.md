---
layout: post
title: "Iterative Segmentation from Limited Training Data: Applications to Congenital Heart Disease"
date: 2018-09-11 22:17:14
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Danielle F. Pace, Adrian V. Dalca, Tom Brosch, Tal Geva, Andrew J. Powell, J&#xfc;rgen Weese, Mehdi H. Moghari, Polina Golland
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new iterative segmentation model which can be accurately learned from a small dataset. A common approach is to train a model to directly segment an image, requiring a large collection of manually annotated images to capture the anatomical variability in a cohort. In contrast, we develop a segmentation model that recursively evolves a segmentation in several steps, and implement it as a recurrent neural network. We learn model parameters by optimizing the interme- diate steps of the evolution in addition to the final segmentation. To this end, we train our segmentation propagation model by presenting incom- plete and/or inaccurate input segmentations paired with a recommended next step. Our work aims to alleviate challenges in segmenting heart structures from cardiac MRI for patients with congenital heart disease (CHD), which encompasses a range of morphological deformations and topological changes. We demonstrate the advantages of this approach on a dataset of 20 images from CHD patients, learning a model that accurately segments individual heart chambers and great vessels. Com- pared to direct segmentation, the iterative method yields more accurate segmentation for patients with the most severe CHD malformations.

##### Abstract (translated by Google)
我们提出了一种新的迭代分割模型，可以从一个小数据集中准确地学习。常见的方法是训练模型以直接分割图像，需要大量手动注释图像以捕获群组中的解剖变异性。相比之下，我们开发了一个分段模型，该模型以几个步骤递归地演化分段，并将其实现为循环神经网络。除了最终分割之外，我们还通过优化演化的中间步骤来学习模型参数。为此，我们通过提出与推荐的下一步配对的不完整和/或不准确的输入分段来训练我们的分段传播模型。我们的工作旨在缓解先天性心脏病（CHD）患者心脏MRI心脏结构分割的挑战，其中包括一系列形态学变形和拓扑变化。我们在来自CHD患者的20幅图像的数据集上展示了这种方法的优势，学习了一种能够精确分割个体心室和大血管的模型。与直接分割相比，迭代方法可以为患有最严重CHD畸形的患者提供更准确的分割。

##### URL
[http://arxiv.org/abs/1809.04182](http://arxiv.org/abs/1809.04182)

##### PDF
[http://arxiv.org/pdf/1809.04182](http://arxiv.org/pdf/1809.04182)

