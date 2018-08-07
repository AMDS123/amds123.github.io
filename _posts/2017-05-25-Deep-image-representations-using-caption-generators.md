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
深度学习利用大量标记数据来学习强大的模型。当目标数据集较小时，通常的做法是使用预先训练的模型执行转移学习以学习新的任务特定表示。然而，用于图像识别的预训练的CNN在训练期间提供有关图像的有限信息，其仅是标记。诸如场景检索之类的任务具有从这种弱监督中学到的特征，并且需要更强的监督以更好地理解图像的内容。在本文中，我们利用从标题生成模型中学习的特征来学习新颖的任务特定图像表示。特别是，我们考虑最先进的字幕系统Show and Tell~ \ cite {SnT-pami-2016}和密集区域描述模型DenseCap~ \ cite {densecap-cvpr-2016}。我们证明，由于在训练过程中提供了更丰富的监督，字幕系统学到的功能比CNN更好。此外，我们训练一个具有修改的成对损失的暹罗网络，以融合〜\ cite {SnT-pami-2016}和〜\ cite {densecap-cvpr-2016}学习的特征，并学习适合检索的图像表示。实验表明，所提出的融合利用了各个特征的互补性质，并在基准数据集上产生了最先进的检索结果。

##### URL
[https://arxiv.org/abs/1705.09142](https://arxiv.org/abs/1705.09142)

##### PDF
[https://arxiv.org/pdf/1705.09142](https://arxiv.org/pdf/1705.09142)

