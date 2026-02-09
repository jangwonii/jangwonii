# 👋 이장원 | Computer Vision Research Engineer

산업 안전 · 이상행동 감지를 위한 **Computer Vision / 3D Perception AI**를 연구·개발하고 있습니다.  
실서비스를 고려한 **모델 설계–학습–배포 파이프라인** 구축에 강점이 있습니다.

---

## 🛠 Tech Stack

### 🔍 AI / Computer Vision
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLOv8/YOLO11-000000?style=flat)
![MMPose](https://img.shields.io/badge/MMPose-005BAC?style=flat)
![TAO Toolkit](https://img.shields.io/badge/NVIDIA%20TAO-76B900?style=flat&logo=nvidia&logoColor=white)
![Point Cloud](https://img.shields.io/badge/PointCloud-3D-blue?style=flat)

### 🧠 Domains
- Action Recognition (CCTV, 이상행동 탐지)
- Pose Estimation (2D/3D Skeleton)
- LiDAR / Point Cloud 3D Object Detection
- Multi-modal AI (Camera + LiDAR)

### ⚙️ Infra / DevOps
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat&logo=nvidia&logoColor=white)
![CVAT](https://img.shields.io/badge/CVAT-annotation-orange?style=flat)

---

## 🚀 Featured Projects

### 1️ 이상행동(Action) 인식 시스템 (CCTV 기반)
**문제**  
- 긴 행동(폭행 등)을 짧은 클립에서 정확히 인식하기 어려움  
- 실시간 추론 환경에서 오탐 최소화 필요

**해결**  
- 원자 행동(punch, kick, push 등) 중심 데이터 설계  
- NVIDIA TAO ARNet 기반 학습 파이프라인 구축  
- 클래스 재구성 및 LR/epoch 튜닝으로 성능 안정화

**기술**  
`PyTorch` · `TAO Toolkit` · `Action Recognition` · `Video AI`

🔗 Repo: https://github.com/your-id/your-action-recognition-repo

---

### 2️ LiDAR 기반 산업 안전 객체 인식 (PointPillars)
**문제**  
- 산업 현장에서 사람/차량/위험 객체를 3D로 정확히 인식해야 함  
- 대용량 Point Cloud 데이터 처리 필요

**해결**  
- PointPillars 기반 3D Object Detection 모델 학습  
- Voxelization, Anchor 튜닝 및 데이터 파이프라인 정리  
- 실제 현장 데이터 기준 성능 검증

**기술**  
`LiDAR` · `Point Cloud` · `PointPillars` · `3D Detection`

🔗 Repo: https://github.com/your-id/your-pointpillars-repo

---

### 3️ Pose 기반 이상상황 감지 파이프라인
**문제**  
- Bounding Box만으로는 미세한 행동 구분 한계  
- Skeleton 기반 분석 필요

**해결**  
- YOLO-Pose + MMPose 조합으로 Skeleton 추출  
- CVAT 자동 라벨링 파이프라인 구축  
- Pose sequence 기반 행동 분석 구조 설계

**기술**  
`YOLO-Pose` · `MMPose` · `CVAT` · `Pose Estimation`

🔗 Repo: https://github.com/your-id/your-pose-project-repo

---

## 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=your-id&show_icons=true&theme=tokyonight)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=your-id&layout=compact&theme=tokyonight)

---

## 📫 Contact

- 📧 Email: weun2002@dankook.ac.kr

---

> *“연구가 서비스로 이어지도록 만드는 엔지니어를 지향합니다.”*
