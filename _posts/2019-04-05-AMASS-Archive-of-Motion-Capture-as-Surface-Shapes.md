---
layout: post
title: "AMASS: Archive of Motion Capture as Surface Shapes"
date: 2019-04-05 21:00:25
categories: arXiv_CV
tags: arXiv_CV Face Deep_Learning
author: Naureen Mahmood (Meshcapade GmbH), Nima Ghorbani (MPI for Intelligent Systems), Nikolaus F. Troje (York University), Gerard Pons-Moll (MPI for Informatics), Michael J. Black (MPI for Intelligent Systems)
mathjax: true
---

* content
{:toc}

##### Abstract
Large datasets are the cornerstone of recent advances in computer vision using deep learning. In contrast, existing human motion capture (mocap) datasets are small and the motions limited, hampering progress on learning models of human motion. While there are many different datasets available, they each use a different parameterization of the body, making it difficult to integrate them into a single meta dataset. To address this, we introduce AMASS, a large and varied database of human motion that unifies 15 different optical marker-based mocap datasets by representing them within a common framework and parameterization. We achieve this using a new method, MoSh++, that converts mocap data into realistic 3D human meshes represented by a rigged body model; here we use SMPL [doi:10.1145/281<a href="https://export.arxiv.org/abs/6795.28180">6795.28180</a>13], which is widely used and provides a standard skeletal representation as well as a fully rigged surface mesh. The method works for arbitrary marker sets, while recovering soft-tissue dynamics and realistic hand motion. We evaluate MoSh++ and tune its hyperparameters using a new dataset of 4D body scans that are jointly recorded with marker-based mocap. The consistent representation of AMASS makes it readily useful for animation, visualization, and generating training data for deep learning. Our dataset is significantly richer than previous human motion collections, having more than 40 hours of motion data, spanning over 300 subjects, more than 11,000 motions, and will be publicly available to the research community.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03278](http://arxiv.org/abs/1904.03278)

##### PDF
[http://arxiv.org/pdf/1904.03278](http://arxiv.org/pdf/1904.03278)

