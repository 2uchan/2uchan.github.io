---
layout: page
title: Network Offloading System using Data Processing Unit (DPU)
description: a project with a background image and giscus comments
img: assets/img/DEPUTY.png
importance: 2
category: Graduate Research Assistant
giscus_comments: true
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/DEPUTY.png" title="deputy image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

CPU는 많은 프로세스들과 공유되어야 하므로 전체 시스템 병목의 원인

CPU 혼잡상황에서도 AI 워크로드와 같이 GPU에서 작업이 이뤄지는 프로세스들의 성능을 보장하기 위한 DEPUTY 시스템 제안

DPU의 ARM 프로세서와 DMA 엔진을 활용한 네트워크 오프로딩 기법 구현

DPU-GPU 공유메모리의 접근 횟수를 줄이기 위한 링버퍼 특성기반 공유 버퍼 접근법 개발

기존 DPU 네트워크 오프로딩 시스템에 비해 최대 1.96배 처리량 향상

연구결과물: IEEE BigData 2025 논문 1편, 국내 특허 1건 출원, 해외 특허(미국) 1건 진행중

Tool: C, RDMA, NVIDIA DPU Framework (DOCA)

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

