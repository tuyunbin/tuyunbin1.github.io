---
title: "SMART: Syntax-calibrated Multi-Aspect Relation Transformer for Change Captioning"
collection: publications
permalink: /publication/2024-smart
excerpt: '**Yunbin Tu**, Liang Li, Li Su, Zheng-Jun Zha, Qingming Huang.


[[PDF](https://ieeexplore.ieee.org/abstract/document/10433795) [Code](https://github.com/tuyunbin/SMART)]


<h2>2023</h2>
---'

date: 2024-01-27
venue: 'IEEE Transactions on Pattern Analysis and Machine Intelligence  (TPAMI, Impact Factor:20.8), 46(07): 4926-4943, January'
---

Change captioning aims to describe the semantic change between two similar images. In this process, as the most typical distractor, viewpoint change leads to the pseudo changes about appearance and position of objects, thereby overwhelming the real change. Besides, since the visual signal of change appears in a local region with weak feature, it is difficult for the model to directly translate the learned change features into the sentence. In this paper, we propose a syntax-calibrated multi-aspect relation transformer to learn effective change features under different scenes, and build reliable cross-modal alignment between the change features and linguistic words during caption generation. Specifically, a multi-aspect relation learning network is designed to 1) explore the fine-grained changes under irrelevant distractors (e.g., viewpoint change) by embedding the relations of semantics and relative position into the features of each image; 2) learn two view-invariant image representations by strengthening their global contrastive alignment relation, so as to help capture a stable difference representation; 3) provide the model with the prior knowledge about whether and where the semantic change happened by measuring the relation between the representations of captured difference and the image pair. Through the above manner, the model can learn effective change features for caption generation. Further, we introduce the syntax knowledge of Part-of-Speech (POS) and devise a POS-based visual switch to calibrate the transformer decoder. The POS-based visual switch dynamically utilizes visual information during different word generation based on the POS of words. This enables the decoder to build reliable cross-modal alignment, so as to generate a high-level linguistic sentence about change. Extensive experiments show that the proposed method achieves the state-of-the-art performance on the three public datasets.

![](https://github.com/tuyunbin/tuyunbin.github.io/blob/master/images/vard_framework.png)

[Download paper here](https://ieeexplore.ieee.org/abstract/document/10433795)
