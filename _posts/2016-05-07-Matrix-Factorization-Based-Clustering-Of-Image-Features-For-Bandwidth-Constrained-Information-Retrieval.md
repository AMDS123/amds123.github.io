---
layout: post
title: "Matrix Factorization-Based Clustering Of Image Features For Bandwidth-Constrained Information Retrieval"
date: 2016-05-07 03:46:22
categories: arXiv_CV
tags: arXiv_CV
author: Jacob Chakareski, Immanuel Manohar, Shantanu Rane
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of accurately and efficiently querying a remote server to retrieve information about images captured by a mobile device. In addition to reduced transmission overhead and computational complexity, the retrieval protocol should be robust to variations in the image acquisition process, such as translation, rotation, scaling, and sensor-related differences. We propose to extract scale-invariant image features and then perform clustering to reduce the number of features needed for image matching. Principal Component Analysis (PCA) and Non-negative Matrix Factorization (NMF) are investigated as candidate clustering approaches. The image matching complexity at the database server is quadratic in the (small) number of clusters, not in the (very large) number of image features. We employ an image-dependent information content metric to approximate the model order, i.e., the number of clusters, needed for accurate matching, which is preferable to setting the model order using trial and error. We show how to combine the hypotheses provided by PCA and NMF factor loadings, thereby obtaining more accurate retrieval than using either approach alone. In experiments on a database of urban images, we obtain a top-1 retrieval accuracy of 89% and a top-3 accuracy of 92.5%.

##### Abstract (translated by Google)
我们考虑准确和高效地查询远程服务器以检索关于由移动设备捕获的图像的信息的问题。除了减少传输开销和计算复杂性之外，检索协议应该对图像采集过程中的变化（诸如平移，旋转，缩放和传感器相关差异）具有鲁棒性。我们建议提取尺度不变的图像特征，然后进行聚类，以减少图像匹配所需的特征数量。主成分分析（PCA）和非负矩阵分解（NMF）作为候选聚类方法进行研究。数据库服务器处的图像匹配复杂度在（小）数量的群集中是二次的，而不是在（非常大的）数量的图像特征中。我们采用依赖于图像的信息内容度量来近似精确匹配所需的模型顺序，即集群的数量，这对于使用反复试验来设置模型顺序是优选的。我们展示了如何结合PCA提供的假设和NMF因子加载，从而获得比单独使用任一种方法更准确的检索。在城市图像数据库的实验中，我们获得了89％的前1个检索精度和92.5％的前3个精度。

##### URL
[https://arxiv.org/abs/1605.02140](https://arxiv.org/abs/1605.02140)

##### PDF
[https://arxiv.org/pdf/1605.02140](https://arxiv.org/pdf/1605.02140)

