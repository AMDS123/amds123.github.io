---
layout: post
title: "PVSS: A Progressive Vehicle Search System for Video Surveillance Networks"
date: 2019-01-10 09:02:08
categories: arXiv_CV
tags: arXiv_CV Detection
author: Xinchen Liu, Wu Liu, Huadong Ma, Shuangqun Li
mathjax: true
---

* content
{:toc}

##### Abstract
This paper is focused on the task of searching for a specific vehicle that appeared in the surveillance networks. Existing methods usually assume the vehicle images are well cropped from the surveillance videos, then use visual attributes, like colors and types, or license plate numbers to match the target vehicle in the image set. However, a complete vehicle search system should consider the problems of vehicle detection, representation, indexing, storage, matching, and so on. Besides, attribute-based search cannot accurately find the same vehicle due to intra-instance changes in different cameras and the extremely uncertain environment. Moreover, the license plates may be misrecognized in surveillance scenes due to the low resolution and noise. In this paper, a Progressive Vehicle Search System, named as PVSS, is designed to solve the above problems. PVSS is constituted of three modules: the crawler, the indexer, and the searcher. The vehicle crawler aims to detect and track vehicles in surveillance videos and transfer the captured vehicle images, metadata and contextual information to the server or cloud. Then multi-grained attributes, such as the visual features and license plate fingerprints, are extracted and indexed by the vehicle indexer. At last, a query triplet with an input vehicle image, the time range, and the spatial scope is taken as the input by the vehicle searcher. The target vehicle will be searched in the database by a progressive process. Extensive experiments on the public dataset from a real surveillance network validate the effectiveness of the PVSS.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.03062](https://arxiv.org/abs/1901.03062)

##### PDF
[https://arxiv.org/pdf/1901.03062](https://arxiv.org/pdf/1901.03062)

