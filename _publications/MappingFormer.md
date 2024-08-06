---
title: "MappingFormer: Learning cross-modal feature mapping for visible-to-infrared image translation"
collection: publications
permalink: /publication/MappingFormer
excerpt: '<div class="paper"><font color="#0000dd">Haining Wang<sup>*</sup></font>, Na Li<sup>*</sup>, Huijie Zhao<sup>†</sup>, Yan Wen, Yi Su, and Yuqiang Fang</div>'
date: 2024-07-15
venue: ' <b>Proceedings of the 32nd ACM International Conference on Multimedia</b> (ACM MM 2024, CCF-A类会议)'
paperurl: 'https://openreview.net/forum?id=BDNtXFXO5n'
---

<div class="paper"><font color="#0000dd">Haining Wang<sup>*</sup></font>, Na Li<sup>*</sup>, Huijie Zhao<sup>†</sup>, Yan Wen, Yi Su, and Yuqiang Fang</div>

[Download paper here](https://openreview.net/forum?id=BDNtXFXO5n)

Due to the limitations of infrared image acquisition conditions, many essential tasks currently rely on visible images as the main source of training data. However, single-modal data makes it difficult for downstream networks to show optimal performance. Therefore, converting the more easily obtainable visible images into infrared images emerges as an effective remedy to alleviate the critical shortage of infrared data. Yet current methods typically focus solely on transferring visible images to infrared style, while overlooking the crucial infrared thermal feature during cross-modal translation. To elevate the authenticity of cross-model translation at the feature level, this paper introduces a translation network based on frequency feature mapping and dual patches contrast, MappingFormer, which can achieve cross-modal image generation from visible to infrared. Specifically, the generator incorporates two branches: low-frequency feature mapping (LFM) and high-frequency feature refinement (HFR), both have embedded the Swin Transformer blocks. The LFM branch captures the fuzzy structural from visible images, while the HFR focuses on mapping edge and texture features. The extracted dual-branch frequency features undergo refinement and fusion through cross-attention mechanisms. Additionally, a dual contrast learning mechanism based on feature patch (DFPC) is designed to infer effective mappings between unaligned cross-modal data. Numerous experimental results prove the effectiveness of this method in cross-modal feature mapping and image generation from visible to infrared. This method holds significant potential for downstream tasks where infrared data is limited.

<center> <img style=" border-radius: 0.3125em; box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" src="../images/MappingFormer.png" width="70%"> <br><div style=" color: orange; border-bottom: 1px solid #d9d9d9; display: inline-block; color: #999; padding: 2px;"> </div><p></p></center>
