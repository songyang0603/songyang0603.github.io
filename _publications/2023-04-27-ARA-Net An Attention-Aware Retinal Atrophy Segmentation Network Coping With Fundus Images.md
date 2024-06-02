---
title: "ARA-Net: An Attention-Aware Retinal Atrophy Segmentation Network Coping With Fundus Images (JCR-Q2, Third author)"
collection: publications
permalink: /publication/2023-04-27-ARA-Net An Attention-Aware Retinal Atrophy Segmentation Network Coping With Fundus Image
excerpt: 'In this paper, An attention-aware retinal atrophy segmentation network (ARA-Net) is proposed to segment retinal atrophy areas from the 2D fundus image.'
date: 2023-04-27
venue: 'Frontiers in Neuroscience'
paperurl: 'https://doi.org/10.3389/fnins.2023.1174937'
citation: 'Chen L, Zhou YY, Gao SY, Li MY, Tan H, Wan ZJ. ARA-net: an attention-aware retinal atrophy segmentation network coping with fundus images. Frontiers in Neuroscience, 2023, 17: 1174937.'
---

## Abstract
**Background**: Accurately detecting and segmenting areas of retinal atrophy are paramount for early medical intervention in pathological myopia (PM). However, segmenting retinal atrophic areas based on a two-dimensional (2D) fundus image poses several challenges, such as blurred boundaries, irregular shapes, and size variation. To overcome these challenges, we have proposed an attention-aware retinal atrophy segmentation network (ARA-Net) to segment retinal atrophy areas from the 2D fundus image.

**Methods**: In particular, the ARA-Net adopts a similar strategy as UNet to perform the area segmentation. Skip self-attention connection (SSA) block, comprising a shortcut and a parallel polarized self-attention (PPSA) block, has been proposed to deal with the challenges of blurred boundaries and irregular shapes of the retinal atrophic region. Further, we have proposed a multi-scale feature flow (MSFF) to challenge the size variation. We have added the flow between the SSA connection blocks, allowing for capturing considerable semantic information to detect retinal atrophy in various area sizes.

**Results**: The proposed method has been validated on the Pathological Myopia (PALM) dataset. Experimental results demonstrate that our method yields a high dice coefficient (DICE) of 84.26%, Jaccard index (JAC) of 72.80%, and F1-score of 84.57%, which outperforms other methods significantly.

**Conclusion**: Our results have demonstrated that ARA-Net is an effective and efficient approach for retinal atrophic area segmentation in PM.

## Key words

retinal atrophy, segmentation, self-attention, multi-scale, 2D fundus images
