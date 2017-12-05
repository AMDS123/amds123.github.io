---
layout: post
title: 'Deep image representations using caption generators'
date: 2017-12-06 02:40:01
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption Deep_Learning Recognition
author: Konda Reddy Mopuri, Vishal B. Athreya, R. Venkatesh Babu
---

* content
{:toc}

##### Abstract
Deep learning exploits large volumes of labeled data to learn powerful models. When the target dataset is small, it is a common practice to perform transfer learning using pre-trained models to learn new task specific representations. However, pre-trained CNNs for image recognition are provided with limited information about the image during training, which is label alone. Tasks such as scene retrieval suffer from features learned from this weak supervision and require stronger supervision to better understand the contents of the image. In this paper, we exploit the features learned from caption generating models to learn novel task specific image representations. In particular, we consider the state-of-the art captioning system Show and Tell~\cite{SnT-pami-2016} and the dense region description model DenseCap~\cite{densecap-cvpr-2016}. We demonstrate that, owing to richer supervision provided during the process of training, the features learned by the captioning system perform better than those of CNNs. Further, we train a siamese network with a modified pair-wise loss to fuse the features learned by~\cite{SnT-pami-2016} and~\cite{densecap-cvpr-2016} and learn image representations suitable for retrieval. Experiments show that the proposed fusion exploits the complementary nature of the individual features and yields state-of-the art retrieval results on benchmark datasets.

##### Abstract (translated by Google)
深度学习利用大量标记的数据来学习强大的模型。当目标数据集很小时，通常使用预先训练的模型来进行转移学习来学习新的任务特定表示。然而，用于图像识别的预先训练的CNN在训练期间被提供有关图像的有限的信息，仅仅是标签。诸如场景检索之类的任务受到从这种弱监督中学到的特征的影响，需要更强的监督以更好地理解图像的内容。在本文中，我们利用从字幕生成模型学习的特征来学习新颖的任务特定的图像表示。特别是，我们考虑最先进的字幕系统Show and Tell〜\ cite {SnT-pami-2016}和密集区域描述模型DenseCap〜\ cite {densecap-cvpr-2016}。我们证明，由于在训练过程中提供了更丰富的监督，字幕系统学到的功能表现要好于CNN。此外，我们训练一个修改的成对丢失的连体网络，融合〜\ cite {SnT-pami-2016}和〜\ cite {densecap-cvpr-2016}学习到的特征，学习适合检索的图像表示。实验表明，所提出的融合利用了各个特征的互补性质，并在基准数据集上产生了最新的检索结果。

##### URL
[https://arxiv.org/abs/1705.09142](https://arxiv.org/abs/1705.09142)

