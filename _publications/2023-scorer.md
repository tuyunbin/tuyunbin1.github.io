---
title: "2023

Self-supervised Cross-view Representation Reconstruction for Change Captioning"
collection: publications
permalink: /publication/2023-scorer
excerpt: '**Yunbin Tu**, Liang Li, Li Su, Zheng-Jun Zha, Chenggang Yan, Qingming Huang.


[[PDF](https://openaccess.thecvf.com/content/ICCV2023/papers/Tu_Self-supervised_Cross-view_Representation_Reconstruction_for_Change_Captioning_ICCV_2023_paper.pdf) [Code](https://github.com/tuyunbin/SCORER) [Poster](https://drive.google.com/file/d/1_KLaOTl-o-fevQbT8zwAEAVlKPoufM_Z/view?usp=drive_link) [Supp.](https://openaccess.thecvf.com/content/ICCV2023/supplemental/Tu_Self-supervised_Cross-view_Representation_ICCV_2023_supplemental.pdf)]'

date: 2023-10-01
venue: 'ICCV (CCF-A, Full paper)'
---

Change captioning aims to describe the difference between a pair of similar images. Its key challenge is how to learn a stable difference representation under pseudo changes caused by viewpoint change. In this paper, we address this by proposing a self-supervised cross-view representation reconstruction (SCORER) network. Concretely, we first design a multi-head token-wise matching to model relationships between cross-view features from similar/dissimilar images. Then, by maximizing cross-view contrastive alignment of two similar images, SCORER learns two view-invariant image representations in a self-supervised way. Based on these, we reconstruct the representations of unchanged objects by cross-attention, thus learning a stable difference representation for caption generation. Further, we devise a cross-modal backward reasoning to improve the quality of caption. This module reversely models a "hallucination" representation with the caption and "before" representation. By pushing it closer  to the "after" representation, we enforce the caption to be informative about the difference in a self-supervised manner.  Extensive experiments show our method achieves the state-of-the-art  results on four datasets. 

![](https://github.com/tuyunbin/tuyunbin.github.io/blob/master/images/scorer_framework.png)

[Download paper here](https://openaccess.thecvf.com/content/ICCV2023/papers/Tu_Self-supervised_Cross-view_Representation_Reconstruction_for_Change_Captioning_ICCV_2023_paper.pdf)
