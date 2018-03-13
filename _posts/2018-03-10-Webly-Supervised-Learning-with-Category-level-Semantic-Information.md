---
layout: post
title: "Webly Supervised Learning with Category-level Semantic Information"
date: 2018-03-10 19:30:43
categories: arXiv_CV
tags: arXiv_CV Classification
author: Li Niu, Qingtao Tang
mathjax: true
---

* content
{:toc}

##### Abstract
As tons of photos are being uploaded to public websites (e.g., Flickr, Bing, and Google) every day, learning from web data has become an increasingly popular research direction because of freely available web resources, which is also referred to as webly supervised learning. Nevertheless, the performance gap between webly supervised learning and traditional supervised learning is still very large, owning to the label noise of web data as well as the domain shift between web data and test data. To be exact, on one hand, the labels of images crawled from public websites are very noisy and often inaccurate. On the other hand, the data distributions between web data and test data are considerably different, which is known as domain shift. Some existing works tend to facilitate learning from web data with the aid of extra information, such as augmenting or purifying web data by virtue of instance-level supervision, which is usually in demand of heavy manual annotation. Instead, we propose to tackle the label noise and domain shift by leveraging more accessible category-level supervision. In particular, we build our method upon variational autoencoder (VAE), in which the classification network is attached on the hidden layer of VAE in a way that the classification network and VAE can jointly leverage the category-level hybrid semantic information. Moreover, we further extend our method to cope with the domain shift by utilizing unlabeled test instances in the training stage followed by low-rank refinement. The effectiveness of our proposed methods is clearly demonstrated by extensive experiments on three benchmark datasets.

##### Abstract (translated by Google)
随着大量照片每天都上传到公共网站（例如Flickr，Bing和Google），由于免费提供网络资源，网络数据学习已成为越来越流行的研究方向，这也被称为网络监督学习。然而，由于网络数据的标签噪声以及网络数据和测试数据之间的域转移，网络监督学习和传统监督学习之间的性能差距仍然很大。确切地说，一方面，从公共网站爬取的图像标签非常嘈杂，通常不准确。另一方面，网络数据和测试数据之间的数据分布差别很大，这就是所谓的域转移。一些现有的作品倾向于借助于额外的信息来帮助学习网络数据，例如通过实例级别的监督来增强或净化网络数据，这通常需要大量的手动注释。相反，我们建议通过利用更多可访问的类别级别监督来解决标签噪音和域名转移问题。具体而言，我们在变分自动编码器（VAE）上构建了我们的方法，其中分类网络以分类网络和VAE可以共同利用类别级别混合语义信息的方式附加在VAE的隐藏层上。此外，我们进一步扩展我们的方法，通过在训练阶段利用未标记的测试实例，然后进行低级细化来应对域转移。我们提出的方法的有效性可以通过对三个基准数据集进行广泛的实验清楚地证明。

##### URL
[https://arxiv.org/abs/1803.03857](https://arxiv.org/abs/1803.03857)

##### PDF
[https://arxiv.org/pdf/1803.03857](https://arxiv.org/pdf/1803.03857)

