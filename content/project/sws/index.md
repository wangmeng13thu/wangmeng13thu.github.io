---

title: Single-wheeled Swarm
summary: _IEEE IROS'23_
subtitle: "Aggregating Single-wheeled Mobile Robots for Omnidirectional Movements -- _IEEE IROS'23_"
lastmod : 2023-10-05
tags:
  - RO
profile: false
share: false
show_date: false

links:
  - icon_pack: fas
    icon: link
    name: paper
    url: 'https://ieeexplore.ieee.org/abstract/document/10341772'
  # - icon_pack: fas
  #   icon: film
  #   name: video
  #   url: 'https://www.bilibili.com/video/BV1Gx41177ED'


image: 
  preview_only: true
---
This paper presents a novel modular robot system that can self-reconfigure to achieve omnidirectional movements for collaborative object transportation. Each robotic module is equipped with a steerable omni-wheel for navigation and is shaped as a regular icositetragon with a permanent magnet installed on each corner for stable docking. After aggregating multiple modules and forming a structure that can cage a target object, we have developed an optimization-based method to compute the distribution of all wheels' heading directions, which enables efficient omnidirectional movements of the structure. By implementing a hierarchical controller on our prototyped system in both simulation and experiment, we validated the trajectory tracking performance of an individual module and a team of six modules in multiple navigation and collaborative object transportation settings. The results demonstrate that the proposed system can maintain a stable caging formation and achieve smooth transportation, indicating the effectiveness of our hardware and locomotion designs.

{{< video src="sws.mp4" controls="yes" >}}