---
title: Dynamic Filtering with Large Sampling Field for Convnets
publication_types: ['paper-conference']
authors:
  - Jialin Wu
  - Dai Li
  - Yu Yang
  - Chandrajit Bajaj
  - Xiangyang Ji
publication_short: ECCV 2018
abstract: We propose a dynamic filtering strategy with large sampling field for
  ConvNets (LS-DFN), where the position-specific kernels learn from not only the
  identical position but also multiple sampled neighbour regions. During
  sampling, residual learning is introduced to ease training and an attention
  mechanism is applied to fuse features from different samples. Such multiple
  samples enlarge the kernels’ receptive fields significantly without requiring
  more parameters. While LS-DFN inherits the advantages of DFN, namely avoiding
  feature map blurring by position-wise kernels while keeping translation
  invariance, it also efficiently alleviates the overfitting issue caused by
  much more parameters than normal CNNs. Our model is efficient and can be
  trained end-to-end via standard back-propagation. We demonstrate the merits of
  our LS-DFN on both sparse and dense prediction tasks involving object
  detection, semantic segmentation and flow estimation. Our results show LS-DFN
  enjoys stronger recognition abilities in object detection and semantic
  segmentation tasks on VOC benchmark and sharper responses in flow estimation
  on FlyingChairs dataset compared to strong baselines.
draft: false
featured: false
date: 2018-09-07T18:07:56.875Z
---
