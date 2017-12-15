---
layout: post
title: "Hierarchical Multi-resolution Mesh Networks for Brain Decoding"
date: 2017-01-11 20:42:47
categories: arXiv_CV
tags: arXiv_CV
author: Itir Onal Ertugrul, Mete Ozay, Fatos Tunay Yarman Vural
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new framework, called Hierarchical Multi-resolution Mesh Networks (HMMNs), which establishes a set of brain networks at multiple time resolutions of fMRI signal to represent the underlying cognitive process. The suggested framework, first, decomposes the fMRI signal into various frequency subbands using wavelet transforms. Then, a brain network, called mesh network, is formed at each subband by ensembling a set of local meshes. The locality around each anatomic region is defined with respect to a neighborhood system based on functional connectivity. The arc weights of a mesh are estimated by ridge regression formed among the average region time series. In the final step, the adjacency matrices of mesh networks obtained at different subbands are ensembled for brain decoding under a hierarchical learning architecture, called, fuzzy stacked generalization (FSG). Our results on Human Connectome Project task-fMRI dataset reflect that the suggested HMMN model can successfully discriminate tasks by extracting complementary information obtained from mesh arc weights of multiple subbands. We study the topological properties of the mesh networks at different resolutions using the network measures, namely, node degree, node strength, betweenness centrality and global efficiency; and investigate the connectivity of anatomic regions, during a cognitive task. We observe significant variations among the network topologies obtained for different subbands. We, also, analyze the diversity properties of classifier ensemble, trained by the mesh networks in multiple subbands and observe that the classifiers in the ensemble collaborate with each other to fuse the complementary information freed at each subband. We conclude that the fMRI data, recorded during a cognitive task, embed diverse information across the anatomic regions at each resolution.

##### Abstract (translated by Google)
我们提出了一个新的框架，称为分层多分辨率网状网络（HMMNs），它建立了一个在fMRI信号的多个时间分辨率的脑网络来表示潜在的认知过程。所提出的框架首先使用小波变换将fMRI信号分解成各个频率子带。然后，通过集合一组局部网格，在每个子带上形成称为网状网络的脑网络。围绕每个解剖学区域的地点相对于基于功能连通性的邻域系统来定义。网格的弧权重通过在平均区域时间序列之间形成的岭回归来估计。在最后一个步骤中，在不同子带上获得的网状网络的邻接矩阵在层次学习架构（称为模糊堆叠泛化（FSG））下被整合用于脑解码。我们在Human Connectome Project任务-fMRI数据集上的结果反映了建议的HMMN模型能够通过提取从多个子带的网格弧权重获得的互补信息来成功地区分任务。利用节点度，节点强度，中介中心性和全局效率等网络度量，研究不同分辨率网状网络的拓扑性质;并在认知任务期间研究解剖区域的连通性。我们观察到不同子带获得的网络拓扑结构之间的显着差异。我们还分析了分类器集成的多样性特性，通过多个子带中的网状网络进行训练，并观察集合中的分类器彼此协作以融合在每个子带释放的互补信息。我们得出这样的结论：在认知任务中记录的fMRI数据在每个分辨率上在解剖区域中嵌入不同的信息。

##### URL
[https://arxiv.org/abs/1607.07695](https://arxiv.org/abs/1607.07695)

##### PDF
[https://arxiv.org/pdf/1607.07695](https://arxiv.org/pdf/1607.07695)

