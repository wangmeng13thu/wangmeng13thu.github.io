---

title: SuperMag
summary: _IEEE IROS'25_
subtitle: "SuperMag: Vision-based Tactile Data Guided High-resolution Tactile Shape Reconstruction for Magnetic Tactile Sensors -- _IEEE IROS'25_"
lastmod : 2025-10-12
tags:
  - TAC
  - RO
profile: false
share: false
show_date: false

links:
  - icon_pack: fas
    icon: link
    name: paper
    url: 'https://ieeexplore.ieee.org/abstract/document/11246193'
  # - icon_pack: fas
  #   icon: film
  #   name: video
  #   url: 'https://www.bilibili.com/video/BV1Gx41177ED'


image: 
  preview_only: true
---
Magnetic-based tactile sensors (MBTS) combine the advantages of compact design and high-frequency operation but suffer from limited spatial resolution due to their sparse taxel arrays. This paper proposes SuperMag, a tactile shape reconstruction method that addresses this limitation by leveraging high-resolution vision-based tactile sensor (VBTS) data to supervise MBTS super-resolution. Co-designed, open-source VBTS and MBTS with identical contact modules enable synchronized data collection of high-resolution shapes and magnetic signals via a symmetric calibration setup. We frame tactile shape reconstruction as a conditional generative problem, employing a conditional variational auto-encoder to infer high-resolution shapes from low-resolution MBTS inputs. The MBTS achieves a sampling frequency of 125Hz, whereas the shape reconstruction sustains an inference time within 2.5ms. This cross-modality synergy advances tactile perception of the MBTS, potentially unlocking its new capabilities in high-precision robotic tasks.

{{< video src="supermag.mp4" controls="yes" >}}