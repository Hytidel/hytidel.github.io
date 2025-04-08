---
collection: publications
category: preprint
premalink: /publication/dynamic-importance-and-uncertainty-in-unet
title: "Dynamic Importance in Diffusion U-Net for Enhanced Image Synthesis"
date: 2025-03-21
excerpt: "<b>Xi Wang</b>, Ziqi He, Yang Zhou<sup>†</sup>"
venue: ICME 2025
paperurl: "https://arxiv.org/abs/2504.03471"
---

**Xi Wang**, Ziqi He, Yang Zhou<sup>†</sup>

---

In this study, we first theoretically proved that, re-weighting the outputs of the Transformer blocks within the U-Net is a "free lunch" for improving the signal-to-noise ratio (SNR) during the sampling process. 
Next, we proposed *Importance Probe* to uncover and quantify the dynamic shifts in importance of the Transformer blocks throughout the denoising process. 
Finally, we design an adaptive importance-based re-weighting schedule tailored to specific image generation and editing tasks. 

Experimental results demonstrate that, our approach significantly improves the efficiency of the inference process, and enhances the aesthetic quality of the samples with identity consistency. 

Our method can be seamlessly integrated into any U-Net-based architecture. 

[Project page](https://github.com/Hytidel/UNetReweighting)

