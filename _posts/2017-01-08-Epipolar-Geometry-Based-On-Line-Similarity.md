---
layout: post
title: "Epipolar Geometry Based On Line Similarity"
date: 2017-01-08 00:11:14
categories: arXiv_CV
tags: arXiv_CV
author: Gil Ben-Artzi, Tavi Halperin, Michael Werman, Shmuel Peleg
mathjax: true
---

* content
{:toc}

##### Abstract
It is known that epipolar geometry can be computed from three epipolar line correspondences but this computation is rarely used in practice since there are no simple methods to find corresponding lines. Instead, methods for finding corresponding points are widely used. This paper proposes a similarity measure between lines that indicates whether two lines are corresponding epipolar lines and enables finding epipolar line correspondences as needed for the computation of epipolar geometry. A similarity measure between two lines, suitable for video sequences of a dynamic scene, has been previously described. This paper suggests a stereo matching similarity measure suitable for images. It is based on the quality of stereo matching between the two lines, as corresponding epipolar lines yield a good stereo correspondence. Instead of an exhaustive search over all possible pairs of lines, the search space is substantially reduced when two corresponding point pairs are given. We validate the proposed method using real-world images and compare it to state-of-the-art methods. We found this method to be more accurate by a factor of five compared to the standard method using seven corresponding points and comparable to the 8-points algorithm.

##### Abstract (translated by Google)
已知可以从三个极线对应关系计算极线几何，但是由于没有简单的方法来找到相应的线，所以这种计算在实践中很少使用。相反，找到对应点的方法被广泛使用。本文提出了一个线之间的相似性度量，表明两条线是否是相应的极线，并能够根据需要计算极线几何。之前已经描述了适合于动态场景的视频序列的两行之间的相似性度量。本文提出了一种适用于图像的立体匹配相似性度量。它是基于两条线之间的立体匹配的质量，因为对应的极线产生良好的立体对应。不是对所有可能的线对进行彻底搜索，而是在给出两个相应的点对时大大减少搜索空间。我们验证提出的方法使用真实世界的图像，并将其与最先进的方法进行比较。与使用7个对应点的标准方法相比，我们发现该方法更精确5倍，与8点算法相当。

##### URL
[https://arxiv.org/abs/1604.04848](https://arxiv.org/abs/1604.04848)

##### PDF
[https://arxiv.org/pdf/1604.04848](https://arxiv.org/pdf/1604.04848)

