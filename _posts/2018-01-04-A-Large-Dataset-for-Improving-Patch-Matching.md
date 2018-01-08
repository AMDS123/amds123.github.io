---
layout: post
title: "A Large Dataset for Improving Patch Matching"
date: 2018-01-04 17:37:45
categories: arXiv_CV
tags: arXiv_CV
author: Rahul Mitra, Nehal Doiphode, Utkarsh Gautam, Sanath Narayan, Shuaib Ahmed, Sharat Chandran, Arjun Jain
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new dataset for learning local image descriptors which can be used for significantly improved patch matching. Our proposed dataset consists of an order of magnitude more number of scenes, images, and positive and negative correspondences compared to the currently available Multi-View Stereo (MVS) dataset from Brown et al. The new dataset also has better coverage of the overall viewpoint, scale, and lighting changes in comparison to the MVS dataset. Our dataset also provides supplementary information like RGB patches with scale and rotations values, and intrinsic and extrinsic camera parameters which as shown later can be used to customize training data as per application. We train an existing state-of-the-art model on our dataset and evaluate on publicly available benchmarks such as HPatches dataset and Strecha et al.\cite{strecha} to quantify the image descriptor performance. Experimental evaluations show that the descriptors trained using our proposed dataset outperform the current state-of-the-art descriptors trained on MVS by 8%, 4% and 10% on matching, verification and retrieval tasks respectively on the HPatches dataset. Similarly on the Strecha dataset, we see an improvement of 3-5% for the matching task in non-planar scenes.

##### Abstract (translated by Google)
我们提出了一个新的数据集用于学习局部图像描述符，可用于显着改善补丁匹配。与Brown等人目前可用的多视点立体（MVS）数据集相比，我们提出的数据集包含更多数量的场景，图像以及正负对应。与MVS数据集相比，新数据集还可以更好地覆盖整个视点，比例和光照变化。我们的数据集还提供补充信息，如具有比例和旋转值的RGB补丁，以及内部和外部相机参数，如后面所示，可用于根据应用定制训练数据。我们在我们的数据集上训练现有的最先进的模型，并对公开可用的基准进行评估，例如HPatches数据集和Strecha等人\ cite {strecha}来量化图像描述符的性能。实验评估表明，使用我们提出的数据集训练的描述符在HPatches数据集上的匹配，验证和检索任务分别胜过当前在MVS上训练的最新描述符8％，4％和10％。同样在Strecha数据集上，我们看到在非平面场景中匹配任务的改进为3-5％。

##### URL
[http://arxiv.org/abs/1801.01466](http://arxiv.org/abs/1801.01466)

##### PDF
[http://arxiv.org/pdf/1801.01466](http://arxiv.org/pdf/1801.01466)

