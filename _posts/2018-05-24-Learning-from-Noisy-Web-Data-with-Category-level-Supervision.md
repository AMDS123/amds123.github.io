---
layout: post
title: "Learning from Noisy Web Data with Category-level Supervision"
date: 2018-05-24 05:41:17
categories: arXiv_CV
tags: arXiv_CV Classification
author: Li Niu, Qingtao Tang, Ashok Veeraraghavan, Ashu Sabharwal
mathjax: true
---

* content
{:toc}

##### Abstract
As tons of photos are being uploaded to public websites (e.g., Flickr, Bing, and Google) every day, learning from web data has become an increasingly popular research direction because of freely available web resources, which is also referred to as webly supervised learning. Nevertheless, the performance gap between webly supervised learning and traditional supervised learning is still very large, owning to the label noise of web data. To be exact, the labels of images crawled from public websites are very noisy and often inaccurate. Some existing works tend to facilitate learning from web data with the aid of extra information, such as augmenting or purifying web data by virtue of instance-level supervision, which is usually in demand of heavy manual annotation. Instead, we propose to tackle the label noise by leveraging more accessible category-level supervision. In particular, we build our method upon variational autoencoder (VAE), in which the classification network is attached on the hidden layer of VAE in a way that the classification network and VAE can jointly leverage the category-level hybrid semantic information. The effectiveness of our proposed method is clearly demonstrated by extensive experiments on three benchmark datasets.

##### Abstract (translated by Google)
随着大量照片每天都上传到公共网站（例如Flickr，Bing和Google），由于免费提供网络资源，网络数据学习已成为越来越流行的研究方向，这也被称为网络监督学习。然而，由于网络数据的标签噪声，网络监督学习和传统监督学习之间的性能差距仍然很大。确切地说，从公共网站爬取的图像标签非常嘈杂，而且通常不准确。一些现有的作品倾向于借助于额外的信息来帮助学习网络数据，例如通过实例级监督来增强或净化网络数据，这通常需要大量的手动注释。相反，我们建议通过利用更多可访问的类别级别监管来解决标签噪音问题。具体而言，我们在变分自动编码器（VAE）上构建了我们的方法，其中分类网络以VAE的隐含层附接，使得分类网络和VAE可以共同利用类别级混合语义信息。我们提出的方法的有效性在三个基准数据集上进行了广泛的实验。

##### URL
[http://arxiv.org/abs/1803.03857](http://arxiv.org/abs/1803.03857)

##### PDF
[http://arxiv.org/pdf/1803.03857](http://arxiv.org/pdf/1803.03857)

