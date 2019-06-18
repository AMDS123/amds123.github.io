---
layout: post
title: "Semi-Supervised Semantic Mapping through Label Propagation with Semantic Texture Meshes"
date: 2019-06-17 13:36:21
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Prediction SLAM
author: Radu Alexandru Rosu, Jan Quenzel, Sven Behnke
mathjax: true
---

* content
{:toc}

##### Abstract
Scene understanding is an important capability for robots acting in unstructured environments. While most SLAM approaches provide a geometrical representation of the scene, a semantic map is necessary for more complex interactions with the surroundings. Current methods treat the semantic map as part of the geometry which limits scalability and accuracy. We propose to represent the semantic map as a geometrical mesh and a semantic texture coupled at independent resolution. The key idea is that in many environments the geometry can be greatly simplified without loosing fidelity, while semantic information can be stored at a higher resolution, independent of the mesh. We construct a mesh from depth sensors to represent the scene geometry and fuse information into the semantic texture from segmentations of individual RGB views of the scene. Making the semantics persistent in a global mesh enables us to enforce temporal and spatial consistency of the individual view predictions. For this, we propose an efficient method of establishing consensus between individual segmentations by iteratively retraining semantic segmentation with the information stored within the map and using the retrained segmentation to re-fuse the semantics. We demonstrate the accuracy and scalability of our approach by reconstructing semantic maps of scenes from NYUv2 and a scene spanning large buildings.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07029](http://arxiv.org/abs/1906.07029)

##### PDF
[http://arxiv.org/pdf/1906.07029](http://arxiv.org/pdf/1906.07029)

