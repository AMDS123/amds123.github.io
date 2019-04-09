---
layout: post
title: "Revealing Scenes by Inverting Structure from Motion Reconstructions"
date: 2019-04-05 22:03:42
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Francesco Pittaluga, Sanjeev J. Koppal, Sing Bing Kang, Sudipta N. Sinha
mathjax: true
---

* content
{:toc}

##### Abstract
Many 3D vision systems localize cameras within a scene using 3D point clouds. Such point clouds are often obtained using structure from motion (SfM), after which the images are discarded to preserve privacy. In this paper, we show, for the first time, that such point clouds retain enough information to reveal scene appearance and compromise privacy. We present a privacy attack that reconstructs color images of the scene from the point cloud. Our method is based on a cascaded U-Net that takes as input, a 2D multichannel image of the points rendered from a specific viewpoint containing point depth and optionally color and SIFT descriptors and outputs a color image of the scene from that viewpoint. Unlike previous feature inversion methods, we deal with highly sparse and irregular 2D point distributions and inputs where many point attributes are missing, namely keypoint orientation and scale, the descriptor image source and the 3D point visibility. We evaluate our attack algorithm on public datasets and analyze the significance of the point cloud attributes. Finally, we show that novel views can also be generated thereby enabling compelling virtual tours of the underlying scene.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03303](http://arxiv.org/abs/1904.03303)

##### PDF
[http://arxiv.org/pdf/1904.03303](http://arxiv.org/pdf/1904.03303)

