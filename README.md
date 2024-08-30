# 📚 딥러닝 논문읽기 스터디

- 매주 본인이 읽고싶은 논문을 하나씩 리뷰하고 다른 사람들 앞에서 발표하는 스터디입니다.
- 발표는 매주 목요일 오후 8시에 [디스코드](https://discord.gg/3EU4GXtG)에서 진행하고 있습니다.

### Image Enhancement (이미지 개선)
|Title|Original Paper Link|Paper Review|reviewer|
|------|---|---|---|
|HDRUNet: Single Image HDR Reconstruction with Denoising and Dequantization|[Link](https://arxiv.org/pdf/2105.13084)|[Link](https://dohyeon.tistory.com/96)|윤도현|

### Depth Estimation (깊이 측정)
|Title|Original Paper Link|Paper Review|reviewer|
|------|---|---|---|
|HITNet: Hierarchical Iterative Tile Refinement Network for Real-time Stereo Matching|[Link](https://arxiv.org/pdf/2007.12140)|[Link](https://dohyeon.tistory.com/91)|윤도현|

### 3D Reconstruction (3차원 복원)
|Title|Original Paper Link|Paper Review|reviewer|
|------|---|---|---|
|NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis|[Link](https://arxiv.org/abs/2003.08934)|[Link](https://dohyeon.tistory.com/92)|윤도현|

### Autonomous Driving (자율 주행)
|Title|Original Paper Link|Paper Review|reviewer|
|------|---|---|---|
|DETR3D: 3D Object Detection from Multi-view Images via 3D-to-2D Queries|[Link](https://arxiv.org/pdf/2110.06922)|[Link](https://dohyeon.tistory.com/94)|윤도현|

### Model Compression (모델 경량화)
|Title|Original Paper Link|Paper Review|reviewer|
|------|---|---|---|
|Integer Quantization for Deep Learning Inference: Principles and Empirical Evaluation|[Link](https://arxiv.org/pdf/2004.09602)|[Link](https://dohyeon.tistory.com/99)|윤도현|
  
  
### ✅ 약속
- 다음 발표자는 일요일 밤 23:59까지 본인이 리뷰할 논문을 [Issue](https://github.com/dohyeonYoon/Deep-Learning-Paper-Review/issues)에 등록해주세요.
- 발표가 끝나면 "**본인의 깃허브 브랜치**"에서 커밋한 뒤 당일 23:59까지 발표자료의 [PR](https://github.com/dohyeonYoon/Deep-Learning-Paper-Review/pulls)을 생성해주세요.

### 📋 커밋규칙
```
1. 먼저 본인의 로컬 메인 브랜치를 최신 상태로 업데이트 합니다.
$ git checkout main #메인 브랜치로 이동
$ git pull origin main #원격 저장소에서 최신 메인 브랜치 내용 받아오기
$ git checkout feature/ydh #작업 브랜치로 이동
$ git merge main #메인 브랜치 내용을 작업 브랜치에 병합

2. readme file을 수정하고 본인의 브랜치로 커밋
$ git add README.md
$ git commit -m "docs: 논문리뷰 추가, close #1" #본인의 이슈를 연동하고 PR이 병합되면 이슈닫힘
$ git push origin feature/ydh #작업 브랜치에 푸시

3. 깃허브에서 PR 생성
```
