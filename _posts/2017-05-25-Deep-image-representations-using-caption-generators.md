---
layout: post
title: "Deep image representations using caption generators"
date: 2017-05-25 12:13:27
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption Transfer_Learning Deep_Learning Recognition
author: Konda Reddy Mopuri, Vishal B. Athreya, R. Venkatesh Babu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning exploits large volumes of labeled data to learn powerful models. When the target dataset is small, it is a common practice to perform transfer learning using pre-trained models to learn new task specific representations. However, pre-trained CNNs for image recognition are provided with limited information about the image during training, which is label alone. Tasks such as scene retrieval suffer from features learned from this weak supervision and require stronger supervision to better understand the contents of the image. In this paper, we exploit the features learned from caption generating models to learn novel task specific image representations. In particular, we consider the state-of-the art captioning system Show and Tell~\cite{SnT-pami-2016} and the dense region description model DenseCap~\cite{densecap-cvpr-2016}. We demonstrate that, owing to richer supervision provided during the process of training, the features learned by the captioning system perform better than those of CNNs. Further, we train a siamese network with a modified pair-wise loss to fuse the features learned by~\cite{SnT-pami-2016} and~\cite{densecap-cvpr-2016} and learn image representations suitable for retrieval. Experiments show that the proposed fusion exploits the complementary nature of the individual features and yields state-of-the art retrieval results on benchmark datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1705.09142](https://arxiv.org/abs/1705.09142)

##### PDF
[https://arxiv.org/pdf/1705.09142](https://arxiv.org/pdf/1705.09142)

