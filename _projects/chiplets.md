---
title: Chiplet-based Architecture Design

description: |
    A novel server scale 2.5-D manycore architecture called SWAP for deep learning (DL) applications.


layout: project
last-updated: 2023-06-12
---

Processing-in-memory (PIM) is a promising technique to accelerate deep learning (DL) workloads. Emerging DL workloads (e.g., ResNet with 152 layers) consist of millions of parameters, which increase the area and fabrication cost of monolithic PIM accelerators. The fabrication cost challenge can be addressed by 2.5-D systems integrating multiple PIM chiplets connected through a network-on-package (NoP). However, server-scale scenarios simultaneously execute multiple compute-heavy DL workloads, leading to significant interchiplet data volume. State-of-the-art NoP architectures proposed in the literature do not consider the nature of DL workloads. In this article, we propose a novel server scale 2.5-D manycore architecture called SWAP that accounts for the traffic characteristics of DL applications. Comprehensive experimental evaluations with different system sizes as well as diverse emerging DL workloads demonstrate that SWAP achieves significant performance and energy consumption improvements with much lower fabrication cost than state-of-the-art NoP topologies.

{:center: style="text-align: center"}
![image](/img/chiplets/overview.png){: width="80%"}
{:center}

## Articles 
* [Florets for Chiplets Talk (Youtube)](https://www.youtube.com/watch?v=4wa_UK5WCmg) - Harsh Sharma 

* [Accelerating the Future of Electronics:](https://medium.com/@harshari/accelerating-the-future-of-electronics-e23cc42d9d39) - Harsh Sharma @ Medium

* [Unlocking Pattern Thinking (1.0): A Fundamental Approach to Problem Solving](https://medium.com/@harshari/sfcunlocking-pattern-thinking-1-0-a-fundamental-approach-to-problem-solving-c10453ce4031) - Harsh Sharma @ Medium


## Publications

* {**BEST PAPER AWARD**}  Harsh Sharma, Lukas Pfromm, Rasit Onur Topaloglu, Janardhan Rao Doppa, Umit Y. Ogras, Ananth Kalyanraman, Partha Pratim Pande.[Florets for Chiplets: Data Flow-aware High-Performance and Energy-efficient Network-on-Interposer for CNN Inference Tasks](https://dl.acm.org/doi/10.1145/3608098). - ESWEEK Conference 2023. Published in ACM Transactions on Embedded Computing Systems Volume 22, September 2023

* {**BEST PAPER AWARD**} Harsh Sharma, Sumit K. Mandal, Jana Doppa, Umit Ogras and Partha Pratim Pande. [SWAP: A Server-Scale Communication-Aware Chiplet-Based Manycore PIM Accelerator](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9852792). - ESWEEK Conference 2022. Published in IEEE TRANSACTIONS ON COMPUTER-AIDED DESIGN OF INTEGRATED CIRCUITS AND SYSTEMS, VOL. 41, NO. 11, NOVEMBER 2022. 

* Harsh Sharma, Sumit K. Mandal, Jana Doppa, Umit Ogras and Partha Pratim Pande. [Achieving Datacenter-scale Performance through Chiplet-based Manycore Architectures](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10137125) - Published in 2023 Design, Automation & Test in Europe Conference (DATE 2023) held in Antwerp, Belgium. 