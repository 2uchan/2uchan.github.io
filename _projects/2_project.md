---
layout: page
title: Network Offloading System using Data Processing Unit (DPU)
img: assets/img/DEPUTY.png
importance: 2
category: Graduate Research Assistant
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/DEPUTY.png" title="deputy image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Identified the CPU as a major system bottleneck due to contention among multiple processes.
Proposed DEPUTY, a system designed to guarantee the performance of GPU-driven workloads (e.g., AI inference) even under CPU congestion.
Implemented network offloading techniques leveraging the ARM processors and DMA engines of a DPU.
Developed a ring buffer–based shared memory access method to reduce access frequency to DPU–GPU shared memory.
Achieved up to 1.96× throughput improvement compared to existing DPU-based network offloading systems.

Outcomes: One publication in IEEE BigData 2025, one Korean patent filed, and one U.S. patent pending.
Tools: C, RDMA, NVIDIA DPU Framework (DOCA)

