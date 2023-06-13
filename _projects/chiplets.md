---
title: Chiplet-based architecture design

description: |
    A novel server scale 2.5-D manycore architecture called SWAP for deep learning (DL) applications.


layout: project
last-updated: 2020-11-12
---

Cortex is an ongoing project that aims at building a compiler and runtime infrastructure that efficiently compiles ML applications with irregular and dynamic control flow and even irregular data structure accesses. To begin with, we have built a framework that can handle models with recursive data structure traversals, as shown in the figure below. For this case, we are able to completely disentangle the recursive traversal from the tensor computations and partially evaluate the former allowing us to offload the entire tensor computation to the accelerator (currently we support CPUs and GPUs) at once. This means that we can generate highly optimized implementations we avoid the costs of frequent communication between the accelerator and the host CPU.

{:center: style="text-align: center"}
![image](/img/cortex/overview.png){: width="80%"}
{:center}

## Publications

* {**BEST PAPER AWARD**} Harsh Sharma, Sumit K. Mandal, Jana Doppa, Umit Ogras and Partha Pratim Pande. [SWAP: A Server-Scale Communication-Aware Chiplet-Based Manycore PIM Accelerator](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9852792). - ESWEEK Conference 2023. Published in IEEE TRANSACTIONS ON COMPUTER-AIDED DESIGN OF INTEGRATED CIRCUITS AND SYSTEMS, VOL. 41, NO. 11, NOVEMBER 2022. 

* Harsh Sharma, Sumit K. Mandal, Jana Doppa, Umit Ogras and Partha Pratim Pande. [Achieving Datacenter-scale Performance through Chiplet-based Manycore Architectures](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10137125) - Published in 2023 Design, Automation & Test in Europe Conference (DATE 2023) held in Antwerp, Belgium. 