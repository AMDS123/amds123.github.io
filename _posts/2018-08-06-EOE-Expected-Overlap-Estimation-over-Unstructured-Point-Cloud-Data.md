---
layout: post
title: "EOE: Expected Overlap Estimation over Unstructured Point Cloud Data"
date: 2018-08-06 23:39:27
categories: arXiv_CV
tags: arXiv_CV
author: Ben Eckart, Kihwan Kim, Jan Kautz
mathjax: true
---

* content
{:toc}

##### Abstract
We present an iterative overlap estimation technique to augment existing point cloud registration algorithms that can achieve high performance in difficult real-world situations where large pose displacement and non-overlapping geometry would otherwise cause traditional methods to fail. Our approach estimates overlapping regions through an iterative Expectation Maximization procedure that encodes the sensor field-of-view into the registration process. The proposed technique, Expected Overlap Estimation (EOE), is derived from the observation that differences in field-of-view violate the iid assumption implicitly held by all maximum likelihood based registration techniques. We demonstrate how our approach can augment many popular registration methods with minimal computational overhead. Through experimentation on both synthetic and real-world datasets, we find that adding an explicit overlap estimation step can aid robust outlier handling and increase the accuracy of both ICP-based and GMM-based registration methods, especially in large unstructured domains and where the amount of overlap between point clouds is very small.

##### Abstract (translated by Google)
我们提出了一种迭代重叠估计技术，以增强现有的点云配准算法，该算法可以在困难的现实世界情况下实现高性能，在这种情况下，大的姿态位移和非重叠几何将导致传统方法失败。我们的方法通过迭代期望最大化过程来估计重叠区域，该过程将传感器视野编码到注册过程中。所提出的技术，预期重叠估计（EOE），是从观察视野中的差异违反所有基于最大似然的配准技术隐含地保持的iid假设的观察得到的。我们演示了我们的方法如何以最小的计算开销增加许多流行的注册方法。通过对合成数据集和实际数据集的实验，我们发现添加显式重叠估计步骤可以帮助进行强大的异常值处理，并提高基于ICP和GMM的注册方法的准确性，尤其是在大型非结构化域和数量上点云之间的重叠非常小。

##### URL
[http://arxiv.org/abs/1808.02155](http://arxiv.org/abs/1808.02155)

##### PDF
[http://arxiv.org/pdf/1808.02155](http://arxiv.org/pdf/1808.02155)

