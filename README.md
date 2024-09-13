# 📚 딥러닝 논문읽기 스터디

- 매주 본인이 읽고싶은 논문을 하나씩 리뷰하고 다른 사람들 앞에서 발표하는 스터디입니다.
- 발표는 매주 목요일 오후 8시에 [디스코드](https://discord.gg/3EU4GXtG)에서 진행하고 있습니다.

### Image Enhancement (이미지 개선)
|Title|Original Paper Link|Paper Review|reviewer|
|------|---|---|---|
|HDRUNet: Single Image HDR Reconstruction with Denoising and Dequantization|[Link](https://arxiv.org/pdf/2105.13084)|[Link](https://dohyeon.tistory.com/96)|윤도현|
|Replacing Mobile Camera ISP with a Single Deep Learning Model|[Link](https://openaccess.thecvf.com/content_CVPRW_2020/papers/w31/Ignatov_Replacing_Mobile_Camera_ISP_With_a_Single_Deep_Learning_Model_CVPRW_2020_paper.pdf)|[Link](https://dohyeon.tistory.com/103)|윤도현|

### Depth Estimation (깊이 측정)
|Title|Original Paper Link|Paper Review|reviewer|
|------|---|---|---|
|HITNet: Hierarchical Iterative Tile Refinement Network for Real-time Stereo Matching|[Link](https://arxiv.org/pdf/2007.12140)|[Link](https://dohyeon.tistory.com/91)|윤도현|

### 3D Reconstruction (3차원 복원)
|Title|Original Paper Link|Paper Review|reviewer|
|------|---|---|---|
|NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis|[Link](https://arxiv.org/abs/2003.08934)|[Link](https://dohyeon.tistory.com/92)|윤도현|
|3D Gaussian Splatting for Real-Time Radiance Field Rendering|[Link](https://arxiv.org/pdf/2308.04079)|[Link](https://ripe-myrtle-c69.notion.site/3D-Gaussian-Splatting-for-Real-Time-Radiance-Field-Rendering-a96a0b27b33046b481566301d96449fa?pvs=4)|이하정|

### Autonomous Driving (자율 주행)
|Title|Original Paper Link|Paper Review|reviewer|
|------|---|---|---|
|DETR3D: 3D Object Detection from Multi-view Images via 3D-to-2D Queries|[Link](https://arxiv.org/pdf/2110.06922)|[Link](https://dohyeon.tistory.com/94)|윤도현|
|Multi-Modal Fusion Transformer for End-to-End Autonomous Driving|[Link](https://arxiv.org/pdf/2104.09224)|[Link](https://ripe-myrtle-c69.notion.site/Multi-Modal-Fusion-Transformer-for-End-to-End-Autonomous-Driving-8398c1292035440a9afb4f1321533fc1?pvs=4)|이하정|
|BEVFusion: Multi-Task Multi-Sensor Fusion with Unified Bird’s-Eye View Representation|[Link](https://arxiv.org/pdf/2205.13542)|[Link](https://medium.com/@lth7234/bev-fusion-%EB%85%BC%EB%AC%B8-%EB%A6%AC%EB%B7%B0-059ebf6c23d8)|이태훈|

### LLM & Multi-modal (자연어처리 & 멀티모달)
|Title|Original Paper Link|Paper Review|reviewer|
|------|---|---|---|
|Visual Instruction Tuning|[Link](https://arxiv.org/pdf/2304.08485)|[Link](https://ripe-myrtle-c69.notion.site/Visual-Instruction-Tuning-47d50207618e49af8b208cd367eb6bf1?pvs=4)|이하정|
|LLaMA: Open and Efficient Foundation Language Models|[Link](https://arxiv.org/pdf/2302.13971)|[Link](https://ripe-myrtle-c69.notion.site/LLaMA-Open-and-Efficient-Foundation-Language-Models-984b585ae63d450a82489f781339b93e?pvs=4)|이하정|
|Text2Loc: 3D Point Cloud Localization from Natural Language|[Link](https://arxiv.org/pdf/2311.15977)|[Link](https://docs.google.com/presentation/d/1LekRr87Gu6Ealb8aZ4uac3q0ifQ9iFtw/edit?usp=sharing&ouid=102530899453259820171&rtpof=true&sd=true)|이하정|

### Model Compression (모델 경량화)
|Title|Original Paper Link|Paper Review|reviewer|
|------|---|---|---|
|Integer Quantization for Deep Learning Inference: Principles and Empirical Evaluation|[Link](https://arxiv.org/pdf/2004.09602)|[Link](https://dohyeon.tistory.com/99)|윤도현|
 
### etc (기타)
|Title|Original Paper Link|Paper Review|reviewer|
|------|---|---|---|
|DREAMFUSION: TEXT-TO-3D USING 2D DIFFUSION|[Link](https://arxiv.org/pdf/2209.14988)|[Link](https://ripe-myrtle-c69.notion.site/DREAMFUSION-TEXT-TO-3D-USING-2D-DIFFUSION-6fcf049f5ed94a45bcb2c0606329e027?pvs=4)|이하정|
|PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation|[Link](https://arxiv.org/pdf/1612.00593)|[Link](https://docs.google.com/presentation/d/1PpHCc6Soce7L5RebuxaLdj0kdA9G9seTRJrd4LEVOcY/edit#slide=id.p)|이태훈|
|Swin Transformer: Hierarchical Vision Transformer using Shifted Windows|[Link](https://arxiv.org/pdf/2103.14030)|[Link](https://medium.com/@lth7234/%EB%85%BC%EB%AC%B8%EB%A6%AC%EB%B7%B0-swin-transformer-hierarchical-vision-transformer-using-shifted-windows-bcb530509f4d)|이태훈|

### ✅ 약속
- 다음 발표자는 일요일 밤 23:59까지 본인이 리뷰할 논문을 [Issue](https://github.com/dohyeonYoon/Deep-Learning-Paper-Review/issues)에 등록해주세요.
- 발표가 끝나면 "**본인의 깃허브 브랜치**"에서 커밋한 뒤 당일 23:59까지 발표자료의 [PR](https://github.com/dohyeonYoon/Deep-Learning-Paper-Review/pulls)을 생성해주세요.

### 📋 커밋규칙
```
1. 저장소 local로 clone (최초 1번만)
$ git clone https://github.com/dohyeonYoon/Deep-Learning-Paper-Review.git

2. 먼저 본인의 로컬 메인 브랜치를 최신 상태로 업데이트 합니다.
$ git checkout main #메인 브랜치로 이동
$ git pull origin main #원격 저장소에서 최신 메인 브랜치 내용 받아오기
$ git checkout feature/ydh #작업 브랜치로 이동
$ git merge main #메인 브랜치 내용을 작업 브랜치에 병합

3. readme file을 수정하고 본인의 브랜치로 커밋
$ git add README.md
$ git commit -m "docs: 논문리뷰 추가, close #1" #본인의 이슈를 연동하고 PR이 병합되면 이슈닫힘
$ git push origin feature/ydh #작업 브랜치에 푸시

4. 깃허브에서 PR 생성
```

### 👨🏼‍💻 Members

<table align="center">
  <tr height="35px">
    <td align="center" width="320px">
      <a> 윤도현 </a>
    </td>
    <td align="center" width="320px">
      <a> 이하정 </a>
    </td>
    <td align="center" width="320px">
      <a> 이태훈 </a>
    </td>
  </tr>
  <tr height="35px">
    <td align="center" width="320px">
      <a href="https://github.com/dohyeonYoon"><img src="https://github.com/dohyeonYoon.png" width="100"></a>
    </td>
    <td align="center" width="320px">
      <a href="https://github.com/SS-hj"><img src="https://github.com/SS-hj.png" width="100">
    </td>
    <td align="center" width="320px">
      <a href="https://github.com/taehunlee990803"><img src="https://github.com/taehunlee990803.png" width="100">
    </td>
  </tr>
  <tr height="35px">
    <td align="center" width="320px">
      <a> Image Enhancement <br> 3D Computer Vision </a>
    </td>
    <td align="center" width="320px">
      <a> Computer Vision <br> Computer Graphics <br> Multi-modal </a>
    </td>
    <td align="center" width="320px">
      <a> Automous Driving </a>
    </td>
  </tr>
</table>