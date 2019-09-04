---
layout: post
title: "Deep Mesh Reconstruction from Single RGB Images via Topology Modification Networks"
date: 2019-09-01 04:17:41
categories: arXiv_CV
tags: arXiv_CV Face Deep_Learning Quantitative
author: Junyi Pan, Xiaoguang Han, Weikai Chen, Jiapeng Tang, Kui Jia
mathjax: true
---

* content
{:toc}

##### Abstract
Reconstructing the 3D mesh of a general object from a single image is now possible thanks to the latest advances of deep learning technologies. However, due to the nontrivial difficulty of generating a feasible mesh structure, the state-of-the-art approaches often simplify the problem by learning the displacements of a template mesh that deforms it to the target surface. Though reconstructing a 3D shape with complex topology can be achieved by deforming multiple mesh patches, it remains difficult to stitch the results to ensure a high meshing quality. In this paper, we present an end-to-end single-view mesh reconstruction framework that is able to generate high-quality meshes with complex topologies from a single genus-0 template mesh. The key to our approach is a novel progressive shaping framework that alternates between mesh deformation and topology modification. While a deformation network predicts the per-vertex translations that reduce the gap between the reconstructed mesh and the ground truth, a novel topology modification network is employed to prune the error-prone faces, enabling the evolution of topology. By iterating over the two procedures, one can progressively modify the mesh topology while achieving higher reconstruction accuracy. Moreover, a boundary refinement network is designed to refine the boundary conditions to further improve the visual quality of the reconstructed mesh. Extensive experiments demonstrate that our approach outperforms the current state-of-the-art methods both qualitatively and quantitatively, especially for the shapes with complex topologies.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00321](http://arxiv.org/abs/1909.00321)

##### PDF
[http://arxiv.org/pdf/1909.00321](http://arxiv.org/pdf/1909.00321)

